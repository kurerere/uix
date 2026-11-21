---
name: "Claude Desktop"
description: "静谧精密的桌面应用设计体系（CDS + Fizzy Lake），以极低噪表面层次、1px 细线分隔与克制语义色构建可长时间专注的桌面工作台。"
colors:
  ink-primary: "#191919"
  ink-primary-hover: "#3C3C3C"
  ink-primary-dark: "#EFEFEF"
  ink-primary-dark-hover: "#D7D7D7"
  claude-clay: "#D97757"
  claude-clay-deep: "#C6613F"
  focus-cobalt: "#2A78D6"
  focus-cobalt-hover: "#2171CA"
  focus-cobalt-ink: "#184F95"
  focus-cobalt-dark: "#6DA7EC"
  pro-violet: "#785EE8"
  pro-violet-ink: "#5437B8"
  pro-violet-dark: "#A89AF0"
  status-success: "#10A122"
  status-success-ink: "#006C10"
  status-success-dark: "#53C556"
  status-warning: "#E49C06"
  status-warning-ink: "#895902"
  status-danger: "#C83839"
  status-danger-ink: "#A42528"
  status-danger-dark: "#F17778"
  canvas-light: "#FFFFFF"
  sidebar-mist: "#FAFAFA"
  text-primary-light: "rgba(0, 0, 0, 0.90)"
  text-secondary-light: "rgba(0, 0, 0, 0.60)"
  text-muted-light: "rgba(0, 0, 0, 0.47)"
  text-disabled-light: "rgba(11, 11, 11, 0.35)"
  border-subtle-light: "rgba(0, 0, 0, 0.08)"
  border-control-light: "rgba(0, 0, 0, 0.12)"
  border-strong-light: "rgba(11, 11, 11, 0.20)"
  ghost-hover-light: "rgba(0, 0, 0, 0.05)"
  ghost-selected-light: "rgba(0, 0, 0, 0.10)"
  surface-card-light: "rgba(0, 0, 0, 0.035)"
  backdrop-light: "rgba(0, 0, 0, 0.40)"
  canvas-dark: "#191919"
  sidebar-charcoal: "#1F1F1F"
  popover-slate: "#303030"
  text-primary-dark: "rgba(255, 255, 255, 0.93)"
  text-secondary-dark: "rgba(255, 255, 255, 0.57)"
  text-muted-dark: "rgba(255, 255, 255, 0.40)"
  text-disabled-dark: "rgba(255, 255, 255, 0.35)"
  border-subtle-dark: "rgba(255, 255, 255, 0.07)"
  border-control-dark: "rgba(255, 255, 255, 0.12)"
  border-strong-dark: "rgba(255, 255, 255, 0.22)"
  ghost-hover-dark: "rgba(255, 255, 255, 0.075)"
  ghost-selected-dark: "rgba(255, 255, 255, 0.15)"
  surface-card-dark: "rgba(255, 255, 255, 0.04)"
  backdrop-dark: "rgba(0, 0, 0, 0.50)"
  parchment-canvas: "#FAF9F5"
  parchment-sidebar: "#F5F4EE"
  parchment-recess: "#F0EEE6"
  obsidian-canvas: "#262624"
  obsidian-sidebar: "#1F1E1D"
  diff-added-light: "#1E9E3C"
  diff-added-bg-light: "#EAF8EC"
  diff-removed-light: "#CD2054"
  diff-removed-bg-light: "#FEEEEE"
  diff-added-dark: "#32D74B"
  diff-added-bg-dark: "#15331B"
  diff-removed-dark: "#FF2C56"
  diff-removed-bg-dark: "#3C181B"
typography:
  display:
    fontFamily: "Anthropic Serif, Georgia, Songti SC, Noto Serif CJK SC, serif"
    fontSize: "28px"
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "14px"
    fontWeight: 580
    lineHeight: 1.4
    letterSpacing: "0em"
  prose:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.62
    letterSpacing: "0em"
  body:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.46
    letterSpacing: "0em"
  label:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.33
    letterSpacing: "0em"
  caption:
    fontFamily: "Anthropic Sans, -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: "11px"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "0em"
  code:
    fontFamily: "JetBrains Mono, SF Mono, Menlo, Consolas, monospace"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "0em"
rounded:
  xs: "4px"
  badge: "5px"
  sm: "6px"
  md: "8px"
  lg: "10px"
  xl: "14px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "12px"
  xl: "16px"
  2xl: "20px"
  3xl: "32px"
components:
  button-primary:
    backgroundColor: "{colors.ink-primary}"
    textColor: "{colors.canvas-light}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "0 12px"
    height: "28px"
  button-primary-hover:
    backgroundColor: "{colors.ink-primary-hover}"
    textColor: "{colors.canvas-light}"
  button-secondary:
    backgroundColor: "{colors.ghost-hover-light}"
    textColor: "{colors.text-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "0 12px"
    height: "28px"
  button-ghost-hover:
    backgroundColor: "{colors.ghost-hover-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.sm}"
  button-icon:
    textColor: "{colors.text-secondary-light}"
    rounded: "{rounded.sm}"
    width: "28px"
    height: "28px"
  nav-item-active:
    backgroundColor: "{colors.ghost-selected-light}"
    textColor: "{colors.text-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "0 10px"
    height: "30px"
  segmented-track:
    backgroundColor: "{colors.ghost-hover-light}"
    rounded: "{rounded.md}"
    padding: "2px"
  segmented-thumb:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.text-primary-light}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "0 10px"
    height: "26px"
  input-field:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.text-primary-light}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "0 10px"
    height: "32px"
  composer-dock:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.xl}"
    padding: "6px 10px"
  modal-dialog:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.xl}"
    width: "860px"
    height: "630px"
  popover-menu:
    backgroundColor: "{colors.canvas-light}"
    textColor: "{colors.text-primary-light}"
    rounded: "{rounded.lg}"
    padding: "4px"
  badge-monogram:
    backgroundColor: "{colors.surface-card-light}"
    textColor: "{colors.text-secondary-light}"
    typography: "{typography.caption}"
    rounded: "{rounded.badge}"
    width: "20px"
    height: "20px"
  switch-track:
    backgroundColor: "{colors.border-strong-light}"
    rounded: "{rounded.full}"
    width: "34px"
    height: "20px"
  switch-track-checked:
    backgroundColor: "{colors.focus-cobalt}"
    rounded: "{rounded.full}"
    width: "34px"
    height: "20px"
---

# Design System: Claude Desktop

## Overview

**Creative North Star: "The Quiet Instrument"**

Claude Desktop 的界面哲学将桌面应用视为一件可连续使用数小时而不令人疲倦的精密器物。它属于典型的 **Operate / Read** 复合型界面：界面本身退居幕后，不与用户正在阅读的长文、代码、表格或数据争夺注意力。所有视觉层次均由极低对比度的表面明度差、`1px` 低透明度细线以及克制的字重阶梯自然建立，而不是依靠厚重卡片边框、彩色标题栏或装饰性渐变。

这套设计体系与具体技术栈完全解耦——无论目标是 Electron、Tauri、Web（React / Vue / Svelte）、Flutter、Qt/QML、SwiftUI 还是 WinUI/WPF/Avalonia，均可按本规范将色值、空间比例、组件状态与物理动效精确映射到目标平台。它在保持极致克制的同时，保留了令人愉悦的物理触感：按钮按下时有干脆的 `0.975` 微缩并在释放时带轻微过冲弹簧回弹，浮层与侧栏切换遵循利落的 `cubic-bezier(0.32, 0.72, 0, 1)` 曲线。

**Key Characteristics:**
- 浅色模式下以纯净主画布与极淡雾灰侧栏区分空间，深色模式下用逐级抬升的深碳灰表达浮层纵深。
- 主操作按钮采用高对比中性墨色而非高饱和品牌色，陶土品牌色仅作为极小面积的识别点睛。
- 侧栏顶栏与侧栏主体无缝贯通，无多余水平割裂线；阅读内容区配备柔和的顶部/底部滚动渐隐遮罩。
- 紧凑、高扫描效率的桌面密度（默认 `13px` 控件正文、`14px` 阅读正文、`28–30px` 行高），杜绝冗余次要标签与大块装饰留白。

## Colors

色板以中性无干扰的 **Fizzy Lake**（现代桌面默认）为核心，同时提供偏温润纸质的 **Warm Classic** 可选阅读变体；彩色被严格收束为聚焦、高阶档位、品牌标识与状态反馈。

### Primary
- **Ink Primary** (`#191919`，悬停 `#3C3C3C`；深色反转 `#EFEFEF`，悬停 `#D7D7D7`)：核心主操作按钮（CTA、发送、确认执行）填充色，配纯白或深碳文字，确保高对比且不喧宾夺主。
- **Claude Clay** (`#D97757`，强调 `#C6613F`)：品牌专属陶土橙，仅用于极小面积的品牌星芒标识、关键待处理高亮或空状态徽记，不用于大面积工具栏、按钮组或导航背景。

### Secondary
- **Focus Cobalt** (`#2A78D6`，悬停 `#2171CA`；文本浅色 `#184F95` / 深色 `#6DA7EC`)：键盘焦点环、开关开启轨道、多选高亮底（`12%` 透明）与链接强调色。
- **Pro Violet** (`#785EE8`；文本浅色 `#5437B8` / 深色 `#A89AF0`)：高阶模式、专业档位徽章与特权标签（柔和底 `rgba(120, 94, 232, 0.12)`）。

### Tertiary
- **Status Success** (`#10A122`；文本浅色 `#006C10` / 深色 `#53C556`)：成功状态徽章、在线指示点与确认反馈，浅底使用 `rgba(16, 161, 34, 0.14)`（深色 `0.12`）。
- **Status Warning** (`#E49C06`；文本浅色 `#895902` / 深色 `#E49C06`)：高占比进度胶囊、过期提醒与警示横幅，浅底使用 `rgba(251, 179, 21, 0.12)`（深色 `0.08`）。
- **Status Danger** (`#C83839` 浅色实底 / `#DC3C3D` 深色实底；文本浅色 `#A42528` / 深色 `#F17778`)：不可逆删除按钮、表单校验错误与高危提示，浅底 `rgba(220, 60, 61, 0.12)`。
- **Diff & Code Accents**：新增绿（浅 `#1E9E3C` / 行底 `#EAF8EC`；深 `#32D74B` / 行底 `#15331B`）、删除红（浅 `#CD2054` / 行底 `#FEEEEE`；深 `#FF2C56` / 行底 `#3C181B`）、修改黄（浅 `#98801F` / 深 `#FFD014`）。代码语法色板如下：
  - **Light 代码**（前景 `#14181F`）：注释 `#6E7685`、关键字 `#8100C2`、字符串 `#008000`、数字 `#008080`、属性 `#B80A18`、函数 `#0051C2`、变量/类型 `#B34A00`。
  - **Dark 代码**（前景 `#EAECF0`）：注释 `#818998`、关键字 `#CA7AF5`、字符串 `#9EE864`、数字 `#5EEDED`、属性 `#F57A84`、函数 `#70B8FF`、变量/类型 `#FAAD60`。

### Neutral
- **Canvas Light / Dark** (`#FFFFFF` / `#191919`)：主工作区与右侧检查器底色。
- **Sidebar Mist / Charcoal** (`#FAFAFA` / `#1F1F1F`)：左侧导航栏与侧栏顶栏底色，与主画布形成极柔和的明度分界。
- **Popover Slate** (浅色 `#FFFFFF` / 深色 `#303030`)：下拉菜单、命令面板、右键菜单与 Tooltip 浮层底色；模态弹窗深色主体取 `#1F1F1F`。
- **Text Hierarchy**：浅色主/次/静音/禁用分别为 `rgba(0,0,0,0.90)` / `0.60` / `0.47` / `0.35`；深色主/次/静音/禁用分别为 `rgba(255,255,255,0.93)` / `0.57` / `0.40` / `0.35`。
- **Borders & Ghost Fills**：常规分割线浅 `rgba(0,0,0,0.08)` / 深 `rgba(255,255,255,0.07)`；控件边框 `0.12`；强调外环 `0.20–0.22`。幽灵悬停浅 `5%` / 深 `7.5%`；幽灵选中浅 `10%` / 深 `15%`。
- **Warm Classic 变体（可选，面向长文阅读/写作应用）**：浅色画布 `#FAF9F5`、侧栏 `#F5F4EE`、凹陷块 `#F0EEE6`、主文 `#141413`；深色画布 `#262624`、侧栏 `#1F1E1D`、卡片 `#30302E`、主文 `#FAF9F5`。
- **暖灰扩展阶梯**（需要额外中性灰层级时避免冷青灰）：`#FCFCFB` · `#F9F9F7` · `#F3F3F0` · `#EDECE8` · `#E1E0D9` · `#C3C2B7` · `#A5A49A` · `#898781` · `#6D6B67` · `#52514E` · `#383835` · `#20201F` · `#151515` · `#0B0B0B`。

### Named Rules
**The Neutral Authority Rule.** 主按钮、选中态与主要导航层级永远由中性墨色与透明灰阶承担，不把品牌色或高亮蓝铺成大面积实心背景。

**The Brand Restraint Rule.** 陶土橙 `#D97757` 在单屏中的视觉占比严格控制在 `≤ 2%`，仅出现在品牌标识或极少量关键标记处，稀缺性本身就是识别度。

**The Dark Elevation Shift Rule.** 深色模式下不可用纯黑阴影制造层次，必须靠表面明度逐级抬升区分层级：主画布 `#191919` → 侧栏/弹窗 `#1F1F1F` → 浮层菜单/Tooltip `#303030`。

## Typography

**Display Font:** Anthropic Serif（回退 `Georgia`, `Songti SC`, `Noto Serif CJK SC`, serif）——仅用于空态大问候语或长文阅读可选衬线模式。
**Body Font:** Anthropic Sans（平台系统无衬线回退：macOS `SF Pro` + `PingFang SC`，Windows `Segoe UI` + `Microsoft YaHei`，Linux `Inter` + `Noto Sans CJK`）。
**Label/Mono Font:** JetBrains Mono（回退 `SF Mono`, `Menlo`, `Consolas`, monospace）。

**Character:** 人文无衬线承载全部桌面操作控件，紧凑而清晰；等宽字体严格以 `1.45×` 行高呈现代码、路径、终端与差异视图；衬线字体只在需要呼吸感的空态或阅读模式下退场补位。

### Hierarchy
- **Display** (`400`, `28px`, 行高 `1.25`, 字距 `-0.01em`)：空态引导问候语，衬线字体，克制不张扬。
- **Headline** (`600`, `20px`, 行高 `1.25`, 字距 `-0.01em`)：独立页面主标题。
- **Title** (`580` 或 `600`, `14–15px`, 行高 `1.4`)：模态框顶栏标题、设置分区标题与正文小节标题。
- **Prose** (`400`, `14px`, 行高 `1.62`；舒适密度 `16px` / `1.55`)：长文阅读、文档与对话正文，推荐单行宽控制在 `65–75ch`。
- **Body** (`400 / 500`, `13px`, 行高 `1.46`；舒适密度 `14px`)：侧栏项、按钮、表单输入、列表与表格单元格的桌面基准字阶。
- **Label** (`500`, `12px`, 行高 `1.33`)：表头、状态底栏、辅助说明与分段控件文案（始终句首大写或自然语言，不用全大写跟踪眉标）。
- **Caption** (`400 / 500`, `11px`, 行高 `1.45`)：导航分组小标题、徽章、键帽与代码行号。
- **Code** (`400`, 默认 `13px`, 行高固定 `round(size × 1.45) = 19px`)：代码块、Diff、终端输出与行内代码（行内代码取 `0.88em`）。

### Named Rules
**The Dark Weight Compensation Rule.** 深色模式下黑底白字视觉上会发粗；支持可变字体的平台应将字重下调约 `40`（`360 / 460 / 540 / 560`），非可变字体平台须启用平滑抗锯齿。

**The Tabular Numerals Rule.** 表格数据、计数、百分比、时间戳与行号一律启用等宽数字（Tabular Numerals），保证垂直扫视对齐。

## Layout

桌面窗口采用弹性三栏壳层拓扑，可按产品信息架构无损裁剪为单栏、双栏或三栏：

- **自定义无边框标题栏（Titlebar）**：固定高度 `40px`，空白区允许拖拽窗口，所有交互控件禁止拖拽。左侧区域宽度与侧栏同步（放侧栏折叠键、前进/后退导航与贴右对齐的视图模式胶囊）；中部放当前上下文标题下拉（`13px` medium）；右侧放检查器开关、面板工具图标组，以及平台原生窗口控件（Windows/Linux 居右留 `8px` 间距排布 `38×40px` 最小化/最大化/关闭键，关闭键悬停 `#E81123` 白字；macOS 左上角预留 `76px` 红黄绿交通灯安全区）。
- **左侧导航栏（Sidebar）**：默认宽 `224px`（可拖拽调宽范围 `200–320px`，右缘预留 `4px` 隐形热区），可平滑折叠至 `0px`（`200ms`）。顶部放高频操作行（内边距 `上10px 左右8px 下6px`），中间间隔 `14–16px` 排布可滚动分组/树列表，底部可选固定 `44px` 底栏（顶部 `1px` 细线，放状态/账户入口与设置齿轮）。
- **主工作区（Main Workspace）**：支持两种排布策略——**阅读/文档流型**采用居中限宽列，提供三档栏宽（窄 `768px` 默认 / 中 `960px` / 宽 `1280px`）与左右 `32px` 安全留白，且滚动容器上下边缘叠加渐隐遮罩（顶 `32px`、底 `48px`）；**工作台/数据型**铺满可用宽度，顶部可配 `34–36px` 标签栏，分屏之间仅用 `1px` 细线分隔。
- **右侧检查器栏（Inspector Rail）**：默认宽 `220–280px`（宽屏上限 `320px`），可一键折叠至 `0px`。内部分区直接用全宽 `1px` 水平细线分隔，每区统一内边距 `上下14px 左右16px`，严禁卡片套卡片。
- **响应式与窄窗降级**：窗口 `< 960px` 时右侧检查器自动收起或转为覆盖抽屉，保证主工作区至少保留 `520px`；窗口 `< 720px` 时左侧栏转为覆盖抽屉，主区左右留白收敛至 `16–20px`。
- **间距节奏**：全局统一采用 `4 / 6 / 8 / 12 / 16 / 20 / 24 / 32 px` 步进。

### Named Rules
**The Seamless Rail Rule.** 左侧栏上方的标题栏与下方侧栏共用同一底色且**不画水平分割线**，垂直分割线自窗口顶边一路贯通到底；仅主工作区与右侧检查器上方绘制 `40px` 标题栏底边 `1px` 细线。

**The Soft Scroll Boundary Rule.** 长滚动阅读区域不得被顶栏或底部输入坞生硬横切，必须用 `32px` 顶部渐隐与 `48px` 底部渐隐让内容自然溶入画布色。

## Elevation & Depth

本体系属于**扁平优先（Flat-by-Default）+ 细线/明度分层**架构。静态区域（侧栏、工作区、检查器、静态面板、预览卡）全部零阴影，仅凭极轻微的底色明度差与 `1px` 低透明度细线界定边界；阴影严格保留给脱离文档流的浮层与可滑动指示块。

### Shadow Vocabulary
- **Active Thumb Shadow** (`box-shadow: 0 1px 2px rgba(0, 0, 0, 0.08)`)：浅色模式下分段控制器激活滑块与开关圆钮的微抬升。
- **Composer Lift** (`box-shadow: 0 1px 3px rgba(0, 0, 0, 0.03)`)：底部停靠输入坞的极微弱悬浮感。
- **Popover / Menu / Toast** (Light `box-shadow: 0 8px 24px rgba(0, 0, 0, 0.12), 0 2px 6px rgba(0, 0, 0, 0.08)`；Dark `box-shadow: 0 8px 24px rgba(0, 0, 0, 0.36), 0 2px 6px rgba(0, 0, 0, 0.22)`)：下拉菜单、右键菜单、悬浮面板与通知卡片。
- **Modal Dialog** (Light `box-shadow: 0 12px 28px -2px rgba(0, 0, 0, 0.14), 0 4px 8px rgba(0, 0, 0, 0.08)`；Dark `box-shadow: 0 12px 28px rgba(0, 0, 0, 0.48)`)：设置对话框、确认弹窗与命令面板。
- **Keyboard Focus Ring** (`box-shadow: inset 0 0 0 1px <canvas>, 0 0 0 1px #2A78D6, 0 0 6px 1px rgba(42, 120, 214, 0.12)`)：仅键盘聚焦呈现的细腻双环焦点。

### Named Rules
**The Flat-By-Default Rule.** 静止在画布上的容器一律零阴影；只有当元素脱离主层（菜单、弹窗、命令面板、Toast）或作为可滑动指示块时才允许使用阴影。

## Shapes

几何语言以**克制、连续的圆角阶梯**和**细腻统一的单色线条**为特征，避免尖锐直角与夸张胶囊混用：

- **圆角梯度**：小徽章与键帽 `4–5px` → 按钮、列表项、图标按钮与标签 `6–7px` → 输入框、下拉框与分段控外轨 `8px` → 代码块、卡片与悬浮菜单 `10px` → 停靠输入坞、命令面板与模态弹窗 `14px` → 开关轨道、进度胶囊与状态点全圆角 `9999px`。
- **嵌套圆角匹配**：容器内嵌子项时保持「外圆角 = 内圆角 + 内边距」（例如 `8px` 分段外轨 + `2px` 内边距 → `6px` 激活滑块）。
- **图标几何**：全站统一使用 `15–16px` 单色线性图标，描边 `1.5–1.6px`、圆角端点与连接（Round Cap / Join），常态随次级文本色，悬停或激活切至主文本色。
- **Diff 斜纹标识**：变更行最左侧使用 `4px` 宽 45° 细斜纹状态条（`2px` 语义色与 `2px` 行底色交替；若目标平台绘制斜纹成本高，降级为 `3px` 纯色圆角竖条）。

## Components

所有交互控件共享同一套物理触感规范：按下 `60ms` 快出微缩，松开以柔和弹簧（等效物理参数 `stiffness ≈ 320, damping ≈ 20`、`450ms`）回弹；所有面板显隐与滑块位移使用 `120–200ms` 的 `cubic-bezier(0.32, 0.72, 0, 1)` 曲线，并尊重系统的减少动态效果设置。

### Buttons
- **Character:** 轻盈克制但具备清晰物理确认感。
- **Shape:** 温和圆角（`6px` 默认 / `7px` 中号），桌面默认高度 `28–30px`（小号 `24px`、大号 `36px`），图标按钮为 `28×28px` 正方形。
- **Primary:** 墨色实底（浅 `#191919` 白字 / 深 `#EFEFEF` `#191919` 字），水平内边距 `10–12px`。
- **Secondary / Ghost / Danger:** Secondary 采用 `5%` 浅灰底配 `1px` 细边（深色 `13%` 白底无边）；Ghost 常态完全透明，悬停出现 `ghost-hover`，激活保持 `ghost-selected`；不可逆删除用实心 Danger 红，温和危险提示用柔和红浅底配危险红文字。
- **Hover / Active / Focus:** 按下 `60ms` 内缩至 `scale(0.975)`，松开弹簧回弹；禁用态统一 `40%` 透明度且取消缩放。

### Segmented Controls & Tabs
- **Character:** 清晰轻量，不喧哗的互斥切换器。
- **SegmentedControl:** `2px` 内边距的 `8px` 圆角浅底轨，内部选项高 `24–26px`、圆角 `6px`；浅色激活块为纯白带 `Active Thumb Shadow`，深色激活块为 `13%` 透明白底。
- **Workspace Tabs:** 高度 `34–36px`、底边 `1px` 细线；激活标签用 `ghost-selected` 圆角胶囊底或底部 `2px` 主色细线，关闭 `×` 仅在当前激活或悬停该标签时显示。

### Inputs / Fields & Toggles
- **Character:** 边框轻描、聚焦清晰、嵌套零冲突。
- **TextInput / Select:** 高 `32px`、圆角 `8px`、水平内边距 `10px`、`1px` `border-control` 细边（浅色纯白底 / 深色 `4%` 白底）。
- **Inline Ghost Select:** 用于设置行或标题栏的轻量下拉——常态无边框无底色，仅文字加右侧 `13–14px` 下拉箭头，悬停出现 `ghost-hover` 胶囊底。
- **Focus & Embedded Rule:** 独立输入框仅在键盘聚焦时呈现 `Keyboard Focus Ring`；**嵌套在复合容器内的无边框输入**（命令面板搜索栏、停靠输入坞文本域、搜索盒内部输入框）必须抑制自身焦点环，由外层容器边框或弹窗自身承担聚焦视觉反馈。
- **Error / Disabled:** 错误态切换边框为 `status-danger`，下方 `4px` 处用 `12px` 危险红直述原因与改法。
- **Switch & Checkbox:** Switch 为 `34×20px` 全圆角胶囊（内边距 `2px`、纯白 `16px` 圆钮，`180ms` 滑动，开启态切换 `#2A78D6`）；Checkbox 为 `16×16px`、`4px` 圆角，选中填 `#2A78D6` 或 `#191919` 配白勾。

### Navigation, Lists & Trees
- **Character:** 呼吸感均匀、无多余横线的安静列表。
- **Style:** 行高 `28–30px`、圆角 `7px`、行间距 `2px`；树形子级每层缩进 `14–16px`，展开箭头 `11–12px` 静音色并旋转 `90°`（`120ms`）。
- **States:** 悬停 `ghost-hover`，激活 `ghost-selected` 加 `500` 字重；单行过长省略截断，行尾操作菜单（`···`）默认隐藏、悬停显现。
- **Badges & Meters:** 语义徽章高 `18–20px`、圆角 `5px`、`11px` medium 低饱和浅底配语义字；单字母集成方标为 `20×20px` 圆角 `5px` 淡底块居中次级色字母；紧凑进度胶囊高 `6px`（或 `14×14px` 细环），按占比切换中性/琥珀/红色。

### Tables & DataTables
- **Character:** 极简扁平、竖向留白宽松、数值对齐工整。
- **Flat Display Table（无行选中高亮）:** 无外框、无竖线、无斑马纹，仅保留表头与各行底部 `1px` `border-subtle` 水平细线；单元格 `上下10px 左右12px`，首列左内边距 `0`、末列右内边距 `0` 与正文齐平。
- **Interactive DataTable（支持排序/多选）:** 粘性表头与画布同底，表头 `12px` 次级色 `500` 字重；因存在行悬停与选中底色，**首尾列须保留 `10–12px` 水平内边距**避免贴边切字；次要/停用行文本降至 `50%` 透明度但行内按钮保持正常清晰度。

### Cards, Overlays & Settings Modal
- **Cards / Panels:** 圆角 `10px`、`1px` 细边、零阴影；可点击卡片悬停由 `3.5%` 淡底加深至 `6%`，按下微缩至 `0.99`。
- **Popover / ContextMenu / Tooltip / Toast:** 浮层统一 `10px` 圆角、`4px` 内边距、`1px` 细边加 `Popover Shadow`，菜单项高 `28–30px`、快捷键右对齐静音键帽；Tooltip 浅色深墨底白字（`#0B0B0B` / `#FFFFFF`）、深色亮浮层底（`#303030` + `1px` 细边）；Toast 悬浮右下角，左侧 `15px` 语义图标配简洁动词陈述，不铺大面积彩条。
- **Command Palette (`Ctrl/Cmd + K`):** 顶居中悬浮，宽 `min(560px, 86vw)`、圆角 `14px`、`Modal Shadow`，顶部 `44px` 无边框搜索输入下接 `34px` 行高分组结果。
- **Dual-Column Settings Modal:** 宽 `min(860px, 86vw)`、高 `min(630px, 86vh)`、圆角 `14px`。顶栏 `48px`（左标题右关闭 `×`）；左栏宽 `196–200px` 含顶部 `30px` 实时搜索框与带 `11px` 静音分组标题的图标导航；右栏内边距 `上下20px 左右28px`，设置行采用「左：标题 `13px` medium + 描述 `12.5px` 次级色 / 右：精准对齐的控件」，区距 `24px`。

### Signature Patterns（按功能需要选用）
- **Docked Composer & Metadata Chin:** 底部停靠输入卡为 `14px` 圆角、`1px` 细边加 `Composer Lift`，左置 `+` 附加键、中为自适应多行输入、有内容时右现 `28×28px` 墨色提交键，输入触发符（如 `/`、`@`）紧贴卡片上方弹出命令菜单；正下方紧贴 `28–30px` 轻量 `12px` 底栏承载当前上下文切换与环形指标。
- **Code & Diff Preview Card:** `10px` 圆角、`1px` 细边，左侧 `4px` 斜纹状态条 + 右对齐 `28px` 静音行号 + 淡红/淡绿柔底代码行，支持双列浅/深主题实时预览。
- **Collapsible Trace:** 折叠态单行 `12.5px` 静音摘要，展开态以左侧 `1px` 细竖导轨缩进展示步骤详情，不套多层方框。
- **TextLink & Loading:** 链接下划线偏移 `3px`，常态为当前文字色 `40%` 透明度、悬停 `60ms` 渐深至 `100%`；骨架屏以 `2s` 在 `100% ↔ 60%` 柔和呼吸（多行错峰 `90ms`），后台进行中状态文字可叠 `3s` 120° 柔和流光。

## Do's and Don'ts

### Do:
- **Do** 保持侧栏顶栏与下方侧栏底色一致且无水平分割线，让垂直分割线直达窗口顶边。
- **Do** 在浅色模式下以 `#FFFFFF` / `#FAFAFA` + `rgba(0,0,0,0.08)` 细线构建层次，在深色模式下用 `#191919` → `#1F1F1F` → `#303030` 阶梯表达纵深。
- **Do** 让按钮按压具备 `scale(0.975)` 微缩反馈与柔和弹簧回弹，并在 `prefers-reduced-motion` 开启时关闭位移动效。
- **Do** 区分纯展示扁平表格（首列 `0` 左距对齐正文）与交互式 DataTable（首尾列保留 `10–12px` 内边距防止选中底色贴字）。
- **Do** 对嵌套在命令面板、输入坞或搜索框内的无边框输入抑制内部焦点环，由外层容器承接聚焦态。
- **Do** 所有表格数字、计数、百分比、时间戳与代码行号启用等宽数字（Tabular Numerals）。

### Don't:
- **Don't** 给静止在画布上的卡片、检查器分区或侧栏叠加明显投影，也不要在检查器里用卡片套卡片。
- **Don't** 把品牌陶土橙 `#D97757` 用作大面积主按钮背景、顶栏底色或导航选中填充。
- **Don't** 在表格中绘制外边框、竖向网格线或斑马纹背景。
- **Don't** 在面板或设置分区上方添加全大写、宽字距的装饰性眉标（ALL-CAPS eyebrow）或多余次要说明标签。
- **Don't** 把本体系与特定前端框架绑定（如在设计规范里写死某套工具类名），也不要向无关产品强行塞入聊天或 AI 业务模块。
