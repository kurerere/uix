---
name: "Codex Desktop"
description: "通透雕塑感桌面设计体系（OpenAI Desktop / Codex），以纯黑/浅雾底层托起大圆角主画布、0.5px 发丝边、毛玻璃控制浮层与 OpenAI Sans 光学字重为核心。"
colors:
  solid-primary-light: "#181818"
  solid-primary-light-hover: "#303030"
  solid-primary-dark: "#F3F3F3"
  solid-primary-dark-hover: "#EDEDED"
  accent-blue: "#0285FF"
  accent-blue-hover: "#0169CC"
  accent-blue-300: "#339CFF"
  accent-blue-200: "#66B5FF"
  accent-blue-100: "#99CEFF"
  accent-blue-soft-light: "#E5F3FF"
  accent-blue-soft-dark: "#00284D"
  status-success-light: "#00A240"
  status-success-ink-light: "#00692A"
  status-success-dark: "#04B84C"
  status-success-ink-dark: "#40C977"
  status-success-soft-light: "#D9F4E4"
  status-danger-light: "#E02E2A"
  status-danger-ink-light: "#911E1B"
  status-danger-dark: "#FA423E"
  status-danger-ink-dark: "#FF6764"
  status-danger-soft-light: "#FFD9D9"
  status-danger-soft-dark: "#4D100E"
  status-warning-light: "#E25507"
  status-warning-ink-light: "#923B0F"
  status-warning-dark: "#FB6A22"
  status-warning-ink-dark: "#FF8549"
  status-warning-soft-light: "#FFE7D9"
  status-warning-soft-dark: "#4A2206"
  status-caution-light: "#BA8E00"
  status-caution-dark: "#FFD240"
  status-caution-soft-light: "#FFF6D9"
  discovery-purple-light: "#924FF7"
  discovery-purple-ink-light: "#6B3AB4"
  discovery-purple-dark: "#AD7BF9"
  discovery-purple-ink-dark: "#BE95FA"
  discovery-purple-soft-light: "#EFE5FE"
  surface-under-light: "#F9F9F9"
  surface-primary-light: "#FFFFFF"
  surface-tertiary-light: "#F3F3F3"
  surface-editor-light: "#EDEDED"
  codeblock-bg-light: "#FCFCFC"
  text-primary-light: "#1A1C1F"
  text-emphasis-light: "#0D0D0D"
  text-secondary-light: "#5D5D5D"
  text-tertiary-light: "#8F8F8F"
  border-subtle-light: "rgba(13, 13, 13, 0.05)"
  border-default-light: "rgba(13, 13, 13, 0.10)"
  border-strong-light: "rgba(13, 13, 13, 0.15)"
  ghost-hover-light: "rgba(13, 13, 13, 0.08)"
  ghost-active-light: "rgba(13, 13, 13, 0.12)"
  backdrop-light: "rgba(0, 0, 0, 0.30)"
  surface-under-dark: "#000000"
  surface-primary-dark: "#181818"
  surface-elevated-dark: "#212121"
  surface-elevated-opaque-dark: "#282828"
  surface-elevated-secondary-dark: "#303030"
  codeblock-bg-dark: "#101010"
  text-primary-dark: "#DFDFDF"
  text-emphasis-dark: "#FFFFFF"
  text-secondary-dark: "#AFAFAF"
  text-tertiary-dark: "#8F8F8F"
  border-subtle-dark: "rgba(255, 255, 255, 0.06)"
  border-default-dark: "rgba(255, 255, 255, 0.12)"
  border-strong-dark: "rgba(255, 255, 255, 0.20)"
  ghost-hover-dark: "rgba(255, 255, 255, 0.12)"
  ghost-active-dark: "rgba(255, 255, 255, 0.16)"
  backdrop-dark: "rgba(0, 0, 0, 0.50)"
typography:
  display:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "28px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "22px"
    fontWeight: 510
    lineHeight: 1.27
    letterSpacing: "-0.26px"
  title:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "16px"
    fontWeight: 590
    lineHeight: 1.5
    letterSpacing: "-0.02em"
  prose:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
  body:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "13px"
    fontWeight: 510
    lineHeight: 1.38
    letterSpacing: "-0.08px"
  label:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.43
    letterSpacing: "0em"
  caption:
    fontFamily: "OpenAI Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "11px"
    fontWeight: 590
    lineHeight: 1.33
    letterSpacing: "-0.15px"
  code:
    fontFamily: "SF Mono, ui-monospace, Menlo, Consolas, Liberation Mono, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0em"
rounded:
  2xs: "2px"
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "10px"
  xl: "12px"
  2xl: "16px"
  3xl: "20px"
  4xl: "24px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  2xl: "20px"
  3xl: "24px"
components:
  button-primary:
    backgroundColor: "{colors.solid-primary-light}"
    textColor: "{colors.surface-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: "0 12px"
    height: "32px"
  button-primary-hover:
    backgroundColor: "{colors.solid-primary-light-hover}"
    textColor: "{colors.surface-primary-light}"
  button-soft:
    backgroundColor: "{colors.surface-editor-light}"
    textColor: "{colors.text-emphasis-light}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: "0 12px"
    height: "32px"
  button-info:
    backgroundColor: "{colors.accent-blue}"
    textColor: "{colors.surface-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: "0 12px"
    height: "32px"
  button-toolbar:
    textColor: "{colors.text-tertiary-light}"
    rounded: "{rounded.lg}"
    width: "28px"
    height: "28px"
  segmented-track:
    backgroundColor: "{colors.surface-editor-light}"
    rounded: "{rounded.lg}"
    padding: "2px"
  segmented-thumb:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-emphasis-light}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "0 10px"
    height: "26px"
  input-outline:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-primary-light}"
    typography: "{typography.prose}"
    rounded: "{rounded.lg}"
    padding: "0 12px"
    height: "32px"
  composer-single-line:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.3xl}"
    padding: "8px 12px"
  composer-multiline:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.4xl}"
    padding: "12px 12px"
  menu-popover:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.2xl}"
    padding: "6px"
  modal-dialog:
    backgroundColor: "{colors.surface-primary-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.xl}"
    padding: "20px"
    width: "450px"
  tooltip-pill:
    backgroundColor: "{colors.solid-primary-light}"
    textColor: "{colors.surface-primary-light}"
    typography: "{typography.label}"
    rounded: "{rounded.2xl}"
    padding: "5px 12px"
  switch-track:
    backgroundColor: "{colors.surface-editor-light}"
    rounded: "{rounded.full}"
    width: "32px"
    height: "19px"
  switch-track-checked:
    backgroundColor: "{colors.accent-blue}"
    rounded: "{rounded.full}"
    width: "32px"
    height: "19px"
---

# Design System: Codex Desktop

## Overview

**Creative North Star: "The Sculpted Glass Sheet"**

Codex Desktop 代表 OpenAI 桌面端的现代通透雕塑美学（融合 **Operate** 与 **Read** 双重体验）。与 Claude Desktop 的纯平细线切分、Devin Desktop 的多卡槽隙工作台都不同，Codex Desktop 用一张**圆润宽大的单主内容画布（Main Surface Sheet）**轻盈地叠置在深黑（深色模式 `#000000`）或浅雾（浅色模式 `#F9F9F9`）的底层侧栏之上，通过 `10–12px` 内切圆角、精细的 **`0.5px` 发丝边框**与原生毛玻璃控制浮层（`blur 12–24px`），呈现出接近现代 macOS 原生器物的通透感与空间纵深。

它的圆角更慷慨（工具按钮 `10px`、悬浮菜单与 Tooltip `16px`、输入坞 `22–24px`），动效更丝滑克制（采用指数级平滑入场曲线 `cubic-bezier(0.19, 1, 0.22, 1)` 与无生硬回弹的临界阻尼弹簧），并通过完整的 8 组语义色族与 5 种按钮材质变体（`solid / soft / surface / outline / ghost`）支撑从极简对话到复杂工程审批的全场景桌面交互。

**Key Characteristics:**
- **纯黑底层托举画布（Dark Mode Signature）**：深色模式下侧栏底层沉至纯黑 `#000000`，主画布抬升为深炭 `#181818`，浮层依次升至 `#212121` / `#282828` / `#303030`，层次极度利落。
- **宽大、数学嵌套的圆角体系**：全局支持 `--corner-radius-scale` 缩放因子，内嵌圆角严格遵循「子圆角 = 外圆角 - 间距」计算公式（如 `16px` 菜单减 `6px` 边距 → `10px` 菜单项）。
- **`0.5px` 发丝边 + 毛玻璃材质**：在高清屏上用 `0.5px` 极细边框替代传统 `1px` 线框，浮层面板与菜单支持 `12–24px` 背景模糊。
- **精细光学字重**：使用 `OpenAI Sans` 的 `510`（控件/卡片标题）与 `590`（表单标题/未读徽标）微调字重，兼顾清晰度与轻盈感。

## Colors

中性色采用无色偏纯黑灰阶（`#FFFFFF` 至 `#0D0D0D` / `#000000`），配合 6 组完整 14 阶语义调色板（Blue / Green / Red / Orange / Yellow / Purple），所有透明度交互底均从前景色派生（浅色基准 `#0D0D0D`，深色基准 `#FFFFFF`）。

### Primary
- **Solid Primary Ink** (浅色 `#181818`，悬停 `#303030`，按下 `#414141`，配 `#FFFFFF` 文字；深色反转 `#F3F3F3`，悬停 `#EDEDED`，按下 `#DCDCDC`，配 `#0D0D0D` 文字)：核心实心主按钮、单选指示心与浅色 Tooltip 背景，靠极致黑白反差建立权威感。

### Secondary
- **Accent Blue / Info** (`#0285FF` 实心填充，`#0169CC` 悬停与浅色链接/焦点环；深色焦点 `#0285FF`、文本 `#66B5FF` / `#99CEFF`；柔和底浅色 `#E5F3FF` / 深色 `#00284D`)：焦点环、开关激活轨、链接、已连接状态、提示徽章与流式文字入场瞬态染色。

### Tertiary
- **Success Green** (浅色 `#00A240` / 深字 `#00692A` / 浅底 `#D9F4E4`；深色 `#04B84C` / 亮字 `#40C977`)：执行通过、代码新增与确认状态。
- **Danger Red** (浅色 `#E02E2A` / 深字 `#911E1B` / 浅底 `#FFD9D9`；深色 `#FA423E` / 亮字 `#FF6764` / 深底 `#4D100E`)：破坏性操作、表单校验失败与异常回溯。
- **Warning Orange** (浅色 `#E25507` / 深字 `#923B0F` / 浅底 `#FFE7D9`；深色 `#FB6A22` / 亮字 `#FF8549` / 深底 `#4A2206`)：风险提示与权限警告。
- **Caution Yellow** (浅色 `#BA8E00` 实心 / `#916F00` 字 / `#FFF6D9` 浅底；深色 `#FFD240`)：温和提醒与内部实验徽章。
- **Discovery Purple** (浅色 `#924FF7` 实心 / `#6B3AB4` 字 / `#EFE5FE` 浅底；深色 `#AD7BF9` / `#BE95FA`)：新能力、探索提示与扩展功能标识。
- **Codeblock 5-Stop Syntax**：代码块背景浅 `#FCFCFC` / 深 `#101010`；五档语法色分别为 1（浅 `#C0660D` / 深 `#FFE48C`）、2（浅 `#0169CC` / 深 `#66B5FF`）、3（浅 `#008635` / 深 `#40C977`）、4（`#E04C91`）、5（浅 `#8046D9` / 深 `#AD7BF9`）。

### Neutral
- **Light Surface Ladder**：底层侧栏 `Surface Under` `#F9F9F9` → 主画布 `Surface Primary` `#FFFFFF` → 次级填充 `#F3F3F3` / 编辑器与软按钮底 `#EDEDED` → 悬浮菜单/弹窗 `#FFFFFF`。
- **Dark Surface Ladder**：底层侧栏 `Surface Under` `#000000` → 主画布 `Surface Primary` `#181818` → 一级浮层 `#212121` → 不透明浮层 `#282828` → 二级浮层/分段滑块 `#303030`。
- **Text Hierarchy**：浅色正文 `#1A1C1F`（强调 `#0D0D0D`）、次级 `#5D5D5D`（约 `65%` 前景）、三级/禁用 `#8F8F8F`；深色正文 `#DFDFDF`（强调 `#FFFFFF`）、次级 `#AFAFAF`、三级 `#8F8F8F`、禁用 `#5D5D5D`。
- **Alpha & Border Ladder**：细边 subtle 浅 `5%` / 深 `6%`，默认边框浅 `10%` / 深 `12%`，强边框浅 `15%` / 深 `20%`；Ghost 按钮悬停浅 `8%` / 深 `12%`，按下浅 `12%` / 深 `16%`。

### Named Rules
**The Pitch-Black Underlayer Rule.** 深色模式下，窗口外框与侧栏底层必须下沉至纯黑 `#000000`，让 `#181818` 主画布像一块悬浮雕塑面板一样自然浮出，绝不把侧栏画得比主画布更亮。

**The Hairline-First Rule.** 高分屏界面优先使用 `0.5px` 发丝边勾勒按钮、菜单与浮层轮廓；只有输入框聚焦或无障碍强边界场景才加厚至 `1px–2px`。

## Typography

**Display Font:** OpenAI Sans（回退系统无衬线；可选 `OpenAI Serif Light` 用于编辑/长文点缀）。
**Body Font:** OpenAI Sans（`-apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif`）。
**Label/Mono Font:** `SF Mono` / `ui-monospace, Menlo, Consolas, monospace`。

**Character:** 干净、柔和且略带几何现代感的无衬线字形，利用精确到十位数的微调字重（`510` 与 `590`）让控件标签比 `400` 更有骨力、又比 `600` 更通透不发闷。

### Hierarchy
- **Display / App Heading** (`600`, `28px`, 行高 `1.25`, 字距 `-0.025em`)：应用级欢迎大标题。
- **Headline / Card Title** (`510`, `22px`, 行高 `28px`, 字距 `-0.26px`；常规中标题 `20px / 26px`, `600`)：卡片与引导页标题。
- **Title / Form Title** (`590`, `16px`, 行高 `24px`, 字距 `-0.02em`)：表单与模态框分组主标题。
- **Prose / Document** (`400`, `14px`, 行高 `21px`)：正文阅读、长段内容与动态列表行。
- **Body / Control Label** (`510`, `13px`, 行高 `18px`, 字距 `-0.08px`)：按钮、导航项、表单标签与建议描述的默认桌面字阶。
- **Label / Text-SM** (`400 / 500`, `12px`, 行高 `17px`)：菜单项、分段控制、Tooltip 与说明文字。
- **Caption / Badge** (`590`, `11px`, 行高 `15px`, 字距 `-0.15px`)：未读计数徽标、小号状态标签与快捷键提示。
- **Code** (`400`, `13px`, 行高 `1.5`；Diff 视图收紧 `1px` 至 `12px`)：代码块、终端输出与差异视图。

### Named Rules
**The Optical Mid-Weight Rule.** 按钮、控件标签与卡片标题使用 `510` 字重（不支持可变字重时取 `500`），表单标题与小型徽章使用 `590`（不支持时取 `600`），避免界面大片使用笨重的 `700` 粗体。

## Layout

采用**底层侧栏托举单主圆角画布（Underlayer Sidebar + Sculpted Main Surface）**的流畅空间模型：

- **标题栏与工具栏节奏**：窗口顶栏高 `44px`，主内容区顶置工具栏高 `46px`（紧凑工具栏 `36px`，子面板工具栏 `40px`）。滚动内容区上方覆盖平滑顶部渐隐遮罩（`MainContentTopFade`），与主画布左上角圆角贴合裁切。
- **左侧导航栏（`Surface Under` 底层）**：宽度自适应 `clamp(240px, 275px, min(520px, 100vw - 320px))`，默认 `275px`，行水平内边距 `8px`、图标与文本间距 `8px`。侧栏收起时，主画布圆角通过 `150ms` 平滑过渡展开至贴齐窗口边界；侧栏作为悬浮抽屉展开时，带有内缩圆角与发丝投影，停靠时再平滑融合（`settle-sidebar`）。
- **主内容画布（Main Surface）**：在 Windows / 桌面壳层中左上角（及非全屏边）带 `10px–12px` 圆角（`radius-lg` / `radius-xl`），承载居中 `max-width: 800px`（左右留白 `20px`）的核心内容流；宽表格/宽代码块支持突破至 `1024px`（`64rem`）、最大高度 `80vh`。
- **统一控件高度阶梯（10 档精密尺码）**：`20 / 22 / 24 / 26 / 28 / 32 / 36 / 40 / 44 / 48 px`；常规设置行高 `64px`（`4rem`），页内搜索框高 `32px`，空态页最小高度 `420px`。

### Named Rules
**The Concentric Inset Formula Rule.** 所有容器与内部元素的圆角和边距必须数学联动：面板顶栏按钮外距 = `外容器圆角(16px) - 按钮圆角(10px) = 6px`；菜单项圆角 = `菜单圆角(16px) - 菜单内边距(6px) = 10px`。

## Elevation & Depth

采用**4 档紧致定向投影（`100–400`）+ `0.5px` 发丝边 + 原生毛玻璃（Native Glass）**混合深度体系，拒绝大半径发散脏影：

### Shadow Vocabulary
- **Hairline Rim** (`box-shadow: 0 0 0 0.5px rgba(0, 0, 0, 0.10)`)：极细物理边界，常与各级投影组合使用。
- **Elevation 100 / SM** (`box-shadow: 0 1px 2px -1px rgba(0, 0, 0, 0.08)`；Dark `0.20`)：微抬升控件与激活标签。
- **Elevation 200 / MD** (`box-shadow: 0 2px 4px -1px rgba(0, 0, 0, 0.08)`；Dark `0.20`)：浮动工具按钮与卡片。
- **Elevation 300 / LG** (`box-shadow: 0 4px 8px -2px rgba(0, 0, 0, 0.10)`；Dark `0.36`)：轻量悬浮面板与卡片。
- **Elevation 400 / XL Spread** (`box-shadow: 0 0 0 0.5px <border>, 0 8px 16px -4px rgba(0, 0, 0, 0.12)`；Dark `0.30`)：下拉菜单、控制浮层（搭配 `blur(16–24px)` 毛玻璃）。
- **Elevation 2XL & Tooltip** (Modal `0 16px 32px -8px rgba(0, 0, 0, 0.19)`；Tooltip `0 8px 18px rgba(15, 23, 42, 0.20)`；Sheet 上浮 `0 -8px 16px rgba(0,0,0,0.07), 0 -2px 6px rgba(0,0,0,0.05), 0 0 0 1px <border>`）。
- **Frosted Glass Material**：控制浮层与原生玻璃表面使用 `backdrop-filter: blur(12px | 16px | 24px)`，在原生毛玻璃激活时叠加 `16%` 透明主画布色。

### Named Rules
**The Negative-Spread Crispness Rule.** 所有标准阴影均带负扩展值（`-1px` 至 `-8px`）与 `0.5px` 发丝环组合，让浮层显得干脆清透而非烟熏模糊。

## Shapes

圆角比传统桌面工具更大、更具现代工业圆润感，且全部乘以统一缩放系数（默认 `1`）：

- **圆角刻度**：`2xs 2px` · `xs 4px`（小徽章）· `sm 6px`（链接聚焦）· `md 8px`（常规小控与滑块）· `lg 10px`（工具栏按钮、常规操作按钮、主画布内角）· `xl 12px`（对话框、Popover、Electron 菜单项）· `2xl 16px`（悬浮菜单、Tooltip、浏览器对话框）· `3xl 20px`（建议卡片、单行输入坞 `22px`）· `4xl 24px`（表单弹窗、多行输入坞）· `full 9999px`（头像、开关、胶囊按钮）。
- **胶囊内边距补偿**：胶囊形（Pill）按钮水平内边距自动乘以 `1.33×`（`--control-gutter-pill-scaling`），避免文字靠近圆弧显得局促。

## Components

全局动效以丝滑、不炫技为准则：基础过渡 `150ms`、中速 `200ms`、舒展 `300ms`；入场使用指数平滑 `cubic-bezier(0.19, 1, 0.22, 1)` 或利落 `cubic-bezier(0.23, 1, 0.32, 1)`，退场 `cubic-bezier(0.8, 0, 0.4, 1)`，位移 `cubic-bezier(0.65, 0, 0.35, 1)`；复选框勾选可用 `cubic-bezier(0.16, 1.8, 0.3, 1)` 轻弹确认。

### Buttons
- **Character:** 材质层次最丰富的核心控件，五档变体覆盖全场景。
- **Shape:** 宽大圆角 `10px`（动作/工具栏按钮），常规高度 `32px`（紧凑 `28px`、微型 `24px`），图标与文本间距 `3 / 4 / 6 px`。
- **5 Variants:**
  - `solid`：实心高对比（Primary 浅 `#181818` / 深 `#F3F3F3`，或 Info 蓝 `#0285FF` / Danger 红 `#E02E2A`）。
  - `soft`：柔和中性底（浅 `#EDEDED` / 深 `#303030`，或各语义 `50` 档浅底），悬停深一阶。
  - `surface`：微透明底 + `1px` 内描边 + 轻空气感投影（`0 2px 8px rgba(0,0,0,0.04)`）。
  - `outline`：透明底 + `16%`（深色 `25%`）线框，悬停出现 `2%–4%` 微底。
  - `ghost`：常态透明，悬停 `8%`（深色 `12%`）柔底，按下 `12%`（深色 `16%`）。

### Segmented Controls & Switches
- **SegmentedControl:** 外轨 `2px` 边距、`2px` 间隙、浅色 `#EDEDED` / 深色 `#0D0D0D` 底；激活滑块浅色纯白 `#FFFFFF` / 深色 `#303030`，带柔和投影 `0 1px 4px -1px rgba(0,0,0,0.20)` 与 `600` 字重。
- **Switch:** 紧凑 `32×19px` 全圆角轨道，`3px` 内缩的 `13×13px` 纯白圆钮（投影 `0 1px 2px rgba(0,0,0,0.20)`）；未选态浅 `#DFDFDF` / 深 `#414141`，开启态 `#0285FF`（或浅色高对比 `#181818`）。
- **Radio & Slider:** Radio `16px` 圆环配 `6px` 实心内点；Slider 轨浅 `#DFDFDF` / 深 `#414141`，已选段 `#767676` / `#8F8F8F`。

### Inputs / Fields & Command Menu
- **Inputs:** 默认高 `32px`、`10px` 圆角（紧凑 `8px`），分 `outline`（边框默认 `16%` → 悬停 `25%` → 聚焦 `50%`）与 `soft`（柔底无框，聚焦现 `20%` 细边）两种形态；校验失败切换为红边（浅 `#E02E2A` / 深 `#BA2623`）。
- **Command Menu (`cmdk`):** 弹窗圆角 `12–16px`，内部列表项带清晰悬停/键盘选中柔底，支持顶部挂载于输入坞上方展开。

### Menus, Modals & Tooltips
- **Menu / Popover:** `16px` 外圆角（Electron 端 `4px` 内边距配 `12px` 菜单项圆角，`0.5px` 发丝边 + `Elevation 400` + 可选 `blur(16px)`）；菜单项水平内边距 `8–12px`，分隔线左右留白对齐文案。
- **Modal / Dialog:** 宽 `250–450px`（表单弹窗大圆角 `24px`，常规对话框 `12–16px`），内边距 `20px`；遮罩浅色 `rgba(0,0,0,0.30)` 或 `rgba(242,242,242,0.50) + blur(1px)`，深色 `rgba(0,0,0,0.50)`；高度变化时平滑过渡 `300ms`（`cubic-bezier(0.23, 1, 0.32, 1)`）。
- **Tooltip:** 标志性 `16px` 大圆角胶囊，浅色深墨底白字（`#181818` / `#FFFFFF`）、深色亮浮层底（`#303030` / `#DFDFDF`），内边距 `5px 12px`，字距 `-0.15px`，内嵌快捷键用 `25%` 透明前景色微徽章。

### Signature Patterns
- **Generous Pill Composer:** 单行态圆角 `22px`，多行展开态圆角 `24px`，底色 `surface-elevated`（浅 `#FFFFFF` / 深 `#212121`），内部操作按钮采用 `28px`（小号 `20px`）紧凑方阵，支持上方展开命令/引用托盘。
- **Streaming Word Arrival:** 流式生成文字时，新抵达词段在 `700ms` 内由柔和信息蓝（`accent-blue`）透明淡入并过渡为正文色，赋予实时输出清晰呼吸感；关闭动态效果时直接静态呈现。
- **User Message Bubble & Avatars:** 用户消息气泡采用极轻透明底（浅 `5%` / 深 `8%`，紧凑态浅 `#F3F3F3` / 深 `#414141`）；头像默认 `28px` 全圆角，重叠头像组使用 `3px` 主画布色镂空切边与 `-8px` 负间距。
- **Stacked Folder & Ready Pulse:** 多层文件/目录采用三层微错位卡片叠影表达集合感；后台任务就绪时提供 `1.25s` 柔和脉冲点提示。

## Do's and Don'ts

### Do:
- **Do** 在深色模式下使用纯黑 `#000000` 侧栏底层托举 `#181818` 主画布与 `#212121–#303030` 浮层，保持清晰的立体台阶。
- **Do** 严格遵守同心嵌套圆角公式（子圆角 = 外圆角 - 内边距），让 `16px` 菜单、`22–24px` 输入坞和 `10px` 按钮在视觉上自然贴合。
- **Do** 在高分屏上优先使用 `0.5px` 发丝边与带负扩展值的 `Elevation 100–400` 投影，保持浮层利落通透。
- **Do** 遵循 `510`（控件/卡片标题）与 `590`（表单标题/徽标）的轻盈光学字重阶梯，并对开关、菜单和流式文字提供 `prefers-reduced-motion` 静态降级。
- **Do** 让主按钮默认保持黑白高对比实底（浅 `#181818` / 深 `#F3F3F3`），把 OpenAI 蓝 `#0285FF` 保留给焦点环、开关开启态、链接与信息强调。

### Don't:
- **Don't** 用尖锐小圆角（如 `2–4px`）替代工具栏按钮（`10px`）、菜单（`16px`）或输入坞（`22–24px`），那会破坏 Codex Desktop 标志性的雕塑圆润气质。
- **Don't** 在浮层阴影上使用大半径正扩展重黑影；缺少负扩展与 `0.5px` 发丝边会让毛玻璃与白底卡片显得浑浊。
- **Don't** 在暗色模式下把底层侧栏调得比主画布亮，或把 Tooltip 与弹窗背景融进同一明度层。
- **Don't** 在静态界面滥用夸张弹跳动画；除微缩复选框确认外，面板、弹窗与高度展开均应采用指数平滑或临界阻尼无过冲曲线。
- **Don't** 在设计规范中绑定特定框架类名，保持所有色彩、圆角、毛玻璃与动效参数可跨平台无损转译。
