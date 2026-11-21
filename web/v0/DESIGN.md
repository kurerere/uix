---
name: "v0 by Vercel"
description: "瑞士工程级极简 Web 设计体系（Vercel Geist + v0），以高对比纯黑白、紧凑负字距 Geist Sans 排版、1px 阴影描边与精致胶囊芯片构成现代 AI 构建与产品展示界面。"
colors:
  ink-primary-light: "#171717"
  ink-primary-dark: "#EDEDED"
  focus-blue-light: "#0072F5"
  focus-blue-hover: "#0062D1"
  focus-blue-ink-light: "#0068D6"
  focus-blue-dark: "#52A8FF"
  blue-soft-light: "#F0F7FF"
  blue-soft-dark: "#0F1C2E"
  status-green: "#45A557"
  status-green-ink-light: "#297A3A"
  status-green-ink-dark: "#62C073"
  status-green-soft-light: "#EFFBEF"
  status-green-soft-dark: "#0B2212"
  status-red: "#E5484D"
  status-red-ink-light: "#CB2A2F"
  status-red-ink-dark: "#FF6166"
  status-red-soft-light: "#FFF0F0"
  status-red-soft-dark: "#2A1314"
  status-amber: "#FFB224"
  status-amber-ink-light: "#A35200"
  status-amber-ink-dark: "#F2A20D"
  status-amber-soft-light: "#FFF6E6"
  status-amber-soft-dark: "#291800"
  accent-teal: "#12A594"
  accent-teal-ink-light: "#067A6E"
  accent-teal-ink-dark: "#0AC7B4"
  accent-purple: "#8E4EC6"
  accent-purple-ink-light: "#7820BC"
  accent-purple-ink-dark: "#BF7AF0"
  accent-pink: "#EA3E83"
  accent-pink-ink-light: "#BD2864"
  accent-pink-ink-dark: "#F75F8F"
  canvas-light: "#FAFAFA"
  surface-light: "#FFFFFF"
  gray-100-light: "#F2F2F2"
  gray-200-light: "#EBEBEB"
  gray-300-light: "#E6E6E6"
  gray-500-light: "#C9C9C9"
  gray-700-light: "#8F8F8F"
  text-secondary-light: "#4D4D4D"
  border-subtle-light: "rgba(0, 0, 0, 0.05)"
  border-default-light: "rgba(0, 0, 0, 0.08)"
  border-strong-light: "rgba(0, 0, 0, 0.10)"
  canvas-dark: "#000000"
  surface-dark: "#0A0A0A"
  gray-100-dark: "#1A1A1A"
  gray-200-dark: "#1F1F1F"
  gray-300-dark: "#292929"
  gray-400-dark: "#2E2E2E"
  gray-500-dark: "#454545"
  gray-700-dark: "#8F8F8F"
  text-secondary-dark: "#A1A1A1"
  border-subtle-dark: "rgba(255, 255, 255, 0.06)"
  border-default-dark: "rgba(255, 255, 255, 0.09)"
  border-strong-dark: "rgba(255, 255, 255, 0.145)"
typography:
  display:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "32px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "16px"
    fontWeight: 500
    lineHeight: 1.5
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: "0em"
  control:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1.43
    letterSpacing: "0em"
  label:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.38
    letterSpacing: "0em"
  caption:
    fontFamily: "Geist Sans, Inter, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.33
    letterSpacing: "0em"
  code:
    fontFamily: "Geist Mono, SFMono-Regular, Roboto Mono, Menlo, Consolas, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
rounded:
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  2xl: "24px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "24px"
  2xl: "32px"
  3xl: "48px"
  4xl: "64px"
components:
  button-primary:
    backgroundColor: "{colors.ink-primary-light}"
    textColor: "{colors.surface-light}"
    typography: "{typography.control}"
    rounded: "{rounded.sm}"
    padding: "0 12px"
    height: "32px"
  button-secondary:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.ink-primary-light}"
    typography: "{typography.control}"
    rounded: "{rounded.sm}"
    padding: "0 12px"
    height: "32px"
  button-ghost:
    textColor: "{colors.text-secondary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "6px 12px"
    height: "32px"
  button-submit-disabled:
    backgroundColor: "{colors.gray-100-light}"
    textColor: "{colors.gray-500-light}"
    rounded: "{rounded.sm}"
    width: "28px"
    height: "28px"
  promo-pill:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.ink-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.full}"
    padding: "0 8px 0 12px"
    height: "32px"
  suggestion-chip:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.text-secondary-light}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    padding: "4px 12px"
  composer-card:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.ink-primary-light}"
    rounded: "{rounded.lg}"
    padding: "12px"
    width: "690px"
  template-card:
    backgroundColor: "{colors.surface-light}"
    textColor: "{colors.ink-primary-light}"
    rounded: "{rounded.md}"
---

# Design System: v0 by Vercel

## Overview

**Creative North Star: "The Swiss Engineering Canvas"**

`v0.app` 承袭 Vercel Geist 设计体系的极简建筑感，是一套融合 **Operate（构建与提示输入）** 与 **Persuade / Showcase（模板展示与社区画廊）** 的现代 Web 应用设计语言。它用极度克制的无彩色黑白灰阶搭建出近乎画廊般干净的舞台：浅色模式下以微冷雪灰画布（`#FAFAFA`）承托纯白交互卡片与 `#171717` 实黑行动按钮；深色模式下沉入真正的纯黑（`#000000`）与极深曜石（`#0A0A0A`），让预览作品、代码与用户输入成为绝对视觉中心。

其标志性气质来自三个精妙克制的细节：**大标题上高达 `-0.04em` 的紧密负字距（Geist Sans）**、**用 `box-shadow` 1px 透明环替代生硬实线边框的 Geist 阴影描边体系**，以及**全圆角轻量白底胶囊芯片（Promo Pill / Suggestion Chips）与利落 `6px` 矩形按钮的对比搭配**。所有规范均以技术栈无关的标准参数描述，可在任意 Web 或跨端框架中完整还原。

**Key Characteristics:**
- **高对比纯粹黑白主轴**：零品牌彩色噪音，主操作按钮永远是高反差黑/白反转（浅 `#171717` / 深 `#EDEDED`），仅在聚焦、链接与状态反馈处克制引入 Geist 语义色。
- **紧凑负字距排版**：`Geist Sans` 标题施加 `-0.04em` 紧密字距（`32px` 对应 `-1.28px`，`24px` 对应 `-0.96px`），形成辨识度极高的瑞士网格秩序感。
- **阴影即边框（Shadow-Border Architecture）**：卡片、浮层菜单与按钮边缘统一用 `0 0 0 1px rgba(0,0,0,0.08)` 叠加极低透明度多层漫射阴影，呈现锐利而通透的立体感。
- **全圆角芯片 + 利落矩形动作键**：引导与筛选芯片采用完全胶囊圆角（`9999px`），正式操作按钮与表单则坚守紧致的 `6px` 圆角，一圆一方建立清晰功能区隔。

## Colors

色板严格遵循 Vercel Geist 的 **10 阶明度体系（100–1000）**：100–300 为背景与填充，400–600 为边框与线框，700–800 为柔和图标/占位，900 为次级文本，1000 为高对比主文本。

### Primary
- **Ink Primary** (浅色 `#171717` 配 `#FFFFFF` 文字；深色 `#EDEDED` 配 `#0A0A0A` 文字)：全站核心 CTA 按钮（`Sign Up`、发送、部署、确认）、标志图形与最高级标题。

### Secondary
- **Geist Focus Blue** (`#0072F5` 浅色焦点环与实心信息色，文本 `#0068D6`，浅底 `#F0F7FF`；深色焦点与链接 `#52A8FF`，实心 `#0072F5`，深底 `#0F1C2E`)：键盘双环焦点、主超链接、选中高亮与信息提示。

### Tertiary
- **Green（成功/运行）**：主色 `#45A557`（浅字 `#297A3A` / 浅底 `#EFFBEF`；深字 `#62C073` / 深底 `#0B2212`）。
- **Red（错误/危险）**：主色 `#E5484D`（浅字 `#CB2A2F` / 浅底 `#FFF0F0`；深字 `#FF6166` / 深底 `#2A1314`）。
- **Amber（警告/提示）**：主色 `#FFB224`（浅字 `#A35200` / 浅底 `#FFF6E6`；深字 `#F2A20D` / 深底 `#291800`）。
- **Teal / Purple / Pink（分类与代码点缀）**：Teal `#12A594`（浅字 `#067A6E` / 深字 `#0AC7B4`）、Purple `#8E4EC6`（浅字 `#7820BC` / 深字 `#BF7AF0`）、Pink `#EA3E83`（浅字 `#BD2864` / 深字 `#F75F8F`）。

### Neutral
- **Light Surface Ladder**：页面画布 `Background-200` `#FAFAFA` → 卡片/输入坞/次按钮 `Background-100` `#FFFFFF` → 禁用/轻底 `Gray-100` `#F2F2F2` → 分割与边框 `Gray-200/300` `#EBEBEB / #E6E6E6` → 输入框加强边 `Gray-500` `#C9C9C9` → 辅助文本 `Gray-900` `#4D4D4D` → 主文本 `Gray-1000` `#171717`。
- **Dark Surface Ladder**：页面画布 `Background-200` `#000000` → 主表面 `Background-100` `#0A0A0A` → 一级卡片/控件 `Gray-100/200` `#1A1A1A / #1F1F1F` → 边框 `Gray-300/400` `#292929 / #2E2E2E` → 加强边 `Gray-500` `#454545` → 辅助文本 `Gray-900` `#A1A1A1` → 主文本 `Gray-1000` `#EDEDED`。
- **Alpha Hairlines**：浅色透明边 `rgba(0,0,0,0.05 / 0.08 / 0.10)`；深色透明边 `rgba(255,255,255,0.06 / 0.09 / 0.13 / 0.145)`。

### Named Rules
**The Monochrome Authority Rule.** 页面骨架、导航栏与主行动按钮永远维持纯粹的黑白灰高对比；彩色只用于状态反馈、焦点环与用户生成的预览缩略图本身。

**The Canvas-vs-Card Lift Rule.** 页面底层在浅色用 `#FAFAFA`、深色用 `#000000`，让纯白 `#FFFFFF`（深色 `#0A0A0A` / `#1A1A1A`）的输入坞、按钮与芯片无需重阴影即可清晰浮现。

## Typography

**Display Font:** Geist Sans（回退 `Inter`, `-apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif`）。
**Body Font:** Geist Sans（同上，常规 UI 正文 `14px`）。
**Label/Mono Font:** Geist Mono（回退 `SFMono-Regular, Roboto Mono, Menlo, Consolas, monospace`）。

**Character:** 精准、冷静的现代瑞士无衬线气质；大号标题用强负字距收紧成稳固的建筑块面，正文与按钮则回归 `0em` 自然呼吸，确保长提示词与多列数据清晰易读。

### Hierarchy
- **Display / Hero H1** (`600`, `32px`, 行高 `40px`, 字距 `-1.28px` / `-0.04em`)：首屏居中核心提问标题（如 `What do you want to create?`）。
- **Headline / Section H2** (`600`, `24px`, 行高 `32px`, 字距 `-0.96px` / `-0.04em`)：画廊与区块标题（如 `Start with a template`）。
- **Title** (`500 / 600`, `16px`, 行高 `24px`, 字距 `-0.02em`)：对话框标题与卡片组标题。
- **Body / Nav** (`400`, `14px`, 行高 `20px`)：顶栏导航链接、提示词输入正文与段落文案。
- **Control / Button** (`500`, `14px`, 行高 `20px`)：所有标准按钮、次要 CTA 与过滤标签。
- **Label / Compact Control** (`500`, `13px`, 行高 `18px`)：输入坞内模型选择器、建议芯片与紧凑工具栏按钮。
- **Caption / Meta** (`400`, `12px`, 行高 `16px`)：模板卡片底部浏览量、点赞数（等宽数字对齐）与辅助标注。
- **Code** (`400`, `13px`, 行高 `1.5`)：生成代码预览、终端命令与等宽片段。

### Named Rules
**The Tight-Headline Rule.** `24px` 及以上标题必须施加 `-0.04em` 负字距，搭配 `600` 字重与 `1.25–1.33` 紧致行高；`14px` 以下正文与控件恢复 `0em` 字距。

## Layout

采用**极简通透单栏中心焦点 + 宽松 1200/1400px 网格画廊**的现代 Web 产品结构：

- **顶部导航栏（Header，`64px` 固定高度）**：与页面同底（`#FAFAFA` / `#000000`），无多余重底线（滚动时可浮现 `0 1px 0 rgba(0,0,0,0.10)` 轻边）。左置 `v0` 几何品牌标志 + 一排低对比平铺导航链接（`14px` `#4D4D4D`，高 `32px`，水平内边距 `12px`）；右置成对高对比操作按钮（`Log In` 描边白底 + `Sign Up` 实心黑底）。二级子菜单高 `46px`。
- **Hero 核心构建舞台**：上方留出大面积呼吸白空间，纵向居中依次排布：
  1. 轻巧公告胶囊（`32px` 高，`9999px` 圆角，白底 + `rgba(0,0,0,0.08)` 细边）；
  2. `32px` 紧字距居中主标题；
  3. **`690px` 居中主输入坞卡片**（`12px` 圆角，纯白底，`1px solid #C9C9C9` 明确边界，最小高 `108px`，内边距 `12px`）；
  4. 单行居中建议胶囊芯片组 + 右侧圆形刷新图标按钮。
- **模板与作品画廊网格**：容器最大宽度 `1200px`（工作台全屏模式可扩展至 `1400px`），左右页边距 `24px`。区块顶栏左右两端对齐（左 `24px` 标题，右分类芯片 + `Browse all >` 轻链接）；下方 3 列等宽卡片网格（`gap: 24px`，桌面 `≥ 1280px` 三列、平板 `≥ 768px` 两列、移动单列），每张预览缩略图严格采用 `16:9` 比例，底部紧跟头像 + 作品名 + 统计数据，不给整张卡片额外套厚重外框。
- **基准间距网格**：以 `4px` 为原子步进（`4 / 8 / 12 / 16 / 24 / 32 / 40 / 48 / 64 px`），区块间距 `32–48px`。

### Named Rules
**The Generous Stage Rule.** 首屏 Hero 舞台在提示词输入坞上下保留充足留白，不塞入次级营销副标题或特性卖点卡片，让用户视线在 `0.5s` 内直达输入焦点。

## Elevation & Depth

Geist 体系最鲜明的技术美学特征是**用双层 `box-shadow` 环绘制边框**，并与极低透明度多层漫射影叠加，在浅色与深色模式下都保持外科手术般的清晰度：

### Shadow Vocabulary
- **Shadow Border（Geist 招牌边框）**：Light `box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.08), 0 0 0 1px #FAFAFA`；Dark `box-shadow: 0 0 0 1px rgba(255, 255, 255, 0.145), 0 0 0 1px #000000`。
- **Small / Card Lift** (`box-shadow: 0 0 0 1px rgba(0,0,0,0.08), 0 2px 2px rgba(0,0,0,0.04)`)：轻量悬浮控件与微抬升卡片。
- **Medium / Large** (`box-shadow: 0 0 0 1px rgba(0,0,0,0.08), 0 2px 2px rgba(0,0,0,0.04), 0 8px 16px -4px rgba(0,0,0,0.04)`)：悬浮信息卡与展开控件。
- **Tooltip** (`box-shadow: 0 0 0 1px rgba(0,0,0,0.08), 0 1px 1px rgba(0,0,0,0.02), 0 4px 8px rgba(0,0,0,0.04)`)：轻盈浮起提示。
- **Menu / Popover** (`box-shadow: 0 0 0 1px rgba(0,0,0,0.08), 0 1px 1px rgba(0,0,0,0.02), 0 4px 8px -4px rgba(0,0,0,0.04), 0 16px 24px -8px rgba(0,0,0,0.06)`)：下拉菜单与浮层选择器。
- **Modal Elevated** (`box-shadow: 0 0 0 1px rgba(0,0,0,0.08), 0 32px 72px -12px rgba(0,0,0,0.06), 0 8px 32px -12px rgba(0,0,0,0.08), 0 8px 24px -12px rgba(0,0,0,0.12)`)：高层级模态对话框，遮罩采用 `80%` 透明画布底色。
- **Dual-Ring Focus** (`box-shadow: 0 0 0 2px <surface>, 0 0 0 4px <focus-blue>`)：清晰隔离的双环无障碍焦点。

### Named Rules
**The Crisp Ring Shadow Rule.** 任何需要投影的悬浮元素必须前置一层 `0 0 0 1px` 低透明度外环（浅色 `8%` 黑 / 深色 `14.5%` 白），杜绝无边界糊影。

## Shapes

圆角克制分明，通过**「矩形操作键 vs 胶囊引导芯片」**形成清晰的交互语义分工：

- **圆角梯度**：微型元素 `4px` → 标准按钮、导航项与小图标键 `6px`（基础表单 `5–6px`）→ 通用组件基准与缩略图卡片 `8px` → 主提示词输入坞、对话框与大型卡片 `12px` → 特大浮层 `24px` → 公告条、建议芯片、圆形图标按钮与头像 `9999px`。
- **线宽与图标**：边框精细克制（`1px` 透明灰边，输入坞外框可强化至 `#C9C9C9` / 深色 `#454545`），图标采用 `14–16px` 单色细线风格（描边 `1.5px`），与文本保持视觉等重。

## Components

微动效遵循 Vercel 标志性的轻盈略微过冲曲线 `cubic-bezier(0.175, 0.885, 0.32, 1.1)`（Popover `200ms`，Overlay 伴随 `scale 0.96 → 1.0` `300ms`）；常规状态切换 `150ms cubic-bezier(0.4, 0, 0.2, 1)`；骨架屏采用 `1.5s ease-in-out infinite reverse` 柔和流光。

### Buttons
- **Character:** 锐利干练的 6px 圆角建筑块。
- **Shape:** 标准高度 `32px`（表单标准 `40px`、大号 `48px`、输入坞内微按钮 `28×28px`），圆角 `6px`，水平内边距 `12px`，`14px` medium。
- **Primary:** 实心高对比墨色（浅 `#171717` 白字 / 深 `#EDEDED` 深黑字），同色 `1px` 边框。
- **Secondary:** 纯白底（深 `#0A0A0A`）配 `1px` 细边（浅 `#E4E4E7` / `rgba(0,0,0,0.08)`，深 `#2E2E2E`），悬停微灰。
- **Ghost:** 顶栏导航与工具键常态无底无框，文字 `#4D4D4D`（深 `#A1A1A1`），悬停渐亮至主文色并显极淡灰底。
- **Disabled Submit:** 输入为空时提交键呈 `28×28px` 浅灰底 `#F2F2F2`、图标 `#C9C9C9`配 `rgba(0,0,0,0.08)` 细边；有输入时瞬切高对比实黑/实白激活态。

### Chips & Promo Pills
- **Promo Pill（公告胶囊）:** 高 `32px`、`9999px` 全圆角、白底 + `1px` `rgba(0,0,0,0.08)` 细边，内边距 `0 8px 0 12px`，左置微型徽标、中为 `14px` 简洁文案（关键品牌词 `600` 加粗）、右置 `>` 引导箭头。
- **Suggestion / Filter Chips:** `9999px` 全圆角、白底（深 `#1A1A1A`）+ `1px` `rgba(0,0,0,0.08)` 细边，内边距 `4px 12px`，左置 `14px` 单色小图标 + `13px` `#4D4D4D` 文案，悬停边框微深、文字切主色。

### Cards / Containers
- **Template Showcase Card:** 上半部为 `16:9` 比例、圆角 `8px–12px` 的干净作品预览图，配 `Shadow Border` 极细外环；下半部直接裸露在画布上（不包额外白卡片框），左放 `28px` 圆形作者头像，右为两行紧凑信息（`14px` medium 标题 + `12px` 静音浏览与点赞计数）。

### Inputs / Fields & Prompt Composer
- **Standard Input:** 默认高 `40px`（小号 `32px`、大号 `48px`），圆角 `6px–8px`，`1px` 灰边，键盘聚焦呈现 Geist 双环蓝焦点（`--ds-focus-ring`）。
- **Hero Prompt Composer:** 居中宽 `690px`、圆角 `12px`、纯白底（深 `#0A0A0A` / `#141414`）、`1px solid #C9C9C9`（深 `#2E2E2E`）清晰边框，内边距 `12px`；上方为无边框多行输入区（`14px / 20px`），底部工具栏左置紧凑 `28px` 模型选择幽灵按钮（如 `v0 Max v`），右置语音图标键与 `28×28px` 提交方键。

### Navigation
- **Top Bar:** 单层水平结构，高 `64px`，左侧品牌标志 + 6 个以内扁平幽灵链接（无多余图标装饰），右侧仅保留 2 个清晰主/次动作键；移动端收折为抽屉菜单。

## Do's and Don'ts

### Do:
- **Do** 保持浅色 `#FAFAFA` 画布配 `#FFFFFF` 卡片、深色 `#000000` 画布配 `#0A0A0A` / `#1A1A1A` 卡片的明度对比。
- **Do** 对 `24px` 及以上标题使用 `-0.04em` 紧致负字距与 `600` 字重，体现 Geist 瑞士工程感。
- **Do** 使用「`6px` 矩形按钮 + `9999px` 胶囊引导芯片」的双形状对比，让正式操作与轻量建议一目了然。
- **Do** 用 `0 0 0 1px rgba(0,0,0,0.08)`（深色 `rgba(255,255,255,0.145)`）阴影环界定卡片与浮层边缘，并配合双环蓝色键盘焦点。
- **Do** 让画廊预览卡片的标题与统计元信息直接落在画布上，保持 `16:9` 预览区与文字区的清爽呼吸感。

### Don't:
- **Don't** 给主按钮或导航栏铺设彩色渐变或高饱和品牌底色——黑白高对比本身就是 v0 / Geist 的核心识别力。
- **Don't** 在 Hero 提示词输入坞周围堆砌营销宣传语、特性图标列或重投影卡片框。
- **Don't** 给模板画廊的每张卡片套上厚边框白盒子并加重阴影，避免视觉臃肿。
- **Don't** 对 `14px` 以下的正文、按钮或表格文字套用 `-0.04em` 过紧负字距，以免降低小字可读性。
- **Don't** 在规范中绑定特定框架类名，保持所有颜色、阴影环、圆角与动效曲线可无损转译到任意技术栈。
