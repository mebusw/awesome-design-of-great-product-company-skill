# Design System Inspiration of UPerform

## 1. Visual Theme & Atmosphere

UPerform（优普丰）是一家专业Scrum/敏捷咨询公司，品牌视觉采用**深海蓝为主色、珊瑚橙为Accent**的专业双色调体系，传达信任、专业与温暖的品牌调性。

设计理念是"专业而温暖"——深海蓝建立权威与信任感，珊瑚橙点缀增添活力与亲和力。这种组合让 UPerform 的教材既值得信赖（适合企业培训），又不冰冷 corporate（富有邀请感）。

**关键特征：**
- 品牌主色为深海蓝 (`#083A67`) — 专业、值得信赖
- 珊瑚橙作为强调色 (`#FF9B7D`) — 活力、温暖
- 钢蓝作为次级色 (`#4F82BA`) — 辅助视觉层级
- 暖米色背景 (`#FFF0D1`) 用于高亮和提示 — 亲切感
- 简洁的卡片布局配合细腻阴影
- 按钮圆角 6px — 柔和但不失专业
- 专业字体：思源黑体（中文）+ Source Sans Pro（英文）

## 2. Color Palette & Roles

### 品牌主色：深海蓝系

| 名称 | HEX | 用途 |
|------|-----|------|
| Navy Deepest | `#041C32` | 最深背景、深色封面、页脚 |
| Navy Dark | `#062B4D` | 深色 Header、深色卡片背景 |
| Navy Mid | `#083A67` | **品牌主色**，主要深色区块、大标题 |
| Navy Base | `#0A477E` | 按钮、链接、强调边框 |

### 品牌次色：钢蓝系

| 名称 | HEX | 用途 |
|------|-----|------|
| Steel Dark | `#2E4C6D` | 次级标题背景、图表深色 |
| Steel Mid | `#395E87` | 图表、图标、悬停态 |
| Steel Base | `#4471A2` | 次级强调、标签背景 |
| Steel Light | `#4F82BA` | **品牌次色**，次级按钮、进度条、分隔线 |

### 强调色：天蓝系

| 名称 | HEX | 用途 |
|------|-----|------|
| Sky Dark | `#386EB0` | 高亮标注、引用块左边框 |
| Sky Mid | `#417ECA` | 链接、信息图标 |
| Sky Base | `#498FE4` | 活跃态、选中高亮 |
| Sky Bright | `#519FFD` | 最亮强调、badge、标签 |

### Accent 色：珊瑚橙系

| 名称 | HEX | 用途 |
|------|-----|------|
| Coral Dark | `#C67861` | 深色 Accent、图标强调 |
| Coral Mid | `#CB7B64` | 次级 Accent |
| Coral Base | `#E78C72` | **Accent 主色**，CTA 按钮、重要标注 |
| Coral Light | `#FF9B7D` | **品牌 Accent**，高亮标签、暖色卡片、图表辅助 |

### 温暖中性：米色系

| 名称 | HEX | 用途 |
|------|-----|------|
| Beige Dark | `#C8BCA4` | 分隔线、禁用态 |
| Beige Mid | `#D9CCB2` | 卡片背景辅助色 |
| Beige Light | `#F1E2C5` | 温暖区块背景 |
| Beige Pale | `#FFF0D1` | 浅色提示背景、引用块背景 |

### 冷中性：灰色系

| 名称 | HEX | 用途 |
|------|-----|------|
| Grey Dark | `#848484` | 辅助文字、图标 |
| Grey Mid | `#A5A5A5` | 占位符文字 |
| Grey Base | `#BBBBBB` | 边框、分割线 |
| Grey Light | `#D2D2D2` | 浅色边框 |
| Grey Pale | `#DDDDDD` | 背景分隔 |
| White | `#FFFFFF` | 纯白背景、卡片 |

### 近黑色

| 名称 | HEX | 用途 |
|------|-----|------|
| Near Black | `#283030` | 正文、深色文字 |
| Dark Grey | `#535353` | 次要正文 |
| Mid Grey | `#A7A7A7` | 辅助说明 |

### 品牌三色速查

| 角色 | HEX | 使用场景 |
|------|-----|----------|
| **Primary** | `#083A67` | 封面、Header、主标题背景 |
| **Secondary** | `#4F82BA` | 次级按钮、进度、图表主色 |
| **Accent** | `#FF9B7D` | CTA 按钮、重要标注、活跃状态 |

## 3. Typography Rules

### 字体家族

**中文：** 思源黑体（Noto Sans SC）/ 微软雅黑 / 苹方
**英文：** Source Sans Pro / Open Sans / Segoe UI

```html
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700&family=Source+Sans+Pro:wght@300;400;600;700&display=swap" rel="stylesheet">
```

### 标题层级

| 级别 | 字号 | 字重 | 颜色 | 用途 |
|------|------|------|------|------|
| Display H1 | 48–60px | 700 | `#083A67` 或 `#FFFFFF` | 封面大标题 |
| Page H2 | 32–36px | 700 | `#083A67` | 页面主标题 |
| Section H3 | 24–28px | 600 | `#0A477E` | 区块标题 |
| Sub H4 | 20–22px | 600 | `#2E4C6D` | 子标题 |
| Label H5 | 16–18px | 500 | `#395E87` | 标签、小标题 |
| Caption | 13–14px | 400 | `#535353` | 注释、说明 |

### 正文层级

| 级别 | 字号 | 行高 | 颜色 |
|------|------|------|------|
| Body Large | 18–20px | 1.7 | `#283030` |
| Body Base | 15–16px | 1.6 | `#283030` |
| Body Small | 13–14px | 1.5 | `#535353` |
| Muted | 12–13px | 1.4 | `#A7A7A7` |

### 设计原则
- **通过字重建立清晰层级**：H1/H2 使用 700（粗体），H3/H4 使用 600（次粗体），正文使用 400（常规）
- **一致的间距系统**：4/8/12/16/24/32/48/64/80/96px 间距系统
- **专业中文支持**：思源黑体提供优秀的中文字符渲染
- **按钮圆角 6px**：柔和但不失专业

## 4. Component Stylings

### 按钮

**Primary 按钮**
- Background: `#083A67`
- Text: `#FFFFFF`
- Border: 2px solid `#083A67`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#0A477E`, border `#0A477E`

**Accent / CTA 按钮**
- Background: `#FF9B7D`
- Text: `#FFFFFF`
- Border: 2px solid `#FF9B7D`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#E78C72`, border `#E78C72`

**Secondary 按钮（描边）**
- Background: transparent
- Text: `#4F82BA`
- Border: 2px solid `#4F82BA`
- Padding: 10px 24px
- Radius: 6px
- Hover: Background `#4F82BA`, text `#FFFFFF`

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
- Border: 1px solid `#D2D2D2`
- Radius: 8px
- Padding: 24px
- Shadow: `0 2px 8px rgba(4, 28, 50, 0.08)`

**深色卡片（深海蓝背景）**
- Background: `#083A67`
- Color: `#FFFFFF`
- Radius: 8px
- Padding: 24px

**暖色卡片（用于亮点、提示）**
- Background: `#FFF0D1`
- Border-left: 4px solid `#FF9B7D`
- Radius: 0 8px 8px 0
- Padding: 16px 20px

**信息卡片（用于说明）**
- Background: `#EBF4FF`
- Border-left: 4px solid `#4F82BA`
- Radius: 0 8px 8px 0
- Padding: 16px 20px

### Header / Banner

**深色 Header**
- Background: linear-gradient(135deg, `#041C32` 0%, `#083A67` 60%, `#0A477E` 100%)
- Color: `#FFFFFF`
- Padding: 48px 64px

**章节 Banner**
- Background: `#083A67`
- Color: `#FFFFFF`
- Padding: 32px 48px
- Border-left: 6px solid `#FF9B7D`

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
.up-badge-primary  { background: #083A67; color: #FFFFFF; }
.up-badge-accent   { background: #FF9B7D; color: #FFFFFF; }
.up-badge-sky      { background: #519FFD; color: #FFFFFF; }
.up-badge-warm     { background: #FFF0D1; color: #C67861; border: 1px solid #FF9B7D; }
```

### 分隔线

```css
.up-divider         { border: none; border-top: 1px solid #D2D2D2; margin: 24px 0; }
.up-divider-accent  { border: none; border-top: 3px solid #FF9B7D; margin: 24px 0; }
.up-divider-primary { border: none; border-top: 3px solid #083A67; margin: 24px 0; }
```

## 5. Layout Principles

### 间距系统

```
4px | 8px | 12px | 16px | 24px | 32px | 48px | 64px | 80px | 96px
```

### 典型配色方案

**方案 A：深蓝专业（推荐用于商务报告、课程封面）**
- 背景：`#083A67`
- 主文字：`#FFFFFF`
- 强调：`#FF9B7D`（珊瑚橙）
- 次级文字：`#D9CCB2`

**方案 B：白底专业（推荐用于内容页、讲义）**
- 背景：`#FFFFFF`
- 主标题：`#083A67`
- 正文：`#283030`
- 强调色块：`#FF9B7D` 或 `#4F82BA`
- 边框/分割：`#D2D2D2`

**方案 C：暖米渐变（推荐用于封面、引导页）**
- 背景渐变：`#FFF0D1` → `#FFFFFF`
- 标题：`#083A67`
- Accent 线条：`#FF9B7D`
- 正文：`#283030`

**方案 D：天蓝亮色（推荐用于数据可视化、图表）**
- 主色：`#083A67` / `#0A477E`
- 数据色1：`#4F82BA`
- 数据色2：`#519FFD`
- 数据色3：`#FF9B7D`
- 数据色4：`#E78C72`
- 中性背景：`#F5F8FA`

### 幻灯片 / 培训材料设计规则

| 幻灯片类型 | 背景 | 标题 | 正文 | 强调 |
|-----------|------|------|------|------|
| 封面页 | `#083A67` 深蓝 | `#FFFFFF` | `#D9CCB2` | `#FF9B7D` |
| 章节分隔页 | `#041C32` | `#FFFFFF` | 无 | `#FF9B7D` 竖线装饰 |
| 内容页 | `#FFFFFF` | `#083A67` | `#283030` | `#FF9B7D` 下划线 |
| 引用/金句页 | `#FFF0D1` | `#083A67` | `#535353` | `#FF9B7D` 左边框 |
| 数据/图表页 | `#FFFFFF` | `#083A67` | `#283030` | 蓝橙双色系 |
| 结尾/CTA 页 | `#083A67` | `#FFFFFF` | `#D9CCB2` | `#FF9B7D` 按钮 |

## 6. Depth & Elevation

| 层级 | 处理方式 | 用途 |
|------|---------|------|
| Base | 无阴影，纯色背景 | 标准内容区块 |
| Card Elevation | `0 2px 8px rgba(4, 28, 50, 0.08)` | 浅色背景上的标准卡片 |
| Header Elevation | 渐变背景 `#041C32` → `#083A67` → `#0A477E` | 英雄头部、章节横幅 |

**阴影理念**：UPerform 使用细腻、专业的阴影。主卡片阴影 (`0 2px 8px rgba(4, 28, 50, 0.08)`) 柔和且扩散，创造温和的抬升感而不戏剧化。头部区域使用渐变背景而非阴影来创造深度感。

## 7. Do's and Don'ts

### Do
- 主色使用 `#083A67`（深海蓝），而非其他蓝色
- Accent 色使用 `#FF9B7D`（珊瑚橙）
- 次色使用 `#4F82BA`（钢蓝）
- 深色背景上的文字使用白色或 `#D9CCB2`
- 按钮圆角使用 `6px`
- 间距使用官方间距系统（4/8/12/16/24/32/48/64/80/96px）
- 封面/Banner 使用深海蓝背景 + 珊瑚橙强调

### Don't
- 不使用品牌色系以外的颜色（如大红色、紫色）
- 不在深色背景上使用纯黑 `#000000`
- 不使用超过 3 种主色调

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

### 快速颜色参考
- 主色：`#083A67`（深海蓝）
- 次色：`#4F82BA`（钢蓝）
- 强调色：`#FF9B7D`（珊瑚橙）
- 浅色背景：`#FFFFFF`
- 暖色背景：`#FFF0D1`
- 正文颜色：`#283030`
- 辅助文字：`#535353`

### 示例组件提示
- "创建英雄头部，渐变背景从 #041C32 到 #083A67。标题 48px 思源黑体字重 700，白色文字。副标题 18px，颜色 #D9CCB2。下方添加 4px 强调条，使用从 #FF9B7D 到 #E78C72 的渐变。"
- "设计内容卡片：白色背景，1px #D2D2D2 边框，8px 圆角，24px padding。标题 28px #083A67。正文 16px #283030，行高 1.6。"
- "创建 Accent CTA 按钮：#FF9B7D 背景，白色文字，6px 圆角，10px 24px padding。15px Source Sans Pro 字重 600。"
- "构建暖色高亮框：#FFF0D1 背景，4px 左侧边框 #FF9B7D，16px 20px padding，0 8px 8px 0 圆角。"
- "设计章节横幅：#083A67 背景，白色文字，32px 48px padding，6px 左侧边框 #FF9B7D。"

### 迭代指南
1. 以深海蓝 `#083A67` 作为主色调 — 它奠定专业基调
2. 为 CTA 和重要高亮添加珊瑚橙 `#FF9B7D` — 创造温暖和活力
3. 使用钢蓝 `#4F82BA` 作为次级元素 — 支持视觉层级
4. 为提示框使用暖米色 `#FFF0D1` — 引人注目而不喧闹
5. 保持所有角圆润但不过于柔软 — 按钮 6px，卡片 8px
6. 使用 4/8/12/16/24/32/48/64/80/96px 系统保持一致的间距

### 快速入门模板

```html
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@300;400;500;700&family=Source+Sans+Pro:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --up-navy:        #083A67;
      --up-navy-base:   #0A477E;
      --up-steel-light: #4F82BA;
      --up-coral-light: #FF9B7D;
      --up-beige-pale:  #FFF0D1;
      --up-near-black:  #283030;
      --up-grey-light:  #D2D2D2;
      --up-white:       #FFFFFF;
    }

    body {
      font-family: 'Noto Sans SC', 'Source Sans Pro', 'Microsoft YaHei', sans-serif;
      color: var(--up-near-black);
      background: var(--up-white);
      font-size: 16px;
      line-height: 1.6;
    }

    .up-header {
      background: linear-gradient(135deg, #041C32 0%, #083A67 100%);
      color: white;
      padding: 48px 64px;
    }

    .up-header h1 { font-size: 42px; font-weight: 700; margin-bottom: 12px; }
    .up-header p  { color: #D9CCB2; font-size: 18px; }

    .up-accent-bar {
      height: 4px;
      background: linear-gradient(90deg, #FF9B7D, #E78C72);
    }

    .up-content { padding: 48px 64px; }
    .up-content h2 { color: var(--up-navy); font-size: 28px; margin-bottom: 24px; }

    .up-btn-accent {
      background: var(--up-coral-light);
      color: white;
      border: none;
      padding: 12px 28px;
      border-radius: 6px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header class="up-header">
    <h1>UPerform 培训材料标题</h1>
    <p>副标题 · 说明文字</p>
  </header>
  <div class="up-accent-bar"></div>
  <main class="up-content">
    <h2>内容区标题</h2>
    <p>正文内容区域...</p>
    <br>
    <button class="up-btn-accent">开始学习 →</button>
  </main>
</body>
</html>
```

### CSS 变量参考

```css
:root {
  --up-navy-deepest: #041C32;
  --up-navy-dark:    #062B4D;
  --up-navy:         #083A67;   /* Brand Primary */
  --up-navy-base:    #0A477E;
  --up-steel-dark:   #2E4C6D;
  --up-steel-mid:    #395E87;
  --up-steel:        #4471A2;
  --up-steel-light:  #4F82BA;   /* Brand Secondary */
  --up-sky-dark:     #386EB0;
  --up-sky-mid:      #417ECA;
  --up-sky:          #498FE4;
  --up-sky-bright:   #519FFD;
  --up-coral-dark:   #C67861;
  --up-coral-mid:    #CB7B64;
  --up-coral:        #E78C72;
  --up-coral-light:  #FF9B7D;   /* Brand Accent */
  --up-beige-dark:   #C8BCA4;
  --up-beige-mid:    #D9CCB2;
  --up-beige-light:  #F1E2C5;
  --up-beige-pale:   #FFF0D1;
  --up-grey-dark:    #848484;
  --up-grey-mid:     #A5A5A5;
  --up-grey:         #BBBBBB;
  --up-grey-light:   #D2D2D2;
  --up-grey-pale:    #DDDDDD;
  --up-white:        #FFFFFF;
  --up-near-black:   #283030;
  --up-dark-grey:    #535353;
  --up-text-muted:   #A7A7A7;
}
```

---

## 相关资源

- 完整视觉规范：查看 `../uperform-visual-design/SKILL.md`