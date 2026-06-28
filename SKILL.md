---
name: design-md-query
description: 查询指定公司/产品的设计系统（DESIGN.md）。当用户提到想了解某个品牌的设计风格、颜色、字体、UI规范，或者说"给我看看 X 的设计"、"查一下 spotify 的设计系统"、"帮我用 apple 风格"、"读取 design-md"、"用 XX 风格帮我做页面"等，立即使用本 skill。支持品牌关键词模糊匹配，例如输入 "apple"、"spotify"、"claude"、"vercel" 等均可触发。只要用户提到品牌名称 + 设计/风格/UI/颜色/字体，必须使用本 skill。
---

# Design-MD Query Skill

从 `docs/` 目录读取指定公司的 DESIGN.md，并以结构化方式呈现设计系统给用户或提供给 AI agent 使用。

## 每个品牌目录的文件结构

```
docs/<slug>/
├── DESIGN.md        ← 主设计系统文档（必读）
├── README.md        ← 简短说明
├── preview.html     ← 亮色预览页
└── preview-dark.html ← 暗色预览页
```

## 可用品牌完整列表（60个）

**AI & 机器学习**：claude, cohere, elevenlabs, minimax, mistral.ai, ollama, opencode.ai, replicate, runwayml, together.ai, x.ai

**开发者工具**：cursor, expo, linear.app, lovable, mintlify, posthog, raycast, resend, sentry, supabase, superhuman, vercel, warp, zapier

**基础设施 & 云**：clickhouse, composio, hashicorp, mongodb, sanity, stripe

**设计 & 生产力**：airtable, cal, clay, figma, framer, intercom, miro, notion, pinterest, webflow

**金融科技 & 加密**：coinbase, kraken, revolut, wise

**企业 & 消费品**：airbnb, apple, ibm, nvidia, spacex, spotify, uber

**汽车品牌**：bmw, ferrari, lamborghini, renault, tesla

**咨询服务**：scrum-alliance, uperform

## 工作流程

### Step 1：标准化关键词 → 目录 slug

| 用户可能输入 | 对应目录 slug |
|------------|-------------|
| mistral / mistral ai | mistral.ai |
| together / together ai | together.ai |
| opencode | opencode.ai |
| linear | linear.app |
| xai / grok | x.ai |
| cal / cal.com | cal |
| lambo / lamborghini | lamborghini |
| anthropic | claude |
| runway | runwayml |
| 其他品牌 | 直接小写，去空格 |

### Step 2：读取 DESIGN.md

```bash
cat docs/<slug>/DESIGN.md
```

**若 slug 不存在**，先模糊搜索：
```bash
ls docs/ | grep -i "<keyword>"
```
若仍无结果，列出完整品牌列表并推荐最相似的选项。

### Step 3：结构化呈现

读取后，按以下顺序整理输出：

1. **品牌一句话总结** — 设计哲学和整体氛围
2. **色彩系统** — 主色/辅色/背景色，附 hex 值
3. **字体规范** — 字体家族 + 字阶层级
4. **核心组件风格** — 按钮、卡片、输入框状态
5. **布局与间距** — 网格、spacing scale、留白哲学
6. **设计 Do's & Don'ts** — 核心规范与反模式
7. **Agent Prompt 片段** — 可直接粘贴给 AI 使用的快速参考

### Step 4：询问后续需求

展示完毕后主动询问：
- 是否需要基于此设计系统生成 UI 组件或页面？
- 是否需要将 DESIGN.md 内容输出为可复用的格式？

## 错误处理

| 情况 | 处理方式 |
|------|---------|
| slug 不存在 | 模糊匹配 + 列出完整品牌表 |
| DESIGN.md 缺失 | 列出目录内现有文件 |


## 使用示例

**用户**：查一下 Spotify 的设计  
→ `cat docs/spotify/DESIGN.md` → 展示鲜绿 #1DB954、暗色背景、Circular 字体等规范，和preview文件

**用户**：帮我用 Vercel 风格做个登录页  
→ 先读 `docs/vercel/DESIGN.md` → 提取设计 → 生成符合黑白精准美学的登录页

**用户**：给我看看 Mistral 的颜色  
→ slug 映射为 `mistral.ai` → `cat docs/mistral.ai/DESIGN.md` → 展示紫色调色板
