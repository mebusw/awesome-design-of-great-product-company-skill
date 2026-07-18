# Design System Inspiration of UPerform

## 1. Visual Theme & Atmosphere

UPerform（优普丰）是一家专业Scrum/敏捷咨询公司，品牌视觉采用国际设计标准 **3 层结构**: **PRIMARY（蓝色主色）+ NEUTRALS（灰色中性）+ SECONDARY（辅助色，可承担强调与点缀）**。各司其职——主色管品牌识别、灰色管功能支撑、辅助色管高级感与强调点缀。

设计理念是"深邃、尊贵、温润"——深海蓝建立深邃感与权威性，灰色提供专业的文字层级支撑，辅助色为关键场景注入高级感并承担强调与点缀职责。**SECONDARY 提供两套互斥的辅助色方案（任选其一，不可同屏出现）**：

- **方案 A：金色系** — Gold 金色 `#EABA1D` + Golden Glow 浅金 `#F2D677`，金属光泽渐变
- **方案 B：粉橙系** — Blush 粉橙 `#CE6E7B` + Peach 浅粉橙 `#FFC7B9`，温润柔和渐变

整套设计（一个项目/一个演示/一个品牌触点）只能选其中一套作为 SECONDARY，不能两套同时出现。

**严格遵循 4 条铁律**：

1. **🆕 SECONDARY 二选一** —— 一套设计中只允许出现一种 SECONDARY（金色 或 粉橙），不能同屏混用
2. **辅助色永远搭配深色或纯白** —— 金色 + 深海蓝 / 雾白；粉橙 + 深海蓝 / 白色
3. **文字只走灰阶**（蓝/辅助色不参与正文）
4. **🆕 辅助色一律使用渐变，禁止纯色** —— 金属色（Gold/Golden Glow）与温润色（Blush/Peach）都需要渐变才能呈现高级感。纯色使用 = 廉价感。大面积背景（卡片底色、Banner、章节页、Header）尤其禁止使用纯色。

**关键特征：**

- **PRIMARY 主色（60-70% 视觉量）** — 海洋蓝 `#1E4976` 为主，深海蓝 `#0A2540` 为深色背景，天空蓝 `#2E6BA8` / 地平蓝 `#4A8FD8` 为辅助与点缀蓝，冰川蓝 `#E8F2FC` 为浅蓝底
- **NEUTRALS 中性色（5 档工具集）** — 碳黑 `#1A1A1A` / 石板灰 `#3D4852` / 钢铁灰 `#6B7785` / 银灰 `#A8B2BD` / 雾白 `#F5F7FA` — 只做文字层级/边框/背景，不参与品牌识别
- **SECONDARY 辅助色（高级感 + 强调点缀，**二选一**）** —
  - **方案 A 金色系**：Gold `#EABA1D` + Golden Glow `#F2D677` 金属光泽渐变，用于 VIP 标识、奖项、关键数字
  - **方案 B 粉橙系**：Blush `#CE6E7B` + Peach `#FFC7B9` 温润柔和渐变，用于温暖亲和、女性向、年轻向场景
- 按钮圆角 6px — 柔和但不失专业
- 专业字体：思源黑体（Noto Sans SC）/ 微软雅黑（中文）+ Source Sans Pro（英文）

> ✅ **WCAG AA 合规状态**：主色蓝系（Ocean / Deep Sea）与白/冰川蓝/雾白的文字路径均 ≥ 8:1（AAA）；灰阶路径在合适场景下均达 AA；金/粉橙辅助色按钮统一为"渐变背景 + 海洋蓝深字"模式（CR ≥ 4.5）。详见 [§2 WCAG AA 合规速查](#wcag-aa-合规速查-正文-451--大字-31--ui-组件-31)。

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

| 名称 | HEX | 用途 | 禁忌 |
|------|-----|------|------|
| Carbon Black（碳黑） | `#1A1A1A` | 最深正文、富黑强调（亮色场景） | 暗色场景改用 `#FFFFFF` |
| Slate Grey（石板灰） | `#3D4852` | **强文本**，标题文字、跨场景安全 | — |
| Steel Grey（钢铁灰） | `#6B7785` | **正文**，段落文字（**仅亮色场景用**） | ❌ 暗色场景下用，CR 仅 3.41 |
| Silver Grey（银灰） | `#A8B2BD` | **边框**，分隔线 | ❌ 任何场景下做正文色（CR 2.15 / 2.81） |
| Mist White（雾白） | `#F5F7FA` | **背景**，次级区块底色 | — |
| White | `#FFFFFF` | 纯白卡片、主背景、深色场景正文 | ❌ 浅金/浅粉橙渐变背景上的文字 |

### 辅助色：两套互斥方案（**任选其一**）

> 🔒 **铁律 #4（必须遵守）**：辅助色（无论金色或粉橙）**任何位置、任何尺寸、任何用途都必须用渐变**。纯色使用 = 廉价感。下面的 hex 颜色值只用于**构造渐变的中间色**，而非"可直接当 background-color 用的纯色"。
> 🔒 **铁律 #1（必须遵守）**：两套方案 **互斥**，一套设计中只能选其一。

#### 方案 A：金色系（Gold + Golden Glow）—— 金属光泽、高级奢华

| 名称 | HEX | 渐变描述 |
|------|-----|---------|
| Gold（金色） | `#EABA1D` | 线性渐变 135°：`#F0CC44` → `#EABA1D` → `#B8950F`，叠加白色高光 `rgba(255,255,255,0.3)` |
| Golden Glow（浅金） | `#F2D677` | 线性渐变 135°：`#FFE9B0` → `#F2D677` → `#D9BC4D`，叠加柔光 `rgba(255,248,220,0.2)`，无硬边框 |

#### 方案 B：粉橙系（Blush + Peach）—— 温润亲和、现代柔和

| 名称 | HEX | 渐变描述 |
|------|-----|---------|
| Blush（粉橙） | `#CE6E7B` | 线性渐变 135°：`#E89AA4` → `#CE6E7B` → `#A85566`，叠加柔光 `rgba(255,220,210,0.25)` |
| Peach（浅粉橙） | `#FFC7B9` | 线性渐变 135°：`#FFE0D7` → `#FFC7B9` → `#E89F8E`，无硬边框 |

**渐变构造公式（必须照搬，不可降级为纯色）**：

```css
/* 方案 A — 金色渐变（用于按钮、深色背景文字） */
background: linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%);

/* 方案 A — 浅金渐变（用于浅色背景、暖卡片） */
background: linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%);

/* 方案 A — 金色文字渐变（深海蓝/海洋蓝渐变背景上专用） */
color: transparent;
background: linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);
-webkit-background-clip: text;
background-clip: text;
-webkit-text-fill-color: transparent;

/* 方案 B — 粉橙渐变（用于按钮、深色背景文字） */
background: linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%);

/* 方案 B — 浅粉橙渐变（用于浅色背景、暖卡片） */
background: linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%);

/* 方案 B — 粉橙文字渐变（深海蓝/海洋蓝渐变背景上专用） */
color: transparent;
background: linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);
-webkit-background-clip: text;
background-clip: text;
-webkit-text-fill-color: transparent;
```

**辅助色使用场景**：

| 方案 | 文字（深海蓝/海洋蓝渐变背景上） | 渐变背景 + 文字 | 适用场景 |
|------|-------------------------------|----------------|---------|
| **A 金色系** | 深海蓝渐变 `#0A2540→#1E4976` + 金字渐变 `#F0CC44→#F2D677→#EABA1D` | 金色渐变背景 + **海洋蓝文字** `#1E4976` | VIP 标识、奖项、关键大数字、高端封面 |
| **B 粉橙系** | 深海蓝渐变 `#0A2540→#1E4976` + 粉橙字渐变 `#E89AA4→#FFC7B9→#CE6E7B` | 粉橙渐变背景 + **白色文字** `#FFFFFF` | 温暖场景、女性向、年轻向、亲和 CTA |

> ⚠️ 关键细节：**辅助色文字**必须用 `background-clip: text` 渐变技术，绝对不能直接写 `color: #EABA1D` 或 `color: #CE6E7B`——那会让字看起来像贴上去的廉价贴纸。渐变 + 深蓝底 = 高级感的灵魂。

### 3 层色彩体系速查 (PRIMARY / NEUTRALS / SECONDARY)

按国际设计标准(Material Design / IBM Carbon / Figma 等),严格说灰色不算"颜色",是"工具集"。这套配色采用 3 层结构,**各司其职**——主色管品牌识别、灰色管功能支撑、辅助色管高级感与强调点缀。

| 层级 | 色系 | 代表色 | 视觉量 | 职责 |
|------|------|--------|--------|------|
| **PRIMARY** | 蓝色系 (5色) | 海洋蓝 `#1E4976` | 60–70% | 品牌识别 — 标题、品牌元素、关键数据 |
| **NEUTRALS** | 灰色系 (5色) | 碳黑/石板/钢铁/银/雾白 | 功能性 | 文字层级、边框、背景、阴影 |
| **SECONDARY** | 辅助色 (2 套互斥) | A. 金色 `#EABA1D` / B. 粉橙 `#CE6E7B` | 装饰性 / 强调性 | 高级感 + 强调点缀 — VIP 标识、奖项、关键强调（≤ 3 处） |

### WCAG AA 合规速查 (正文 4.5:1 · 大字 3:1 · UI 组件 3:1)

> 测算方法：相对亮度 `L = 0.2126·R + 0.7152·G + 0.0722·B`（sRGB→linear），对比度 `CR = (L₁+0.05)/(L₂+0.05)`。

#### 关键色值相对亮度

| 色名 | HEX | L |
|------|-----|---|
| Deep Sea 深海蓝 | `#0A2540` | 0.0175 |
| Ocean 海洋蓝 | `#1E4976` | 0.0636 |
| Sky 天空蓝 | `#2E6BA8` | 0.1394 |
| Horizon 地平蓝 | `#4A8FD8` | 0.2610 |
| Glacier 冰川蓝 | `#E8F2FC` | 0.8770 |
| Mist 雾白 | `#F5F7FA` | 0.9282 |
| White | `#FFFFFF` | 1.0000 |
| Carbon 碳黑 | `#1A1A1A` | 0.0103 |
| Slate 石板灰 | `#3D4852` | 0.0624 |
| Steel 钢铁灰 | `#6B7785` | 0.1803 |
| Silver 银灰 | `#A8B2BD` | 0.4385 |
| Gold 金 | `#EABA1D` | 0.5268 |
| Blush 粉橙 | `#CE6E7B` | 0.2570 |
| **#C8D1DA** (导航辅助) | `#C8D1DA` | 0.6265 |

#### ✅ 文字 × 背景 对比度（合规组合）

| 文字 | 背景 | CR | 阈值 | 用途 |
|------|------|-----|------|------|
| `#FFFFFF` | Ocean / Deep Sea | 9.24 / 13.73 | ≥ 4.5 ✅ AAA | Hero、品牌主色按钮 |
| `#FFFFFF` | Glacier | 8.16 | ≥ 4.5 ✅ AAA | 卡片正文 |
| Ocean `#1E4976` | Glacier | 8.16 | ≥ 4.5 ✅ AAA | 信息卡片标题 |
| Carbon `#1A1A1A` | White / Mist | 17.41 / 15.5+ | ≥ 4.5 ✅ AAA | 标题、富黑强调 |
| Slate `#3D4852` | White | 9.34 | ≥ 4.5 ✅ AAA | 强文本、H3/H4 |
| Sky `#2E6BA8` | White | 5.54 | ≥ 4.5 ✅ AA | section-label |
| Steel `#6B7785` | White | 4.56 | ≥ 4.5 ✅ AA (临界) | 亮色场景正文（仅白底） |
| Silver `#A8B2BD` | Deep Sea | 7.24 | ≥ 4.5 ✅ AAA | 暗色场景正文、深底边框 |
| `#C8D1DA` | Ocean | 5.96 | ≥ 4.5 ✅ AA | Ocean 背景上的次级链接 |
| Ocean `#1E4976` | Gold 渐变 (mid) | 5.08 | ≥ 4.5 ✅ AA | 金色按钮文字（**font-weight ≥ 600**） |
| Ocean `#1E4976` | Blush 渐变 (mid) | 4.55 | ≥ 4.5 ✅ AA | 粉橙按钮文字（**font-weight ≥ 600**） |
| Gold 渐变 | Deep Sea 渐变 | 8.5–10.9 | ≥ 4.5 ✅ AAA | 海洋蓝+金字卡片标题 |
| Blush 渐变 | Deep Sea 渐变 | 4.55–10.45 | ≥ 4.5 ✅ AA | 海洋蓝+粉橙字卡片标题 |

#### ❌ 系统性反模式（这些组合不能用作正文色）

| 失败组合 | CR | 失败原因 |
|---------|-----|---------|
| `#FFFFFF` on Gold 渐变 | 1.6–1.8 | 浅色底 + 白字 = 油漆感 |
| `#FFFFFF` on Blush 渐变 | 2.2–3.4 | 同上 |
| Silver `#A8B2BD` on White | 2.15 | 边框色当正文，亮场景下消失 |
| Steel `#6B7785` on Mist `#F5F7FA` | 4.25 | 浅底上钢灰不够深 |
| Steel `#6B7785` on Glacier `#E8F2FC` | 4.03 | 浅底上钢灰不够深 |
| Steel `#6B7785` on Deep Sea | 3.41 | 暗色场景下钢灰消失 |
| Silver `#A8B2BD` on Ocean | 4.30 | 海洋蓝背景上银灰差 0.20 |
| Horizon `#4A8FD8` on White | 3.38 | 地平蓝作正文色不够深 |
| Horizon `#4A8FD8` on Ocean | 2.74 | 地平蓝在深底上变深（背景对它而言偏深） |
| Gold-lo `#B8950F` on Mist | 2.64 | 渐变最深端作正文色 |

#### 6 项系统修复（一次性覆盖全部 AA 失败）

| # | 位置 | 旧 | 新 | 旧 CR → 新 CR |
|---|------|------|------|--------------|
| 1 | `.up-btn-secondary`（金按钮） | `#FFFFFF` on 金渐变 | `#1E4976` Ocean + `font-weight:700` | 1.6–1.8 → 5.08+ |
| 2 | `.up-btn-blush`（粉橙按钮） | `#FFFFFF` on 粉橙渐变 | `#1E4976` Ocean + `font-weight:600` | 2.2–3.4 → 4.55+ |
| 3 | `.nav-links a`（亮色版） | Silver on Ocean | `#C8D1DA` + `font-weight:600` | 4.30 → 5.96 |
| 4 | `.color-swatch-role` | Silver on White | Steel `#6B7785` | 2.15 → 4.56 |
| 5 | `.type-meta` / `.spacing-value` / `.radius-label` 等 | Steel on 浅底 | Slate `#3D4852` | 4.03–4.25 → 8.7+ |
| 6 | `.up-btn-sky` / `.badge-sky` | Horizon on White | Sky `#2E6BA8` | 3.38 → 5.54 |

> 暗色版（`preview-dark.html`）沿用同根原则，但用色对调：**浅底场景用 Steel/Silver（暗底 CR 7.24+），深字场景用 Ocean/Deep Sea。** Silver 在深底上是合规正文色（7.24），在浅底上不是（2.15）；Sky 反过来，深底上变深（2.81），浅底上合规（5.54）。

#### 角色纪律（系统级规则）

1. **辅助色渐变背景上的文字必须是 Ocean `#1E4976` 或更深**（`font-weight ≥ 600`），绝不 `#FFFFFF`。
2. **Silver `#A8B2BD` 只做边框（1px decorative），不做正文色**。在亮色场景下做正文会消失（2.15）。
3. **Steel `#6B7785` 仅在白底做正文**。一旦落在 Mist/Glacier 浅底或深底上，必须升级为 Slate。
4. **Horizon `#4A8FD8` 永远不当正文色**。在亮底 CR 3.38，在深底 2.74 — 两个场景都不过。它是装饰/图标色，不是文字色。
5. **正文落地前先看背景**：浅底（White/Mist/Glacier）走 Carbon/Slate/Steel 三阶梯；深底（Deep Sea/Ocean）走 White/Glacier/Silver 三阶梯；浅金/浅粉橙渐变底走 Ocean。

## 3. Typography Rules

### 字体家族

**中文：** 思源黑体（Noto Sans SC）/ 微软雅黑
**英文：** Source Sans Pro

```html
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;600;700&family=Source+Sans+Pro:wght@400;600;700&display=swap" rel="stylesheet">
```

### 标题层级

| 级别 | 字号 | 字重 | 颜色 | 用途 |
|------|------|------|------|------|
| Display H1 | 48–60px | 700 | `#1A1A1A`（亮色）/ `#FFFFFF`（暗色） | 封面大标题 |
| Page H2 | 32–36px | 700 | `#1E4976`（亮色）/ `#FFFFFF`（暗色） | 页面主标题 |
| Section H3 | 24–28px | 600 | `#3D4852`（亮色）/ `#4A8FD8`（暗色） | 区块标题 |
| Sub H4 | 20–22px | 600 | `#3D4852`（亮色）/ `#FFFFFF`（暗色） | 子标题 |
| Caption | 13–14px | 400 | `#6B7785` | 注释、说明 |

### 正文层级

| 级别 | 字号 | 行高 | 颜色 |
|------|------|------|------|
| Body Base | 15–16px | 1.6 | `#1A1A1A`（亮色）/ `#A8B2BD`（暗色） |
| Caption | 13–14px | 1.5 | `#6B7785` |

### 设计原则
- **通过字重建立清晰层级**：H1/H2 使用 700（粗体），H3/H4 使用 600（次粗体），正文使用 400（常规）
- **一致的间距系统**：4/8/12/16/24/32/48/64/80/96px 间距系统
- **专业中文支持**：思源黑体提供优秀的中文字符渲染
- **按钮圆角 6px**：柔和但不失专业

## 4. Component Stylings

> 🆕 **二选一规则**：下方金色/粉橙组件，二选一使用，**不可同屏混用**。

### 按钮

**Primary 按钮**
- Background: `#1E4976`
- Text: `#FFFFFF`
- Border: 2px solid `#1E4976`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#2E6BA8`, border `#2E6BA8`

**方案 A — 金色 Premium 按钮（金色系专用）**
- Background: `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)`
- Text: `#1E4976`（**海洋蓝**——AA 合规，深字配浅渐变底）
- Border: 1px solid `#9A7B1A`
- Padding: 10px 24px
- Radius: 6px
- **Font-weight: 700**（粗体加重深字，提升金色最深端可读性）
- 叠加白色高光：`box-shadow: inset 0 1px 0 rgba(255,255,255,0.3)`
- Hover: 加深渐变 + 轻微上浮

**方案 B — 粉橙 Premium 按钮（粉橙系专用）**
- Background: `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)`
- Text: `#1E4976`（**海洋蓝**——AA 合规，深字配浅渐变底）
- Border: 1px solid `#8B4754`
- Padding: 10px 24px
- Radius: 6px
- **Font-weight: 600**（粗体加重深字）
- 叠加柔光：`box-shadow: inset 0 1px 0 rgba(255,220,210,0.3)`
- Hover: 加深渐变 + 轻微上浮

**Secondary 按钮（描边）**
- Background: transparent
- Text: `#2E6BA8`（**天空蓝**，Horizon 在浅底上 CR 仅 3.38 不过 AA，换 Sky CR 5.54 ✅）
- Border: 2px solid `#2E6BA8`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#2E6BA8`, text `#FFFFFF`

**Ghost 按钮（深色背景上）**
- Background: transparent
- Text: `#FFFFFF`
- Border: 2px solid `rgba(255,255,255,0.6)`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `rgba(255,255,255,0.15)`, border `#FFFFFF`

**方案 A — 金色渐变背景 + 海洋蓝文字按钮（金色系专用）**
- Background: `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)`
- Text: `#1E4976`（海洋蓝）
- Border: 1px solid `#9A7B1A`
- Padding: 10px 24px
- Radius: 6px
- Font-weight: 700

**方案 B — 粉橙渐变背景 + 海洋蓝文字按钮（粉橙系专用）**
- Background: `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)`
- Text: `#1E4976`（海洋蓝）
- Border: 1px solid `#8B4754`
- Padding: 10px 24px
- Radius: 6px
- Font-weight: 600

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

**方案 A — 金色暖卡片（金色系专用，用于亮点、引用）**
- Background: `linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%)`（**渐变，绝不纯色**）
- Border-left: 4px（**金色渐变描边**）：`linear-gradient(180deg, #F0CC44 0%, #B8950F 100%)`
- Radius: 0 8px 8px 0
- Padding: 16px 20px
- 叠加柔光：`box-shadow: inset 0 0 0 1px rgba(255,248,220,0.4)`

**方案 B — 粉橙暖卡片（粉橙系专用，用于温暖引用、亲和提示）**
- Background: `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)`（**Blush 渐变，绝不纯色**）
- Border-left: 4px（**粉橙渐变描边**）：`linear-gradient(135deg, #E89AA4 0%, #A85566 100%)`
- Radius: 0 8px 8px 0
- Padding: 16px 20px
- 叠加柔光：`box-shadow: inset 0 1px 0 rgba(255,220,210,0.25)`
- 文字：标题白色 `#FFFFFF`，正文 `rgba(255,255,255,0.85)`

**🆕 海洋蓝 + 辅助色文字卡片（标志性组合）**

深邃的海洋蓝铺底，辅助色渐变文字浮于其上，营造"深海藏光"的视觉张力。

| 方案 | Background | 文字渐变 | Border-left 渐变 |
|------|-----------|---------|-----------------|
| A 金色 | 深海蓝渐变 `linear-gradient(135deg, #0A2540 0%, #1E4976 100%)` | 金字渐变 `#F0CC44 → #F2D677 → #EABA1D` | `linear-gradient(180deg, #F0CC44 0%, #B8950F 100%)` |
| B 粉橙 | 深海蓝渐变 `linear-gradient(135deg, #0A2540 0%, #1E4976 100%)` | 粉橙字渐变 `#E89AA4 → #FFC7B9 → #CE6E7B` | `linear-gradient(180deg, #E89AA4 0%, #A85566 100%)` |

- Title 颜色：**辅助色文字渐变**（`background-clip: text`）：
  ```css
  /* 方案 A */
  background: linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);
  /* 方案 B */
  background: linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  ```
- Body 颜色：`#E8F2FC`（冰川蓝）或 `#FFFFFF`
- Radius: 0 8px 8px 0
- Padding: 16px 20px
- 阴影：`box-shadow: 0 4px 16px rgba(10, 37, 64, 0.3)`（深色卡片需要更深的阴影）
- 适用：高端引用、VIP 标识、奖项展示、关键数据高亮

**信息卡片（冰川蓝背景）**
- Background: `#E8F2FC`
- Border-left: 4px solid `#4A8FD8`
- Radius: 0 8px 8px 0
- Padding: 16px 20px

### Header / Banner

**深色 Header（深海蓝渐变）**
- Background: `linear-gradient(135deg, #0A2540 0%, #1E4976 60%, #2E6BA8 100%)`
- Color: `#FFFFFF`
- Padding: 48px 64px

### 标签 / Badge

> 🆕 **二选一规则**：金色 badge 与粉橙 badge 互斥,不可同屏混用。

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
.up-badge-sky      { background: transparent; color: #2E6BA8; border: 1px solid #2E6BA8; }  /* 浅底用 Sky(5.54)，深底用 Silver(7.24) */

/* 方案 A — 金色系 Badge */
.up-badge-gold     { background: linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%); color: #1E4976; border: 1px solid #9A7B1A; font-weight: 700; }
.up-badge-warm     { background: linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%); color: #1A1A1A; }

/* 方案 B — 粉橙系 Badge */
.up-badge-blush    { background: linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%); color: #1E4976; border: 1px solid #8B4754; font-weight: 600; }
.up-badge-peach    { background: linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%); color: #1A1A1A; }

/* 🆕 方案 A — 海洋蓝 + 金字渐变 badge (标志性奢华) */
.up-badge-ocean-gold {
  background: #1E4976;
  border: 1px solid transparent;
  background-image: linear-gradient(#1E4976, #1E4976),
                    linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);
  background-origin: border-box;
  background-clip: padding-box, border-box;
  position: relative;
}
.up-badge-ocean-gold span {
  background: linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
  letter-spacing: 1px;
}

/* 🆕 方案 B — 海洋蓝 + 粉橙字渐变 badge (标志性格式) */
.up-badge-ocean-blush {
  background: #1E4976;
  border: 1px solid transparent;
  background-image: linear-gradient(#1E4976, #1E4976),
                    linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);
  background-origin: border-box;
  background-clip: padding-box, border-box;
  position: relative;
}
.up-badge-ocean-blush span {
  background: linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
  letter-spacing: 1px;
}

/* 🆕 方案 A — 深海蓝 + 浅金字渐变 badge (更深邃版本) */
.up-badge-deep-gold {
  background: linear-gradient(135deg, #0A2540 0%, #1E4976 100%);
  border: 1px solid rgba(234, 186, 29, 0.4);
  box-shadow: inset 0 1px 0 rgba(255, 215, 100, 0.15);
}
.up-badge-deep-gold span {
  background: linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  letter-spacing: 1px;
}

/* 🆕 方案 B — 深海蓝 + 浅粉橙字渐变 badge (更深邃版本) */
.up-badge-deep-blush {
  background: linear-gradient(135deg, #0A2540 0%, #1E4976 100%);
  border: 1px solid rgba(206, 110, 123, 0.4);
  box-shadow: inset 0 1px 0 rgba(255, 200, 190, 0.15);
}
.up-badge-deep-blush span {
  background: linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  letter-spacing: 1px;
}
```

**Badge 使用指南（3 类 + 2 套二选一）**：

| Badge | 底色 | 文字 | 适用场景 |
|-------|------|------|---------|
| `up-badge-primary` | 海洋蓝纯色 `#1E4976` | 白色 | 普通标签 |
| `up-badge-sky` | 透明 + 地平蓝描边 `#4A8FD8` | 地平蓝 `#4A8FD8` | 描边标签 |
| **方案 A** `up-badge-gold` | Gold 金色渐变 | 白色 | VIP / 奖项 |
| **方案 A** `up-badge-warm` | Golden Glow 浅金渐变 | 碳黑 | 暖色标签 |
| **方案 B** `up-badge-blush` | Blush 粉橙渐变 | 白色 | 强调 / 标记 |
| **方案 B** `up-badge-peach` | Peach 浅粉橙渐变 | 碳黑 | 暖色标签 |
| **方案 A** 🆕 `up-badge-ocean-gold` | 海洋蓝底 + 金色渐变描边 | 金字渐变 | 高端强调 |
| **方案 B** 🆕 `up-badge-ocean-blush` | 海洋蓝底 + 粉橙渐变描边 | 粉橙字渐变 | 温暖强调 |
| **方案 A** 🆕 `up-badge-deep-gold` | 深海蓝渐变底 + 半透明金描边 | 浅金字渐变 | 顶级荣誉 |
| **方案 B** 🆕 `up-badge-deep-blush` | 深海蓝渐变底 + 半透明粉橙描边 | 浅粉橙字渐变 | 温暖荣誉 |

## 5. Layout Principles

### 间距系统

```
4px | 8px | 12px | 16px | 24px | 32px | 48px | 64px | 80px | 96px
```

### 典型配色方案 (二选一)

> **🆕 二选一铁律**：下方 6 种场景中,**SECONDARY 列**的金色与粉橙互斥,一套设计只能选一种辅助色,不可混用。
> **🆕 渐变铁律**：所有标"金色"或"粉橙"的位置,**100% 使用渐变**（背景、按钮、描边、文字均不例外）。纯色出现 = 廉价感。

| 场景 | 主色 (PRIMARY) | 辅助 A (SECONDARY·金色) | 辅助 B (SECONDARY·粉橙) | 文字/底色 |
|------|---------------|------------------------|------------------------|----------|
| **1. 商务场景** | 深海蓝 `#0A2540` | Gold 渐变 `#F0CC44`→`#EABA1D`→`#B8950F` | Blush 渐变 `#E89AA4`→`#CE6E7B`→`#A85566` | 白字 + 辅助色字渐变 + 辅助色底白字按钮 |
| **2. 数字产品** | 雾白 `#F5F7FA` | Golden Glow 渐变 `#FFE9B0`→`#F2D677`→`#D9BC4D` | Peach 渐变 `#FFE0D7`→`#FFC7B9`→`#E89F8E` | 海洋蓝 `#1E4976` 字 + 辅助色底海洋蓝字 |
| **3. 营销物料** | 天空蓝 `#2E6BA8` | Gold 渐变 | Blush 渐变 | 白字 + 辅助色字渐变 |
| **4. 年轻场景** | Sky Blue 天空蓝 | Golden Glow 渐变 | Peach 渐变 | 现代亲和 + 辅助色字渐变 |
| **5. 专业场景** | Ocean Blue 海洋蓝 | Silver 银灰 | Silver 银灰 | 严谨专业（**此场景不强调辅助色**） |
| **6. 🆕 标志性奢华（海洋蓝+辅助色）** | 海洋蓝 `#1E4976` 或 深海蓝渐变 `#0A2540`→`#1E4976` | 金字渐变（`background-clip: text`）+ 金边 | 粉橙字渐变（`background-clip: text`）+ 粉橙边 | 🆕 辅助色字渐变 + 白色 + 辅助色描边 |

### 幻灯片 / 培训材料设计规则 (三明治结构)

> **🆕 二选一铁律**：下方表格中"金色版"与"粉橙版"互斥,一套幻灯片只能选一种。
> **🆕 渐变铁律**：所有标"金色"或"粉橙"的位置,100% 渐变;标题用了辅助色作为文字色,必须用 `background-clip: text` 渐变技术,绝不能 `color: #EABA1D` 或 `color: #CE6E7B` 写死。

| 幻灯片类型 | 背景 (PRIMARY) | 标题色 | 正文色 (NEUTRALS) | 可用点缀 (SECONDARY·二选一) |
|-----------|----------------|--------|-------------------|----------------------------|
| 封面页 | 深海蓝 `#0A2540` | 🆕 辅助色字渐变 (A: 金 / B: 粉橙) | 冰川蓝 `#E8F2FC` | 辅助色渐变 (品牌标识) + 海洋蓝 (辅助文字) |
| 章节分隔页 | 深海蓝 `#0A2540` | 🆕 辅助色字渐变 | 冰川蓝 `#E8F2FC` | 辅助色渐变 (竖线装饰) + 辅助色 (Logo) |
| 内容页 | 雾白 `#F5F7FA` 或 冰川蓝 `#E8F2FC` | 海洋蓝 `#1E4976` | 钢铁灰 `#6B7785` | 辅助色渐变 (强调) + 天空蓝 (图表) |
| 🆕 引用/金句页（深蓝版） | 海洋蓝 `#1E4976` 或 深海蓝渐变 | 🆕 辅助色字渐变 | 冰川蓝 `#E8F2FC` | 辅助色渐变 (左边框装饰) |
| 引用/金句页（暖版） | A: Golden Glow 渐变 `#FFE9B0`→`#F2D677`→`#D9BC4D` / B: Peach 渐变 `#FFE0D7`→`#FFC7B9`→`#E89F8E` | 碳黑 `#1A1A1A` | 石板灰 `#3D4852` | 辅助色渐变 (左边框装饰) |
| 数据/成果页 | 雾白 `#F5F7FA` | 碳黑 `#1A1A1A` | 石板灰 `#3D4852` | 🆕 辅助色字渐变 (关键大数字) |
| 结尾/CTA 页 | 深海蓝 `#0A2540` | 🆕 辅助色字渐变 | 冰川蓝 `#E8F2FC` | 辅助色渐变按钮 + 辅助色渐变 (品牌收尾) |

## 6. Depth & Elevation

| 层级 | 处理方式 | 用途 |
|------|---------|------|
| Base | 无阴影，纯色背景 | 标准内容区块 |
| Card Elevation | `0 2px 8px rgba(10, 37, 64, 0.08)` | 浅色背景上的标准卡片 |
| Header Elevation | 渐变背景 `#0A2540` → `#1E4976` → `#2E6BA8` | 英雄头部、章节横幅 |
| 🆕 Ocean + 辅助色 Card | 海洋蓝底 `#1E4976` + 🆕 辅助色字渐变 + `0 4px 16px rgba(10,37,64,0.3)` | 高端引用、VIP 标识、关键数据高亮 |
| 🆕 Deep + 辅助色 Badge | 深海蓝渐变底 `#0A2540`→`#1E4976` + 🆕 浅辅助色字渐变 + 1px 半透明辅助色描边 | 顶级荣誉、品牌周年、限量版标签 |

> ❌ **已移除**：`Premium Header`（深海蓝 → 海洋蓝 → 金色 三段渐变）已从设计系统中删除。如需高级封面，请使用 `Header Elevation` + 辅助色描边/徽章组合。

**阴影理念**：UPerform 使用细腻、专业的阴影。主卡片阴影 (`0 2px 8px rgba(10, 37, 64, 0.08)`) 柔和且扩散，创造温和的抬升感而不戏剧化。深色背景上的辅助色文字卡片使用更深的阴影 (`0 4px 16px rgba(10, 37, 64, 0.3)`) 让卡片从深色背景中"浮起"。头部区域使用渐变背景而非阴影来创造深度感。辅助色元素叠加柔光层（`rgba(255, 248, 220, 0.2)` 金色 / `rgba(255, 220, 210, 0.2)` 粉橙）营造光泽。**辅助色永远是渐变,不是阴影或纯色**——这是高级感的灵魂。

## 7. Do's and Don'ts

### Do

**3 层体系使用规范**
- **PRIMARY 主色** 使用 `#1E4976`（海洋蓝），占 60-70% 视觉量
- **NEUTRALS 中性色** 只做功能支撑（文字/边/底），不参与品牌识别
- **SECONDARY 辅助色** 二选一（A 金色系 或 B 粉橙系），**一套设计只能选一种，不可同屏混用**

**辅助色使用规范 DO'S（金色系·方案 A）**
- ✅ **金色必须用渐变**——Gold `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)` 或 Golden Glow `linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%)`
- ✅ 高端元素、VIP 标识
- ✅ 奖项证书、荣誉展示
- ✅ 重要 CTA 按钮强调（**渐变背景**）
- ✅ 品牌周年庆典素材
- ✅ 限量版产品标识
- ✅ 关键数字、Logo 旁点缀、签名
- ✅ **强调与点缀** — 关键标签、活跃高亮、数据亮点
- ✅ 🆕 **海洋蓝背景 + 金字渐变**（标志性奢华组合，用于高端封面、Hero、奖项、VIP 标识）——金字用 `background-clip: text` 渐变技术
- ✅ 🆕 **金色渐变背景 + 海洋蓝文字**（金色作为背景时，文字用海洋蓝 `#1E4976`）

**辅助色使用规范 DO'S（粉橙系·方案 B）**
- ✅ **粉橙必须用渐变**——Blush `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)` 或 Peach `linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%)`
- ✅ 温暖场景、女性向、年轻向
- ✅ 亲和 CTA、温和提示
- ✅ 品牌周年、限时活动
- ✅ 强调标签、数据亮点（替代原橙色的强调职责）
- ✅ 🆕 **海洋蓝背景 + 粉橙字渐变**（标志性格式组合）——粉橙字用 `background-clip: text` 渐变技术
- ✅ 🆕 **粉橙渐变背景 + 海洋蓝文字**（粉橙作为背景时，文字用海洋蓝 `#1E4976` + `font-weight ≥ 600`）——**不是白字**，白字 CR 仅 2.2–3.4 失败 AA

**排版与组件规范**
- 深色背景上的文字使用白色或 `#A8B2BD`（两者在深底上 CR 7.24+ 均达 AA）
- 浅色信息块使用 `#E8F2FC`（冰川蓝）或 `#F5F7FA`（雾白）
- **辅助色渐变背景上的文字统一用 Ocean `#1E4976` + `font-weight ≥ 600`**（不要白字，详见 §2 WCAG 节）
- 按钮圆角使用 `6px`
- 间距使用官方间距系统（4/8/12/16/24/32/48/64/80/96px）
- 封面/Banner 使用深海蓝渐变 + **辅助色渐变强调**
- 高级场景使用蓝+辅助色渐变组合

### Don't

**辅助色使用规范 DON'TS（铁律 #4 严格执行）**
- ❌ **使用纯色辅助色**（`background: #EABA1D` / `background: #F2D677` / `background: #CE6E7B` / `background: #FFC7B9` / `color: #EABA1D` / `color: #CE6E7B`）——任何位置、任何尺寸、任何用途一律禁止
- ❌ **两套辅助色混用**（同一设计/项目/页面中,金色和粉橙不能同时出现）——二选一
- ❌ 大面积背景色（即使是渐变,辅助色作为主背景超过 30% 视觉量也会显廉价）
- ❌ 正文字颜色（辅助色文字只用于标题、关键数字、Hero 字,不用于正文段落）
- ❌ 低对比度组合
- ❌ 过度使用（全场不超过 3 处辅助色元素）
- ❌ **把辅助色文字当纯色用**（如 `color: #EABA1D`）——必须 `background-clip: text` 渐变,否则字会"贴不住"深色背景
- ❌ **白字压在浅金/浅粉橙渐变背景上**（CR 1.6–3.4 失败 AA）——必须用海洋蓝深字

**3 层体系反模式**
- ❌ 不使用品牌色系以外的颜色（如大红色、紫色）
- ❌ 不在深色背景上使用纯黑 `#000000`
- ❌ 不在冰川蓝上使用辅助色（会糊）
- ❌ 不让蓝/辅助色参与正文（正文只走灰色）
- ❌ 不把灰色升格为 "secondary" 抢蓝色品牌位
- ❌ 不在普通内容页强行使用辅助色渐变
- ❌ 不在浅色背景上使用辅助色文字（对比度不足,看不见）
- ❌ **不同时使用金色和粉橙**（一套设计二选一）

### 四条使用铁律 (CRITICAL RULES)

1. **🆕 辅助色二选一,不可混用**
   一套设计中只允许使用 **方案 A（金色系）或 方案 B（粉橙系）** 中的 **一种**。
   整套设计（一个项目/一个演示/一个品牌触点）只能选其中一套作为 SECONDARY，不能两套同时出现。
   这是本套设计系统的核心约束。

2. **辅助色永远搭配深色或纯白**
   - 方案 A：金色 + 深海蓝 = 经典奢华；金色 + 雾白 = 轻柔优雅
   - 方案 B：粉橙 + 深海蓝 = 现代深色背景；粉橙 + 白色 = 温暖明亮
   - **辅助色不要放在冰川蓝上（会糊）**
   - 辅助色使用上限 ≤ 3 处

3. **文字层级用灰色系统，蓝/辅助色不参与正文**
   正文只走 `#1A1A1A` → `#3D4852` → `#6B7785` 的灰阶。
   蓝/辅助色都是装饰色，不是文字色——避免大段彩色文字，既疲劳又掉档次。
   **同时遵守 WCAG AA 对比度阈值（正文 4.5:1，大字 3:1，UI 组件 3:1）**。
   - Silver `#A8B2BD` 只做边框，不做正文（白底 CR 2.15 失败）
   - Steel `#6B7785` 仅在白底做正文（Mist/Glacier/深底上失败）
   - Horizon `#4A8FD8` 永远不当正文色
   - 完整规则见 [§2 WCAG AA 合规速查](#wcag-aa-合规速查-正文-451--大字-31--ui-组件-31)

4. **🆕 辅助色一律使用渐变,禁止纯色**（新铁律）
   无论是金属色（Gold/Golden Glow）还是温润色（Blush/Peach），纯色使用 = 廉价感 = 油漆/荧光笔。
   **所有辅助色元素（背景、底色、按钮、描边、文字）100% 渐变**。
   - 渐变背景：`linear-gradient(135deg, ...)` 多色渐变
   - 渐变文字：`background-clip: text` + `-webkit-text-fill-color: transparent`
   - 渐变描边：`background-image` 双层 + `background-origin: border-box`
   - 大面积背景（卡片底色、Banner、Header、章节页）尤其禁止使用纯辅助色——这是高级感的灵魂。

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

### 3 层色彩体系速查

```
PRIMARY        NEUTRALS                    SECONDARY (渐变,二选一)
海洋蓝         碳黑/石板/钢铁/银/雾白     方案A: 金/浅金渐变  /  方案B: 粉橙/浅粉橙渐变
```

- **PRIMARY**（品牌识别 60-70%）：深海蓝 `#0A2540` / 海洋蓝 `#1E4976` / 天空蓝 `#2E6BA8` / 地平蓝 `#4A8FD8` / 冰川蓝 `#E8F2FC`
- **NEUTRALS**（功能支撑）：碳黑 `#1A1A1A` / 石板灰 `#3D4852` / 钢铁灰 `#6B7785` / 银灰 `#A8B2BD` / 雾白 `#F5F7FA`
- **SECONDARY**（高级感 + 强调点缀，≤ 3 处，**二选一**）：
  - **方案 A 金色系**：Gold `#EABA1D` + Golden Glow `#F2D677` 金属光泽渐变
  - **方案 B 粉橙系**：Blush `#CE6E7B` + Peach `#FFC7B9` 温润柔和渐变

### 快速颜色参考
- 品牌主色：`#1E4976`（海洋蓝）
- 文字正文：`#1A1A1A` → `#3D4852` → `#6B7785`（灰阶）
- 边框分割：`#A8B2BD`（银灰）
- 浅色背景：`#F5F7FA`（雾白）/ `#E8F2FC`（冰川蓝）
- 🆕 **高级强调 / 强调点缀（方案 A）**：**金色渐变**（不是 `#EABA1D`）— 背景用 `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)`;金字用 `background-clip: text` 渐变技术
- 🆕 **高级强调 / 强调点缀（方案 B）**：**粉橙渐变**（不是 `#CE6E7B`）— 背景用 `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)`;粉橙字用 `background-clip: text` 渐变技术

### 示例组件提示

**通用部分：**
- "设计内容卡片：白色背景，1px `#A8B2BD` 边框，8px 圆角，24px padding。标题 28px `#1E4976`。正文 16px `#1A1A1A`，行高 1.6。"
- "构建冰川蓝信息框：`#E8F2FC` 背景，4px 左侧边框 `#4A8FD8`，16px 20px padding，0 8px 8px 0 圆角。"

**方案 A — 金色系组件：**
- "**创建金色 Premium 按钮**（方案 A）：金属渐变 `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)` 背景（**绝不用纯色 `background: #EABA1D`**），1px `#9A7B1A` 描边，白色文字，6px 圆角，叠加 inset 高光 `rgba(255,255,255,0.3)`。"
- "**创建金色渐变背景按钮 + 海洋蓝文字**：背景 `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)`，文字 `#1E4976` 海洋蓝，6px 圆角，10px 24px padding。"
- "**构建浅金暖色框**：`linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%)` 背景，4px 左侧边框用渐变 `linear-gradient(180deg, #F0CC44 0%, #B8950F 100%)`，叠加柔光 `inset 0 0 0 1px rgba(255,248,220,0.4)`。"
- "**构建海洋蓝+金字渐变卡片**（标志性奢华组合）：海洋蓝 `#1E4976` 纯色背景（或深海蓝渐变 `#0A2540`→`#1E4976`），4px 左侧边框用金色渐变 `linear-gradient(180deg, #F0CC44 0%, #B8950F 100%)`，标题用**金字渐变**：`background: linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%); -webkit-background-clip: text; background-clip: text; color: transparent;`，正文用冰川蓝 `#E8F2FC`，阴影 `0 4px 16px rgba(10,37,64,0.3)`，0 8px 8px 0 圆角。"
- "**创建英雄头部**：渐变背景从 `#0A2540` 到 `#1E4976` 再到 `#2E6BA8`。标题 48px 思源黑体字重 700，**白色或金字渐变（`background-clip: text` 技术,不要用 `color: #EABA1D`）**。副标题 18px，颜色 `#A8B2BD`。下方添加 4px 强调条，使用**金色渐变 `linear-gradient(90deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)`**。"

**方案 B — 粉橙系组件：**
- "**创建粉橙 Premium 按钮**（方案 B）：渐变 `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)` 背景（**绝不用纯色 `background: #CE6E7B`**），1px `#8B4754` 描边，白色文字，6px 圆角，叠加 inset 高光 `rgba(255,220,210,0.3)`。"
- "**创建粉橙渐变背景按钮 + 白色文字**：背景 `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)`，文字 `#FFFFFF` 纯白，6px 圆角，10px 24px padding。"
- "**构建浅粉橙暖色框**：`linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%)` 背景，4px 左侧边框用渐变 `linear-gradient(180deg, #E89AA4 0%, #A85566 100%)`，叠加柔光 `inset 0 0 0 1px rgba(255,220,210,0.4)`。"
- "**构建海洋蓝+粉橙字渐变卡片**（标志性格式组合）：海洋蓝 `#1E4976` 纯色背景（或深海蓝渐变），4px 左侧边框用粉橙渐变，标题用**粉橙字渐变**：`background: linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%); -webkit-background-clip: text; background-clip: text; color: transparent;`，正文用冰川蓝 `#E8F2FC`，阴影 `0 4px 16px rgba(10,37,64,0.3)`。"

### 迭代指南 (3 层结构)

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

**SECONDARY 辅助色系（**二选一，≤ 3 处**）**

方案 A — 金色系（金属光泽，高级奢华）：
11. 🆕 **金色场景使用金色渐变**（不是纯色）—— Gold `linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%)` + Golden Glow `linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%)`
12. **全场不超过 3 处金色元素**（VIP 标识、奖项、关键强调、强调与点缀）
13. 🆕 **金字必须用渐变**：使用 `background-clip: text` 技术,`background: linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%)` + `-webkit-background-clip: text; color: transparent`,绝不写 `color: #EABA1D`
14. 🆕 **金描边必须用渐变**：使用双层 `background-image` + `background-origin: border-box` + `background-clip: padding-box, border-box`,绝不写 `border: 1px solid #EABA1D`

方案 B — 粉橙系（温润柔和，温暖亲和）：
15. 🆕 **粉橙场景使用粉橙渐变**（不是纯色）—— Blush `linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%)` + Peach `linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%)`
16. **全场不超过 3 处粉橙元素**
17. 🆕 **粉橙字必须用渐变**：使用 `background-clip: text` 技术,绝不写 `color: #CE6E7B`
18. 🆕 **粉橙描边必须用渐变**：使用双层 `background-image`,绝不写 `border: 1px solid #CE6E7B`

**四条铁律**
- 🆕 🔴 **辅助色二选一，不可混用** —— 一套设计只允许使用一种 SECONDARY（金色系 或 粉橙系），不能同屏出现
- 🟡 **辅助色永远搭配深色或纯白**(深海蓝/雾白/白色),不要放冰川蓝上;**辅助色已承担强调与点缀职责(≤ 3 处)**
- ⚪ **文字只走灰阶**(`#1A1A1A` → `#3D4852` → `#6B7785`),蓝/辅助色不参与正文
- 🆕 🟨 **辅助色一律渐变，禁止纯色** —— 任何位置、任何尺寸、任何用途的辅助色 100% 渐变;大面积背景尤其禁止使用纯辅助色

**排版与组件**
- 保持所有角圆润但不过于柔软 — 按钮 6px，卡片 8px
- 使用 4/8/12/16/24/32/48/64/80/96px 系统保持一致的间距
- 🆕 辅助色字渐变需保证对比度：深色背景用浅辅助色，浅色背景用深辅助色

### CSS 变量参考 (3 层结构)

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

  /* ========== SECONDARY 方案 A (辅助色) - 金色系 ========== */
  /* ⚠️ 二选一:本套 OR 下方粉橙系,不可同屏混用 */
  /* 这些 hex 颜色只用于"构造渐变的中间色",禁止直接当 background-color 纯色使用 */
  /* 高级感 + 强调点缀:全场 ≤ 3 处 */
  --up-gold:         #EABA1D;   /* Gold 金色 - 中间色 */
  --up-gold-hi:      #F0CC44;   /* 亮金高光 */
  --up-gold-lo:      #B8950F;   /* 深金阴影 */
  --up-gold-edge:    #9A7B1A;   /* 金色描边 */
  --up-glow:         #F2D677;   /* Golden Glow 浅金 - 中间色 */
  --up-glow-hi:      #FFE9B0;   /* 浅金高光 */
  --up-glow-lo:      #D9BC4D;   /* 浅金阴影 */

  /* ========== SECONDARY 方案 A (辅助色) - 金色系 (渐变变量) ========== */
  /* 这些是设计系统中"金色"的真正形态 —— 100% 渐变,绝无纯色 */
  --up-gold-gradient:        linear-gradient(135deg, #F0CC44 0%, #EABA1D 50%, #B8950F 100%);
  --up-gold-gradient-soft:   linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);
  --up-gold-gradient-border: linear-gradient(135deg, #F0CC44 0%, #B8950F 100%);

  --up-glow-gradient:        linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%);
  --up-glow-gradient-text:   linear-gradient(135deg, #FFE9B0 0%, #F2D677 50%, #D9BC4D 100%);
  --up-gold-text:            linear-gradient(135deg, #F0CC44 0%, #F2D677 50%, #EABA1D 100%);

  /* ========== SECONDARY 方案 B (辅助色) - 粉橙系 ========== */
  /* ⚠️ 二选一:本套 OR 上方金色系,不可同屏混用 */
  --up-blush:        #CE6E7B;   /* Blush 粉橙 - 中间色 */
  --up-blush-hi:     #E89AA4;   /* 粉橙高光 */
  --up-blush-lo:     #A85566;   /* 粉橙阴影 */
  --up-blush-edge:   #8B4754;   /* 粉橙描边 */
  --up-peach:        #FFC7B9;   /* Peach 浅粉橙 - 中间色 */
  --up-peach-hi:     #FFE0D7;   /* 浅粉橙高光 */
  --up-peach-lo:     #E89F8E;   /* 浅粉橙阴影 */

  /* ========== SECONDARY 方案 B (辅助色) - 粉橙系 (渐变变量) ========== */
  --up-blush-gradient:        linear-gradient(135deg, #E89AA4 0%, #CE6E7B 50%, #A85566 100%);
  --up-blush-gradient-soft:   linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);
  --up-blush-gradient-border: linear-gradient(135deg, #E89AA4 0%, #A85566 100%);

  --up-peach-gradient:        linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%);
  --up-peach-gradient-text:   linear-gradient(135deg, #FFE0D7 0%, #FFC7B9 50%, #E89F8E 100%);
  --up-blush-text:            linear-gradient(135deg, #E89AA4 0%, #FFC7B9 50%, #CE6E7B 100%);

}

---

## 相关资源

- 完整视觉规范：查看 `../uperform-visual-design/SKILL.md`
- 配色方案来源：`./优普丰品牌设计配色方案.md`
