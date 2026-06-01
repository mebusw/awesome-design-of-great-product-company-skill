# Design System Inspiration of UPerform

## 1. Visual Theme & Atmosphere

UPerform（优普丰）是一家专业Scrum/敏捷咨询公司，品牌视觉采用国际设计标准 **4 层结构**: **PRIMARY（蓝色主色）+ NEUTRALS（灰色中性）+ SECONDARY（金色辅助）+ ACCENT（橙色点缀）**。各司其职——主色管品牌识别、灰色管功能支撑、金色管高级感、橙色管行动信号。

设计理念是"深邃、尊贵、活力"——深海蓝建立深邃感与权威性，灰色提供专业的文字层级支撑，尊贵金与香槟金为关键场景注入高端金属光泽，活力橙与珊瑚光作为行动信号让品牌年轻而不冰冷。**严格遵循 3 条铁律**:橙色全场 ≤ 3 处、金色永远搭配深色、文字只走灰阶。

**关键特征：**

- **PRIMARY 主色（60-70% 视觉量）** — 海洋蓝 `#1E4976` 为主，深海蓝 `#0A2540` 为深色背景，天空蓝 `#2E6BA8` / 地平蓝 `#4A8FD8` 为辅助与点缀蓝，冰川蓝 `#E8F2FC` 为浅蓝底
- **NEUTRALS 中性色（5 档工具集）** — 碳黑 `#1A1A1A` / 石板灰 `#3D4852` / 钢铁灰 `#6B7785` / 银灰 `#A8B2BD` / 雾白 `#F5F7FA` — 只做文字层级/边框/背景，不参与品牌识别
- **SECONDARY 辅助色（高级感 ≤ 3 处）** — 尊贵金 `#D4AF37` + 香槟金 `#F2D492` 金属光泽渐变，用于 VIP 标识、奖项、关键数字
- **ACCENT 点缀色（行动信号 ≤ 3 处）** — 活力橙 `#FF6B35` + 珊瑚光 `#FF9B7D`，用于 CTA 按钮、增长率
- 按钮圆角 6px — 柔和但不失专业
- 专业字体：宋体 / 思源黑体（中文）+ Source Sans Pro（英文）

## 2. Color Palette & Roles

### 品牌主色：蓝色系

| 名称 | HEX | 用途 |
|------|-----|------|
| Deep Sea Blue（深海蓝） | `#0A2540` | 最深背景、深色封面、页脚、Hero 深色段 |
| Ocean Blue（海洋蓝） | `#1E4976` | **品牌主色**，主要深色区块、大标题 |
| Sky Blue（天空蓝） | `#2E6BA8` | 按钮、链接、强调边框、活跃态 |
| Horizon Blue（地平蓝） | `#4A8FD8` | **品牌次色**，次级按钮、信息卡片、进度条 |
| Glacier Blue（冰川蓝） | `#E8F2FC` | 浅色信息背景、引用块、卡片底色 |

### 中性色：灰色系

| 名称 | HEX | 用途 |
|------|-----|------|
| Carbon Black（碳黑） | `#1A1A1A` | 最深正文、富黑强调 |
| Slate Grey（石板灰） | `#3D4852` | **强文本**，标题文字 |
| Steel Grey（钢铁灰） | `#6B7785` | **正文**，段落文字 |
| Silver Grey（银灰） | `#A8B2BD` | **边框**，分隔线 |
| Mist White（雾白） | `#F5F7FA` | **背景**，次级区块底色 |
| White | `#FFFFFF` | 纯白卡片、主背景 |

### 辅助色：金色系（真正的金属感）

| 名称 | HEX | 渐变描述 |
|------|-----|---------|
| Prestige Gold（尊贵金） | `#D4AF37` | 线性渐变 135°：`#E8C547` → `#D4AF37` → `#B8941F`，叠加白色高光 `rgba(255,255,255,0.3)`，1px 深色描边 `#9A7B1A` |
| Champagne Gold（香槟金） | `#F2D492` | 线性渐变 135°：`#FFF4D6` → `#F2D492` → `#D9BC6E`，叠加柔光 `rgba(255,248,220,0.2)`，无硬边框 |

**金色使用场景**：
- Prestige Gold：高级 CTA 按钮、关键徽章、奖项标识、强调条
- Champagne Gold：暖色高亮卡片、引用块背景、轻量级强调

### 点缀色：橙色系（年轻活力）

| 名称 | HEX | 用途 |
|------|-----|------|
| Vibrant Orange（活力橙） | `#FF6B35` | **主 Accent**，CTA 按钮、重要标注、活跃高亮 |
| Coral Light（珊瑚光） | `#FF9B7D` | **次 Accent**，次级高亮、暖色标签、图表辅助 |

### 4 层色彩体系速查 (PRIMARY / NEUTRALS / SECONDARY / ACCENT)

按国际设计标准(Material Design / IBM Carbon / Figma 等),严格说灰色不算"颜色",是"工具集"。这套配色采用 4 层结构,**各司其职**——主色管品牌识别、灰色管功能支撑、金色管高级感、橙色管行动信号。

| 层级 | 色系 | 代表色 | 视觉量 | 职责 |
|------|------|--------|--------|------|
| **PRIMARY** | 蓝色系 (5色) | 海洋蓝 `#1E4976` | 60–70% | 品牌识别 — 标题、品牌元素、关键数据 |
| **NEUTRALS** | 灰色系 (5色) | 碳黑/石板/钢铁/银/雾白 | 功能性 | 文字层级、边框、背景、阴影 |
| **SECONDARY** | 金色系 (2色) | 尊贵金 `#D4AF37` | 装饰性 | 高级感 — VIP 标识、奖项、关键强调 |
| **ACCENT** | 橙色系 (2色) | 活力橙 `#FF6B35` | 行动性 | CTA 按钮、重要提示(全场 ≤ 3 处) |

## 3. Typography Rules

### 字体家族

**中文：** 宋体 / 思源黑体（Noto Sans SC）/ 微软雅黑 / 苹方
**英文：** Source Sans Pro / Open Sans / Segoe UI

```html
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;600;700&family=Source+Sans+Pro:wght@300;400;600;700&display=swap" rel="stylesheet">
```

### 标题层级

| 级别 | 字号 | 字重 | 颜色 | 用途 |
|------|------|------|------|------|
| Display H1 | 48–60px | 700 | `#0A2540` 或 `#FFFFFF` | 封面大标题 |
| Page H2 | 32–36px | 700 | `#1E4976` | 页面主标题 |
| Section H3 | 24–28px | 600 | `#2E6BA8` | 区块标题 |
| Sub H4 | 20–22px | 600 | `#3D4852` | 子标题 |
| Label H5 | 16–18px | 500 | `#6B7785` | 标签、小标题 |
| Caption | 13–14px | 400 | `#6B7785` | 注释、说明 |

### 正文层级

| 级别 | 字号 | 行高 | 颜色 |
|------|------|------|------|
| Body Large | 18–20px | 1.7 | `#1A1A1A` |
| Body Base | 15–16px | 1.6 | `#1A1A1A` |
| Body Small | 13–14px | 1.5 | `#3D4852` |
| Muted | 12–13px | 1.4 | `#A8B2BD` |

### 设计原则
- **通过字重建立清晰层级**：H1/H2 使用 700（粗体），H3/H4 使用 600（次粗体），正文使用 400（常规）
- **一致的间距系统**：4/8/12/16/24/32/48/64/80/96px 间距系统
- **专业中文支持**：思源黑体提供优秀的中文字符渲染
- **按钮圆角 6px**：柔和但不失专业

## 4. Component Stylings

### 按钮

**Primary 按钮**
- Background: `#1E4976`
- Text: `#FFFFFF`
- Border: 2px solid `#1E4976`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#2E6BA8`, border `#2E6BA8`

**Accent / CTA 按钮（活力橙）**
- Background: `#FF6B35`
- Text: `#FFFFFF`
- Border: 2px solid `#FF6B35`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#E55A2B`, border `#E55A2B`

**Premium 按钮（尊贵金渐变）**
- Background: `linear-gradient(135deg, #E8C547 0%, #D4AF37 50%, #B8941F 100%)`
- Text: `#FFFFFF`
- Border: 1px solid `#9A7B1A`
- Padding: 10px 24px
- Radius: 6px
- 叠加白色高光：`box-shadow: inset 0 1px 0 rgba(255,255,255,0.3)`
- Hover: 加深渐变 + 轻微上浮

**Secondary 按钮（描边）**
- Background: transparent
- Text: `#4A8FD8`
- Border: 2px solid `#4A8FD8`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#4A8FD8`, text `#FFFFFF`

**Ghost 按钮（深色背景上）**
- Background: transparent
- Text: `#FFFFFF`
- Border: 2px solid `rgba(255,255,255,0.6)`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `rgba(255,255,255,0.15)`, border `#FFFFFF`

### 卡片

**标准卡片**
- Background: `#FFFFFF`
- Border: 1px solid `#A8B2BD`
- Radius: 8px
- Padding: 24px
- Shadow: `0 2px 8px rgba(10, 37, 64, 0.08)`

**深色卡片（深海蓝背景）**
- Background: `#0A2540`
- Color: `#FFFFFF`
- Radius: 8px
- Padding: 24px

**金色暖卡片（用于亮点、引用）**
- Background: `linear-gradient(135deg, #FFF4D6 0%, #F2D492 100%)`
- Border-left: 4px solid `#D4AF37`
- Radius: 0 8px 8px 0
- Padding: 16px 20px
- 叠加柔光：`box-shadow: inset 0 0 0 1px rgba(255,248,220,0.4)`

**信息卡片（冰川蓝背景）**
- Background: `#E8F2FC`
- Border-left: 4px solid `#4A8FD8`
- Radius: 0 8px 8px 0
- Padding: 16px 20px

**暖色卡片（橙色，用于重点提示）**
- Background: `#FFF0E8`（活力橙 8% 透明叠白）
- Border-left: 4px solid `#FF6B35`
- Radius: 0 8px 8px 0
- Padding: 16px 20px

### Header / Banner

**深色 Header（深海蓝渐变）**
- Background: `linear-gradient(135deg, #0A2540 0%, #1E4976 60%, #2E6BA8 100%)`
- Color: `#FFFFFF`
- Padding: 48px 64px

**章节 Banner**
- Background: `#1E4976`
- Color: `#FFFFFF`
- Padding: 32px 48px
- Border-left: 6px solid `#FF6B35`

**金色 Banner（高级封面）**
- Background: `linear-gradient(135deg, #0A2540 0%, #1E4976 50%, #D4AF37 100%)`
- Color: `#FFFFFF`
- Padding: 64px
- 叠加金属光泽

### 标签 / Badge

```css
.up-badge {
  display: inline-block;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 12px;
  font-weight: 600;
  letter-spacing: 0.5px;
}
.up-badge-primary  { background: #1E4976; color: #FFFFFF; }
.up-badge-accent   { background: #FF6B35; color: #FFFFFF; }
.up-badge-sky      { background: #4A8FD8; color: #FFFFFF; }
.up-badge-coral    { background: #FF9B7D; color: #FFFFFF; }
.up-badge-gold     { background: linear-gradient(135deg, #E8C547 0%, #D4AF37 50%, #B8941F 100%); color: #FFFFFF; border: 1px solid #9A7B1A; }
.up-badge-warm     { background: #F2D492; color: #0A2540; }
```

### 分隔线

```css
.up-divider         { border: none; border-top: 1px solid #A8B2BD; margin: 24px 0; }
.up-divider-accent  { border: none; border-top: 3px solid #FF6B35; margin: 24px 0; }
.up-divider-primary { border: none; border-top: 3px solid #1E4976; margin: 24px 0; }
.up-divider-gold    { border: none; border-top: 3px solid; background: linear-gradient(90deg, transparent 0%, #D4AF37 50%, transparent 100%); height: 3px; margin: 24px 0; }
```

## 5. Layout Principles

### 间距系统

```
4px | 8px | 12px | 16px | 24px | 32px | 48px | 64px | 80px | 96px
```

### 典型配色方案 (6 种场景)

| 场景 | 主色 (PRIMARY) | 辅助 (SECONDARY) | 点缀 (ACCENT) | 文字/底色 |
|------|---------------|----------------|--------------|----------|
| **A. 商务场景** | 深海蓝 `#0A2540` | 尊贵金 `#D4AF37` 渐变 | 活力橙 `#FF6B35` | 白色字 + 金字 + 金底白字按钮 |
| **B. 数字产品** | 雾白 `#F5F7FA` | 香槟金 `#F2D492` 渐变 | 海洋蓝 `#1E4976` | 金字 + 海洋蓝底白字按钮 |
| **C. 营销物料** | 天空蓝 `#2E6BA8` | 尊贵金 `#D4AF37` | 活力橙 `#FF6B35` | 白色字 + 金字 |
| **D. 年轻场景** | Sky Blue 天空蓝 | Champagne Gold 香槟金 | Energy Orange 活力橙 | 现代亲和 |
| **E. 专业场景** | Ocean Blue 海洋蓝 | Silver 银灰 | Coral Glow 珊瑚光 | 严谨专业 |
| **F. 商务场景 2** | Midnight Blue 深海蓝 | Prestige Gold 尊贵金 | Energy Orange 活力橙 | 经典奢华 |

### 幻灯片 / 培训材料设计规则 (三明治结构)

| 幻灯片类型 | 背景 (PRIMARY) | 标题色 | 正文色 (NEUTRALS) | 可用点缀 (SECONDARY + ACCENT) |
|-----------|----------------|--------|-------------------|----------------------------|
| 封面页 | 深海蓝 `#0A2540` | 雾白 `#F5F7FA` | 冰川蓝 `#E8F2FC` | 尊贵金 (品牌标识) + 海洋蓝 (辅助文字) |
| 章节分隔页 | 深海蓝 `#0A2540` | 雾白 `#F5F7FA` | 冰川蓝 `#E8F2FC` | 活力橙 (竖线装饰) + 尊贵金 (Logo) |
| 内容页 | 雾白 `#F5F7FA` 或 冰川蓝 `#E8F2FC` | 海洋蓝 `#1E4976` | 钢铁灰 `#6B7785` | 活力橙 (强调) + 天空蓝 (图表) |
| 引用/金句页 | 香槟金 `#F2D492` 渐变 | 碳黑 `#1A1A1A` | 石板灰 `#3D4852` | 尊贵金 (左边框装饰) |
| 数据/成果页 | 雾白 `#F5F7FA` | 碳黑 `#1A1A1A` | 石板灰 `#3D4852` | 尊贵金 (关键大数字) + 活力橙 (增长率) |
| 结尾/CTA 页 | 深海蓝 `#0A2540` | 雾白 `#F5F7FA` | 冰川蓝 `#E8F2FC` | 活力橙 (按钮) + 尊贵金 (品牌收尾) |

## 6. Depth & Elevation

| 层级 | 处理方式 | 用途 |
|------|---------|------|
| Base | 无阴影，纯色背景 | 标准内容区块 |
| Card Elevation | `0 2px 8px rgba(10, 37, 64, 0.08)` | 浅色背景上的标准卡片 |
| Header Elevation | 渐变背景 `#0A2540` → `#1E4976` → `#2E6BA8` | 英雄头部、章节横幅 |
| Premium Header | 蓝金渐变 `#0A2540` → `#1E4976` → `#D4AF37` | 高级封面、奖项页 |

**阴影理念**：UPerform 使用细腻、专业的阴影。主卡片阴影 (`0 2px 8px rgba(10, 37, 64, 0.08)`) 柔和且扩散，创造温和的抬升感而不戏剧化。头部区域使用渐变背景而非阴影来创造深度感。金色元素叠加柔光层 (`rgba(255, 248, 220, 0.2)`) 营造金属光泽。

## 7. Do's and Don'ts

### Do

**4 层体系使用规范**
- **PRIMARY 主色** 使用 `#1E4976`（海洋蓝），占 60-70% 视觉量
- **NEUTRALS 中性色** 只做功能支撑（文字/边/底），不参与品牌识别
- **SECONDARY 辅助色** 使用 `#D4AF37`（尊贵金）做高级感点缀
- **ACCENT 点缀色** 使用 `#FF6B35`（活力橙）做 CTA 按钮

**金色使用规范 DO'S**
- ✅ 高端元素、VIP 标识
- ✅ 奖项证书、荣誉展示
- ✅ 重要 CTA 按钮强调
- ✅ 品牌周年庆典素材
- ✅ 限量版产品标识
- ✅ 关键数字、Logo 旁点缀、签名

**排版与组件规范**
- 深色背景上的文字使用白色或 `#A8B2BD`
- 浅色信息块使用 `#E8F2FC`（冰川蓝）或 `#F5F7FA`（雾白）
- 按钮圆角使用 `6px`
- 间距使用官方间距系统（4/8/12/16/24/32/48/64/80/96px）
- 封面/Banner 使用深海蓝渐变 + 活力橙强调
- 高级场景使用蓝金渐变 + 香槟金高光

### Don't

**金色使用规范 DON'TS**
- ❌ 大面积背景色
- ❌ 正文字颜色
- ❌ 低对比度组合
- ❌ 过度使用（全场不超过 3 处金色元素）
- ❌ 与竞品金色混淆

**4 层体系反模式**
- ❌ 不使用品牌色系以外的颜色（如大红色、紫色）
- ❌ 不在深色背景上使用纯黑 `#000000`
- ❌ 不在冰川蓝上使用金色（会糊）
- ❌ 不让蓝/橙/金参与正文（正文只走灰色）
- ❌ 不把灰色升格为 "secondary" 抢蓝色品牌位
- ❌ 不在普通内容页强行使用金色渐变

### 三条使用铁律 (CRITICAL RULES)

1. **橙色是"放大镜"，不是"油漆"**
   整场不超过 3 处橙色元素（按钮 + 1-2 个关键数据），多了就失去强调意义。

2. **金色永远搭配深色**
   尊贵金 + 深海蓝 = 经典奢华；香槟金 + 雾白 = 轻柔优雅。
   **金色不要放在冰川蓝上（会糊）**。

3. **文字层级用灰色系统，蓝/橙/金不参与正文**
   正文只走 `#1A1A1A` → `#3D4852` → `#6B7785` 的灰阶。
   蓝是装饰色，不是文字色——避免大段海洋蓝文字，既疲劳又掉档次。

## 8. Responsive Behavior

### 断点

| 名称 | 宽度 | 关键变化 |
|------|-------|---------|
| Mobile | <640px | 单列，减少间距 |
| Tablet | 640–1024px | 双列网格，标准间距 |
| Desktop | >1024px | 完整布局，最大间距 |

### 折叠策略
- 卡片网格：多列 → 移动端单列
- 头部：按比例减少 padding
- 字体：较小屏幕上缩小标题
- 间距：使用更小的间距档位

## 9. Agent Prompt Guide

### 4 层色彩体系速查

```
PRIMARY        NEUTRALS                    SECONDARY         ACCENT
海洋蓝         碳黑/石板/钢铁/银/雾白     尊贵金/香槟金    活力橙/珊瑚光
```

- **PRIMARY**（品牌识别 60-70%）：深海蓝 `#0A2540` / 海洋蓝 `#1E4976` / 天空蓝 `#2E6BA8` / 地平蓝 `#4A8FD8` / 冰川蓝 `#E8F2FC`
- **NEUTRALS**（功能支撑）：碳黑 `#1A1A1A` / 石板灰 `#3D4852` / 钢铁灰 `#6B7785` / 银灰 `#A8B2BD` / 雾白 `#F5F7FA`
- **SECONDARY**（高级感点缀）：尊贵金 `#D4AF37` / 香槟金 `#F2D492`
- **ACCENT**（行动信号）：活力橙 `#FF6B35`（全场 ≤ 3 处）/ 珊瑚光 `#FF9B7D`

### 快速颜色参考
- 品牌主色：`#1E4976`（海洋蓝）
- 文字正文：`#1A1A1A` → `#3D4852` → `#6B7785`（灰阶）
- 边框分割：`#A8B2BD`（银灰）
- 浅色背景：`#F5F7FA`（雾白）/ `#E8F2FC`（冰川蓝）
- 高级强调：`#D4AF37`（尊贵金，全场 ≤ 3 处）
- 行动 CTA：`#FF6B35`（活力橙，全场 ≤ 3 处）

### 示例组件提示
- "创建英雄头部，渐变背景从 `#0A2540` 到 `#1E4976` 再到 `#2E6BA8`。标题 48px 思源黑体字重 700，白色文字。副标题 18px，颜色 `#A8B2BD`。下方添加 4px 强调条，使用从 `#FF6B35` 到 `#FF9B7D` 的渐变。"
- "设计内容卡片：白色背景，1px `#A8B2BD` 边框，8px 圆角，24px padding。标题 28px `#1E4976`。正文 16px `#1A1A1A`，行高 1.6。"
- "创建活力橙 CTA 按钮：`#FF6B35` 背景，白色文字，6px 圆角，10px 24px padding。15px Source Sans Pro 字重 600。"
- "创建尊贵金 Premium 按钮：金属渐变 `linear-gradient(135deg, #E8C547 0%, #D4AF37 50%, #B8941F 100%)`，1px `#9A7B1A` 描边，白色文字，6px 圆角，叠加 inset 高光 `rgba(255,255,255,0.3)`。"
- "构建冰川蓝信息框：`#E8F2FC` 背景，4px 左侧边框 `#4A8FD8`，16px 20px padding，0 8px 8px 0 圆角。"
- "构建香槟金暖色框：`linear-gradient(135deg, #FFF4D6 0%, #F2D492 100%)` 背景，4px 左侧边框 `#D4AF37`，叠加柔光。"
- "设计章节横幅：`#1E4976` 背景，白色文字，32px 48px padding，6px 左侧边框 `#FF6B35`。"
- "设计高级封面：背景渐变从 `#0A2540` → `#1E4976` → `#D4AF37`，标题用白色，装饰用香槟金高光。"

### 迭代指南 (4 层结构)

**PRIMARY 主色系（蓝色 60-70% 视觉量）**
1. 以海洋蓝 `#1E4976` 作为主色调 — 它奠定专业基调
2. 深海蓝 `#0A2540` 用于最深色块（深色 Header、页脚、封面）
3. 天空蓝 `#2E6BA8` 用于辅助蓝（二级标题、卡片顶条、hover 状态）
4. 地平蓝 `#4A8FD8` 用于点缀蓝（图标、链接、图表高亮）
5. 冰川蓝 `#E8F2FC` 用于浅蓝底（卡片底色、引用块、表格交替行）

**NEUTRALS 中性色系（灰色 5 档 — 工具集）**
6. 碳黑 `#1A1A1A` 用于极深文本（大标题）
7. 石板灰 `#3D4852` 用于强文本（小标题、关键句）
8. 钢铁灰 `#6B7785` 用于正文（不用纯黑，更柔和专业）
9. 银灰 `#A8B2BD` 用于边框/分割
10. 雾白 `#F5F7FA` 用于浅色背景（与冰川蓝二选一）

**SECONDARY 辅助色系（金色 — 高级感）**
11. 高级场景使用尊贵金 `#D4AF37` + 香槟金 `#F2D492` 渐变
12. **全场不超过 3 处金色元素**（VIP 标识、奖项、关键强调）

**ACCENT 点缀色系（橙色 — 行动信号）**
13. CTA 按钮使用活力橙 `#FF6B35`
14. 珊瑚光 `#FF9B7D` 用于次级 CTA、暖色标签
15. **橙色全场不超过 3 处**（按钮 + 1-2 个关键数据）

**三条铁律**
- 🔴 橙色是"放大镜"不是"油漆"，全场 ≤ 3 处
- 🟡 金色永远搭配深色（深海蓝/雾白），不要放冰川蓝上
- ⚪ 文字只走灰阶（`#1A1A1A` → `#3D4852` → `#6B7785`），蓝/橙/金不参与正文

**排版与组件**
- 保持所有角圆润但不过于柔软 — 按钮 6px，卡片 8px
- 使用 4/8/12/16/24/32/48/64/80/96px 系统保持一致的间距

### CSS 变量参考 (4 层结构)

```css
:root {
  /* ========== PRIMARY (品牌主色) - 蓝色系 ========== */
  --up-deep-sea:     #0A2540;   /* Deep Sea 深海蓝 - 深色背景 */
  --up-ocean:        #1E4976;   /* Ocean 海洋蓝 - 品牌主色 (60-70%) */
  --up-sky:          #2E6BA8;   /* Sky 天空蓝 - 辅助蓝/二级标题/hover */
  --up-horizon:      #4A8FD8;   /* Horizon 地平蓝 - 点缀蓝/图标/链接 */
  --up-glacier:      #E8F2FC;   /* Glacier 冰川蓝 - 浅蓝底/卡片底色 */

  /* ========== NEUTRALS (中性色) - 灰色系 ========== */
  /* 工具集:文字层级/边框/背景/阴影,不参与品牌识别 */
  --up-carbon:       #1A1A1A;   /* Carbon 碳黑 - 极深文本/大标题 */
  --up-slate:        #3D4852;   /* Slate 石板灰 - 强文本/小标题 */
  --up-steel-text:   #6B7785;   /* Steel 钢铁灰 - 正文 */
  --up-silver:       #A8B2BD;   /* Silver 银灰 - 边框/分割 */
  --up-mist:         #F5F7FA;   /* Mist 雾白 - 浅色背景 */
  --up-white:        #FFFFFF;

  /* ========== SECONDARY (辅助色) - 金色系 ========== */
  /* 高级感点缀:全场 ≤ 3 处,搭配深色使用 */
  --up-prestige:     #D4AF37;   /* Prestige 尊贵金 - 金重点 */
  --up-prestige-hi:  #E8C547;   /* 亮金高光 */
  --up-prestige-lo:  #B8941F;   /* 深金阴影 */
  --up-prestige-edge:#9A7B1A;   /* 金色描边 */
  --up-champagne:    #F2D492;   /* Champagne 香槟金 - 金柔光 */
  --up-champagne-hi: #FFF4D6;   /* 香槟金高光 */
  --up-champagne-lo: #D9BC6E;   /* 香槟金阴影 */

  /* ========== ACCENT (点缀色) - 橙色系 ========== */
  /* 行动信号:CTA 按钮,全场 ≤ 3 处 */
  --up-vibrant:      #FF6B35;   /* Vibrant 活力橙 - CTA */
  --up-vibrant-dark: #E55A2B;   /* 活力橙 hover */
  --up-coral:        #FF9B7D;   /* Coral 珊瑚光 - 柔强调/次 CTA */
}
```

---

## 相关资源

- 完整视觉规范：查看 `../uperform-visual-design/SKILL.md`
- 配色方案来源：`./优普丰品牌设计配色方案.md`
