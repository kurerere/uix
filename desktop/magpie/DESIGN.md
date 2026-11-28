---
name: "Magpie Desktop"
description: "静谧克制的单表面桌面控制台设计体系（The Quiet Control Deck），以真实品牌图标、定列对齐的弹出式按钮控件、可变形顶栏/侧栏壳层与高对比无障碍色阶为核心。"
colors:
  accent-indigo-light: "#4F46E5"
  accent-indigo-soft-light: "#EEEDFD"
  accent-indigo-fg-light: "#FFFFFF"
  accent-sel-light: "#ECEBFB"
  accent-indigo-dark: "#A5B4FC"
  accent-indigo-soft-dark: "#2B2C47"
  accent-indigo-fg-dark: "#14142A"
  accent-sel-dark: "#33345A"
  status-green-light: "#189A58"
  status-green-soft-light: "#E4F6EC"
  status-green-dark: "#6FD99B"
  status-green-soft-dark: "#1E3A2B"
  status-red-light: "#D64545"
  status-red-soft-light: "#FBE9E9"
  status-red-dark: "#F28B82"
  status-red-soft-dark: "#45272A"
  status-confirm-danger-light: "#C73535"
  status-amber-light: "#B45309"
  status-amber-soft-light: "#FBF0DF"
  status-amber-dark: "#F2B544"
  status-amber-soft-dark: "#3F3220"
  status-drift-light: "#CE2C31"
  status-drift-soft-light: "#FEEBEC"
  status-drift-dark: "#FF9592"
  status-drift-soft-dark: "#3B1219"
  bg-light: "#F4F4F6"
  card-light: "#FFFFFF"
  card-inset-light: "#F9F9FB"
  pill-light: "#F1F1F4"
  pill-hover-light: "#E9E9EE"
  seg-track-light: "#E6E6EB"
  line-light: "#E3E3E8"
  line-subtle-light: "#ECECF0"
  fg-light: "#1C1C21"
  fg-secondary-light: "#4B4B53"
  ctl-fg-light: "#63636B"
  muted-light: "#85858D"
  faint-light: "#B9B9C2"
  pop-bg-light: "rgba(255, 255, 255, 0.94)"
  scrim-light: "rgba(0, 0, 0, 0.28)"
  bg-dark: "#1A1A1E"
  card-dark: "#232327"
  card-inset-dark: "#1F1F23"
  pill-dark: "#2D2D33"
  pill-hover-dark: "#36363D"
  seg-track-dark: "rgba(255, 255, 255, 0.035)"
  seg-thumb-dark: "rgba(255, 255, 255, 0.15)"
  line-dark: "#333339"
  line-subtle-dark: "#2C2C32"
  fg-dark: "#EDEDF1"
  fg-secondary-dark: "#B9B9C1"
  ctl-fg-dark: "#A1A1AA"
  muted-dark: "#9C9CA6"
  faint-dark: "#90909A"
  pop-bg-dark: "rgba(38, 38, 43, 0.96)"
  scrim-dark: "rgba(0, 0, 0, 0.32)"
typography:
  kpi:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 600
    lineHeight: 1.35
    letterSpacing: "0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0em"
  control:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "12.5px"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0em"
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0em"
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "11px"
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: "0.04em"
  micro:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Segoe UI Variable Text, Segoe UI, Microsoft YaHei UI, system-ui, sans-serif"
    fontSize: "9.5px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.04em"
  code:
    fontFamily: "ui-monospace, SF Mono, Cascadia Mono, Menlo, Consolas, Microsoft YaHei UI, monospace"
    fontSize: "11.5px"
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: "0em"
rounded:
  2xs: "2px"
  xs: "4px"
  badge: "5px"
  sm: "6px"
  md: "7px"
  lg: "8px"
  xl: "10px"
  popover: "11px"
  2xl: "12px"
  modal: "14px"
  full: "999px"
spacing:
  2xs: "2px"
  xs: "4px"
  sm: "6px"
  md: "8px"
  lg: "10px"
  xl: "12px"
  2xl: "14px"
  3xl: "16px"
  4xl: "18px"
components:
  button-primary:
    backgroundColor: "{colors.accent-indigo-light}"
    textColor: "{colors.accent-indigo-fg-light}"
    typography: "{typography.control}"
    rounded: "{rounded.sm}"
    padding: "3px 7px"
  button-action:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-secondary-light}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "0 10px"
    height: "27px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ctl-fg-light}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "3px 7px"
  button-icon:
    backgroundColor: "transparent"
    textColor: "{colors.muted-light}"
    rounded: "{rounded.md}"
    width: "26px"
    height: "26px"
  popup-field:
    backgroundColor: "{colors.pill-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.control}"
    rounded: "{rounded.sm}"
    padding: "0 5px 0 8px"
    height: "25px"
  popup-field-hover:
    backgroundColor: "{colors.pill-hover-light}"
    textColor: "{colors.fg-light}"
  list-card:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    rounded: "{rounded.2xl}"
  list-row:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.body}"
    padding: "7px 12px 7px 14px"
    height: "48px"
  sidebar-item-active:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: "0 8px"
    height: "30px"
  segmented-track:
    backgroundColor: "{colors.pill-light}"
    rounded: "{rounded.md}"
    padding: "2px"
  segmented-thumb:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.label}"
    rounded: "{rounded.badge}"
    padding: "0 10px"
    height: "22px"
  input-field:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.control}"
    rounded: "{rounded.md}"
    padding: "0 9px"
    height: "27px"
  popover-picker:
    backgroundColor: "{colors.pop-bg-light}"
    textColor: "{colors.fg-light}"
    rounded: "{rounded.popover}"
    width: "320px"
  modal-dialog:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    rounded: "{rounded.modal}"
    width: "600px"
  status-toast:
    backgroundColor: "{colors.card-light}"
    textColor: "{colors.fg-light}"
    typography: "{typography.control}"
    rounded: "{rounded.popover}"
    padding: "3px 10px"
  badge-pill:
    backgroundColor: "{colors.pill-light}"
    textColor: "{colors.muted-light}"
    typography: "{typography.micro}"
    rounded: "{rounded.xs}"
    padding: "1px 5px"
---

# Design System: Magpie Desktop

## Overview

**Creative North Star: "The Quiet Control Deck"**

Magpie Desktop 是一套围绕 **“单一静谧底面、真实品牌标识、如弹出按钮般利落的控件”**（One quiet surface, real logos, controls that read as pop-up buttons）构建的 **Operate** 型原生桌面控制台设计体系。它不靠繁复的装饰性卡片套叠或高饱和度色块争夺注意力，而是将高密度的配置项、实时用量指标、路由策略与多端状态压缩在冷调中性灰画布上的整齐列表之中，让用户在连续调试与切换任务时始终拥有一目了然的秩序感。

本体系原生覆盖三大形态并保持视觉基因统一：无边框主桌面窗口（`Main Window`，可在顶部居中分段标签与左侧可调宽边栏之间整屏变形切换）、轻量毛玻璃托盘浮窗（`Tray Panel`，在紧凑空间内以 `36px` 行高与点击原地展开维持高效率）、以及自适应响应式网页端（`Responsive Web`，在窄屏自动演化为 `50.5px` 底部磨砂导航栏）。所有色彩、字阶、布局网格、动效曲线与无障碍规则均与具体 UI 框架完全解耦，可无损迁移至 Web、Electron、Wails、Tauri、Qt 或原生桌面技术栈。

**Key Characteristics:**
- **静谧冷灰单底面与实色品牌锚点**：主画布采用微冷中性灰（浅色 `#F4F4F6` / 深色 `#1A1A1E`）托起纯白或深炭卡片，所有识别度交由真实的多色/单色品牌图标承担，文字与选中态默认保持石墨黑灰克制。
- **定列对齐的弹出式控件**：列表行右侧的设置控件统一使用等宽双栏或三栏网格锁定垂直对齐线，使整列下拉箭头在视觉上形成一条笔直的扫描通道。
- **物理隐喻与零抖动布局**：保留滚动条占位沟槽杜绝折叠展开引起的页面横跳；子列表采用卷轴式渐隐展开；侧栏文字与图标配备随鼠标移动的 `oklab` 手电筒微光反馈。
- **全场景无障碍工程纪律**：内建 WCAG 4.5:1 控件文本底线、独立的高对比度色板覆盖、失败态形状与颜色双重编码（以 `×` 替代单一红点），以及对色觉障碍友好的 Okabe–Ito 图表色系。

## Colors

色板以极低饱和度的冷调中性灰（Cool-Neutral Gray）构成背景与卡片层级，用**靛蓝（Indigo）**作为默认系统强调色，并支持用户切换 6 套预设强调色或自定义取色器色彩。

### Primary
- **Magpie Indigo**（浅色 `#4F46E5`，柔底 `#EEEDFD`，反白字 `#FFFFFF`，选中行底 `#ECEBFB`；深色 `#A5B4FC`，柔底 `#2B2C47`，深色字 `#14142A`，选中行底 `#33345A`）：核心主操作按钮、键盘焦点轮廓、开关/激活指示点、进度条填充及未定色态下的默认强调色。
- **可选用户预设强调色（Appearance Accent Presets）**：支持在保留全部中性灰结构的前提下，将主强调色无缝替换为 Blue (`#2563EB`)、Teal (`#0D9488`)、Green (`#16A34A`)、Orange (`#EA580C`)、Pink (`#DB2777`) 或 Graphite (`#52525B`)，系统自动推导出对应的柔底色、反白前景色与列表选中底色。

### Secondary
- **Graphite Selection**（默认 `--mark` 取主文本色 `#1C1C21` / `#EDEDF1`，滑块填充色由面板/卡片自身承载）：桌面导航当前项图标与分段控制器选中文字的默认着色方案，模仿原生桌面边栏的石墨质感；仅当用户主动指定个性化强调色时，才将导航激活文字与标识转为对应强调色。

### Tertiary
- **Status Green**（浅色 `#189A58` / 柔底 `#E4F6EC`；深色 `#6FD99B` / 柔底 `#1E3A2B`）：连接成功、网关运行中、免费额度标签与命令行配置就绪指示。
- **Status Red & Confirm Danger**（浅色 `#D64545` / 柔底 `#FBE9E9`；深色 `#F28B82` / 柔底 `#45272A`；不可逆删除确认弹窗实心按钮浅色 `#C73535`）：错误提示、校验失败边框、拦截状态与高危删除动作。
- **Status Amber**（浅色 `#B45309` / 柔底 `#FBF0DF`；深色 `#F2B544` / 柔底 `#3F3220`）：额度超速预警、桌面端需重启提示、弃用警告徽章与收藏星标激活色。
- **Config Drift Coral**（浅色 `#CE2C31` / 柔底 `#FEEBEC`；深色 `#FF9592` / 柔底 `#3B1219`）：专用配置漂移状态色，用于标识外部工具配置被改写而脱离托管的行内修复胶囊与托盘角标。
- **Data Visualization Series（默认 7 色序列 & Okabe–Ito 色盲安全序列）**：
  - **默认图表色**：浅色 `#4F46E5` · `#0EA5E9` · `#10B981` · `#F59E0B` · `#EC4899` · `#8B5CF6` · `#64748B`；深色 `#A5B4FC` · `#7DD3FC` · `#6EE7B7` · `#FCD34D` · `#F9A8D4` · `#C4B5FD` · `#94A3B8`。
  - **Okabe–Ito 色觉障碍安全序列**：浅色 `#0072B2` · `#E69F00` · `#009E73` · `#D55E00` · `#CC79A7` · `#56B4E9` · `#64748B`；深色 `#56B4E9` · `#FBBF24` · `#2DD4BF` · `#FB7185` · `#E879F9` · `#F0E442` · `#94A3B8`，配合差异化虚线样式区分相邻数据线。
- **Syntax Tokens（代码/JSON 预览色）**：
  - 浅色：字符串 `#1A7F45`、关键字 `#7C3AED`、函数 `#1D4ED8`、数字 `#B45309`、变量 `#0E7490`、操作符 `#A21CAF`、注释 `#85858D`。
  - 深色：字符串 `#98D8A4`、关键字 `#C4B5FD`、函数 `#93C5FD`、数字 `#F2B544`、变量 `#67E8F9`、操作符 `#F0ABFC`、注释 `#8B8B94`。

### Neutral
- **Main Window Surfaces**：浅色画布 `#F4F4F6`、主卡片 `#FFFFFF`、展开内嵌编辑区 `#F9F9FB`、胶囊控件 `#F1F1F4`（悬停 `#E9E9EE`）、顶栏轨道 `#E6E6EB`、实线边框 `#E3E3E8`、行内分割细线 `#ECECF0`；深色画布 `#1A1A1E`、主卡片 `#232327`、展开内嵌区 `#1F1F23`、胶囊控件 `#2D2D33`（悬停 `#36363D`）、顶栏微透明轨道 `rgba(255, 255, 255, 0.035)`、滑块 `rgba(255, 255, 255, 0.15)`、边框 `#333339`、行内细线 `#2C2C32`。
- **Tray Panel Frosted Surfaces**：浅色背景 `#F2F2F5`（叠 `93%` 混色透底）、纯白卡片 `#FFFFFF`、`rgba(0, 0, 0, 0.07)` 细线；深色背景 `#1B1C20`、卡片 `#25262C`、内嵌区 `#212227`、胶囊 `#2E2F36`（悬停 `#383942`）、`rgba(255, 255, 255, 0.07)` 细线。
- **Text Hierarchy**：浅色主文 `#1C1C21` / 次文 `#4B4B53` / 控件静默文本 `#63636B` / 弱提示 `#85858D` / 极淡辅助 `#B9B9C2`；深色主文 `#EDEDF1` / 次文 `#B9B9C1` / 控件文本 `#A1A1AA` / 弱提示 `#9C9CA6` / 极淡 `#90909A`。
- **High-Contrast Mode（系统或偏好开启“增强对比度”时生效）**：浅色强制提深文本至 `#111114 / #3A3A41 / #55555D / #5E5E66`、控件文本 `#4A4A52`、外框 `#84848E`（保证 ≥ 3.3:1 边框对比度）与内线 `#BDBDC6`；深色提亮文本至 `#F4F4F7 / #D2D2D8 / #BDBDC5 / #B4B4BC`、控件文本 `#C0C0C8`、外框 `#77777F`、内线 `#4E4E56`，焦点外环加粗至 `3px`。

### Named Rules
**The Graphite Selection Rule.** 在默认未设定个性化强调色时，侧边栏当前项与分段开关的选中态保持中性石墨墨色（`#1C1C21` / `#EDEDF1`）配卡片实体底色，避免大片高饱和彩色在高频切换控件中制造视觉疲劳。

**The Shape-Over-Color Failure Rule.** 任何失败、离线或异常状态不得仅靠红绿圆点色差表达；失败指示器必须叠加 `×` 几何切形（`stroke-width: 2.4px`），确保在灰度显示或红绿色弱视角下依然瞬间可辨。

**The Contrast-Floor Text Rule.** 浅色模式下的标准弱提示灰（`#85858D`）在纯白卡片上仅约 `3.7:1`，因此凡是落在卡片内、按钮内或图表说明中的静默操作文字，必须抬升至控件专用灰（`#63636B`），保证全场景对比度严格达到 `4.5:1` 以上。

## Typography

**Display & Body Font:** 跨平台系统原生无衬线栈——macOS 与 Linux 采用 `-apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", system-ui, sans-serif`；Windows 平台显式切换为 `"Segoe UI Variable Text", "Segoe UI", "Microsoft YaHei UI", "Microsoft YaHei", system-ui, sans-serif`，确保中文界面优先命中清晰的微软雅黑 UI 而非浏览器旧式回退字体。
**Mono Font:** 通用平台采用 `ui-monospace, "SF Mono", Menlo, Consolas, monospace`；Windows 平台显式指定 `"Cascadia Mono", Consolas, "Microsoft YaHei UI", "Microsoft YaHei", monospace`。

**Character:** 整体采用高密度、紧凑行高的桌面控制台排版（默认正文 `13px / 1.4`），极少使用超过 `20px` 的装饰性巨型标题，依靠精细的半级字号阶梯（`10.5 / 11 / 11.5 / 12 / 12.5 / 13 / 13.5 / 16 / 20px`）与克制的字重对比（`400 / 500 / 600`）划分阅读主次。

### Hierarchy
- **KPI Figure** (`600`, `20px`, 行高 `1.15`, 字距 `-0.01em`)：顶部统计磁贴的核心汇总数字，内嵌单位符号降至 `13px / 500` 弱提示色。
- **Headline** (`600`, `16px`, 行高 `1.3`, 字距 `-0.01em`)：独立确认弹窗与空状态主标题。
- **Title** (`600`, `13.5px`, 行高 `1.35`, 字距 `0.01em`)：顶部应用品牌字标、面包屑末级标题与主要卡片组头。
- **Body** (`400 / 500`, `13px`, 行高 `1.4`)：列表行主名称（`500`）、侧边栏一级导航、搜索框输入与弹窗说明正文。
- **Control** (`500`, `12.5px`, 行高 `1.4`)：弹出式字段芯片当前值、主导航顶部标签、弹出菜单项、浮动状态胶囊与表单输入框文字。
- **Label** (`400 / 500`, `12px`, 行高 `1.4`)：普通文本按钮、表单右对齐标签、分段选项文案与表格单元格。
- **Caption** (`500`, `11px`, 行高 `1.35`, 字距 `0.04em`)：侧边栏分组小标题、数据表头、快捷键键帽、行内副标题（`11.5px`）及单图例标注；在 KPI 卡片或分组标题中采用全大写配 `0.05em` 字距。
- **Micro Badge** (`600`, `9.5px`, 行高 `1.4`, 字距 `0.04em`)：极小尺寸的状态微标（`FREE`、`DIRECT`、协议或上下文容量微章）。
- **Code** (`400`, `11.5px`, 行高 `1.45`)：JSON 配置编辑框、命令行安装命令片段与配置对比差异视图。

### Named Rules
**The Platform-Native CJK Stack Rule.** 在 Windows 桌面 WebView 环境下，必须为无衬线与等宽字体栈同时注入 `Microsoft YaHei UI` 回退，严禁依赖浏览器默认通用 `monospace`——在中文 Windows 下通用等宽字会回落到 `11px` 下发虚断裂的点阵宋体（SimSun）。

**The Tabular Metrics Rule.** 一切列表数值、版本号、余额、端口地址、倒计时、配额占比与代码行号必须开启等宽数字（Tabular Numerals），保证垂直对齐与动态刷新时不产生横向晃动。

## Layout

桌面壳层围绕**“一窗双态变形拓扑”**（Top Tabs ↔ Collapsible Sidebar）与**“防抖动居中内容容器”**构建，同时向下兼容系统托盘浮窗与移动端 Web 视图：

- **无边框标题栏（Frameless Titlebar）**：主窗口顶栏基准高 `46px`（macOS 下按 `50px / zoom` 缩放并在左侧预留 `96px` 交通灯安全区；Windows 下右侧预留 `146px` 给三个 `46px` 宽原生样式窗口控制键，关闭按钮悬停呈现 `#C42B1C` 纯红白字；Linux 下在图标组末端放置 `22px` 圆形胶囊关闭按钮）。顶栏空白区域支持拖拽窗口，所有交互按钮禁拖。
- **双态变形导航（Top Segmented Tabs ↔ Sidebar）**：
  - **顶栏标签态**：顶栏绝对居中放置无灰底轨道的分段导航胶囊，仅当前激活项显示白色/半透明浮起滑块。窗口宽度收窄时，顶栏按优先级渐进退让：先隐藏搜索图标，再折叠品牌文字仅留鸟形徽标、更新胶囊收拢为箭头图标，继而将标签从绝对居中切换为流式居中并依次收缩选项内边距（`12px → 8px → 6px → 3px`），直至允许标签条横向静默滚动。
  - **左侧边栏态**：桌面端默认宽 `212px`（视口 `≤ 859px` 时收敛为 `184px`），右缘设 `8px` 隐形拖拽调宽热区（触摸屏扩至 `24px`），右边界为 `0.5px` 垂直细线。侧栏顶部与主窗口顶栏等高（`46px` / macOS `50px`），放置与主窗口位置完全一致的侧栏折叠键与徽标；中部按分组标题（`11px`）排列 `30px` 行高的导航项，当前激活页面下方通过左缩进 `16px` 带 `1px` 垂直导轨的子列表直接展开其内部标签页（`26px` 行高）；底部固定区采用 `column-reverse` 布局（最大占比 `55%`，展开子列表时扩至 `80%`），由下往上依次锚定网关状态行、设置按钮及其向上展开的子标签。侧栏激活时，主视图顶部工具条固定悬浮到顶栏右侧空白区，使标题栏成为共享操作带。
- **主工作区与滚动安全（Main Workspace）**：主内容区在宽屏窗口下自动居中限宽至 `1200px`（左右内边距取 `max(16px, calc(50% - 600px))`），防止超大显示器把名称与右侧控件拉成两极。主滚动区强制常驻垂直滚动槽并将滚动条宽度计入右侧安全内边距减去项（`padding-right - var(--bar)`），彻底消除展开折叠面板时页面内容向左跳动 `8px` 的闪烁；非 macOS 平台将滚动条样式统一为 `10px` 透明轨道内嵌 `3px` 留白的细圆角拇指。
- **双栏弹窗与托盘紧凑布局**：主窗口行最小高 `48px`（内边距 `上下7px 右12px 左14px`、列距 `12px`）；托盘浮窗（`Tray Panel`）行高收紧至 `36px`（内边距 `0 12px`、列距 `10px`），页脚保留 `28px` 紧凑栏用于放置“打开主窗口”、“退出”与状态结果。视口 `≤ 600px` 时，列表行自动切换为「图标+名称在第一行 / 定宽控件列满宽折行至第二行」；移动端 Web（`≤ 760px` 或触屏 `≤ 1024px`）将主导航移至底部 `50.5px` + 安全区高度的磨砂底栏，最多平铺 5 个带 `23px` 图标的入口（超出收纳入“更多”弹出菜单）。
- **间距步进**：全局遵循 `2 / 4 / 6 / 8 / 10 / 12 / 14 / 16 / 18 px` 精密步进，卡片间距 `8–12px`，表单网格行距 `10px`、列距 `14px`。

### Named Rules
**The Fixed-Column Pop-up Grid Rule.** 在代理或规则列表行中，右侧的弹出式选择器组必须锁定固定列宽（主窗口 `350px`，分为 `minmax(0, 1fr)` 与 `124px` 两列；托盘浮窗 `272px`，分为 `minmax(0, 1fr)` 与 `118px` 两列；附加方格开关再按 `29px` 步进追加第三列），确保整张列表中所有下拉箭头永远对齐在同一条垂直线上。

**The Zero-Reflow Scrollbar Gutter Rule.** 所有可滚动页面与模态框表单正文必须始终保留滚动条轨道空间，并将实测滚动条宽度从右内边距中扣除；禁止在内容高度跨越视口临界点时动态增删滚动条导致网格列宽重排。

**The Morphing Shell Rule.** 从顶栏标签切换到侧边栏布局不是两套孤立界面，而是一次由 `View Transitions` 驱动的连续形变（`320ms`，`cubic-bezier(0.77, 0, 0.175, 1)`）：侧栏整体滑入/滑出，每个页面导航标签飞越到目标位置，图标与品牌同步对齐，避免生硬切屏。

## Elevation & Depth

本体系属于**细线界定为主、半透明磨砂浮层为辅**的浅浮层级架构。主画布上的列表容器与统计卡片在常规桌面模式下零投影，仅通过 `1px` 实线边框与极微弱的底色差（`#F4F4F6` 画布 vs `#FFFFFF` 卡片 / `#1A1A1E` 画布 vs `#232327` 卡片）建立秩序；阴影仅用于提示“可被点按的立体控件（托盘浮窗内）”与“脱离文档流飘浮的浮层”。

### Shadow Vocabulary
- **Active Thumb Edge**：浅色 `box-shadow: 0 1px 2px rgba(0, 0, 0, 0.14), 0 0 0 0.5px rgba(0, 0, 0, 0.08)`；深色 `box-shadow: inset 0 0.5px 0 rgba(255, 255, 255, 0.08), 0 1px 2px rgba(0, 0, 0, 0.30)`——用于顶栏分段滑块、分段开关滑块与侧边栏激活项的微弱实体凸起。
- **Panel Card & Pill Edge**：浅色卡片 `0 0 0 1px rgba(0, 0, 0, 0.05), 0 1px 2px rgba(0, 0, 0, 0.04)`、胶囊控件 `inset 0 0 0 1px rgba(0, 0, 0, 0.12), 0 1px 1px rgba(0, 0, 0, 0.06)`；深色卡片 `inset 0 0 0 1px rgba(255, 255, 255, 0.06)`、胶囊控件 `inset 0 0 0 1px rgba(255, 255, 255, 0.11), 0 1px 2px rgba(0, 0, 0, 0.28)`——专用于磨砂托盘浮窗，让按钮真正像原生弹出按钮（Pop-up Button）一样浮出底面。
- **Drag-Sort Lift** (`box-shadow: 0 6px 18px rgba(20, 22, 30, 0.12), 0 0 0 1px <line>`)：列表行或插件导航项被拖拽排序时的离地悬浮影。
- **Floating Toast & Scroll Capsule**：浮动状态胶囊 `inset 0 0 0 1px color-mix(in srgb, currentColor 30%, transparent), 0 6px 20px rgba(0, 0, 0, 0.28)`；右下角直达顶/底悬浮胶囊 `0 4px 14px rgba(20, 22, 30, 0.12), 0 0 0 0.5px <line-subtle>` 配 `20px` 背景模糊。
- **Frosted Popover** (`background: rgba(255, 255, 255, 0.94)` / `rgba(38, 38, 43, 0.96)`，`backdrop-filter: blur(24px)`；浅色 `0 16px 44px rgba(20, 22, 30, 0.16), 0 2px 8px rgba(20, 22, 30, 0.06), 0 0 0 0.5px rgba(20, 22, 30, 0.10)`；深色 `0 16px 44px rgba(0, 0, 0, 0.55), 0 2px 8px rgba(0, 0, 0, 0.30), 0 0 0 0.5px rgba(255, 255, 255, 0.10)`)：下拉选择器、模型挑选器与右键菜单。
- **Modal Dialog** (`box-shadow: 0 0 0 1px <line>, 0 24px 60px rgba(0, 0, 0, 0.32), 0 2px 8px rgba(0, 0, 0, 0.12)`)：居中表单弹窗与二次确认框；非 Windows 桌面端背景遮罩叠 `blur(8px) saturate(1.1)` 磨砂暗幕。
- **Keyboard Focus & Input Glow**：按钮与控件键盘聚焦呈现 `2px` 实线外轮廓（`outline-offset: 1px`，高对比度模式增至 `3px`）；文本输入框聚焦呈现 `1px` 强调色边框加 `0 0 0 3px` 柔和外晕（`22%` 强调色）。

### Named Rules
**The Hairline-First Surface Rule.** 主窗口中的静态列表卡片、图表容器与统计组均不得添加大面积扩散投影，必须用 `1px` 低对比度边框与清晰的背景明度差划定领地；`0.5px` 半像素外环仅保留给漂浮指示块与浮层边缘。

**The Backdrop-Safe Scrim Rule.** 全屏模态框背景暗幕虽然在 macOS 与 Web 端使用 `8px` 毛玻璃模糊增强景深，但在 Windows 桌面 WebView 环境下必须强制关闭全屏 `backdrop-filter`，仅保留半透明遮罩色，以防止部分 GPU 驱动在弹窗测试与登录回调时发生渲染卡死。

## Shapes

几何形态遵循**细腻渐进的微圆角体系**与**极简光学图标对齐规则**，整体气质类似原生桌面工具软件的克制精密感：

- **连续圆角阶梯**：滚动滑块与进度条轨道 `2px` → 极小徽章与键帽 `4px` → 分段子滑块、代码片段与骨架屏 `5px` → 弹出按钮芯片、侧栏子项、标签与文本按钮 `6px` → 列表项、输入文本框、图标按钮、分段外轨与托盘标签滑块 `7px` → 嵌套子卡、选择器导轨块与拖拽高亮行 `8px` → 常规设置卡片与安装命令卡 `10px` → 弹出选择面板与底部浮动提示胶囊 `11px` → 主列表卡片与统计组外框 `12px` → 模态对话框与确认弹窗 `14px` → 开关圆钮、更新胶囊、状态指示点与叠放图标圆盘 `999px / 50%`。
- **嵌套圆角同心**：外层容器与内部滑块严格匹配同心差值（例如 `7px` 圆角分段轨配 `2px` 内边距，内部滑块取 `5px`；托盘内卡片从主窗口 `12px` 同步收紧为 `10px`）。
- **图标几何与光学补偿**：
  - 全站功能图标统一使用 `14–16px` 线性矢量，描边 `1.5–2px`，圆角端点与圆角拐点（Round Cap / Round Join）。
  - **实心铺满型品牌图标 `82%` 光学缩尺**：对于铺满整个方框或圆盘的实心块状第三方品牌图标，必须将其绘制尺寸缩小至图标盒的 `82%`，使其在视觉重量上与旁边的线条型图标保持绝对一致。
  - **重叠图标圆盘栈**：路由组或聚合项展示多个服务商时，采用 `20px`（行内弹出控件中为 `17px`）纯白/深炭圆盘叠放，`1px` 边框描边，后一个圆盘向左负边距 `-4px` 压叠并依次递减层级，内部图标固定 `13px` / `11px`。
  - **隐形左边界拖拽点阵**：可拖拽排序的列表行左侧仅在鼠标悬停、拖拽中或键盘聚焦时，于图标外侧左缘浮现 `2×3` 颗 `0.9px` 静音微点（`6×11px`），常态完全隐藏，杜绝“常驻抓手”造成的视觉噪音。
- **平铺零圆角变体（可选的平铺窗口壳层模式）**：支持一键切换至平铺窗口管理器适配态（如 Omarchy / Hyprland 风格）——所有容器圆角统一覆写为窗口主题圆角（默认 `0px`，旋转指示器与滑块旋钮保留圆形），取消一切模糊滤镜与投影，改用主题边框色描边，并将标签转为 `0.12em` 宽字距全大写。

## Components

全站交互控件共用轻量快响应动效语言：通用微交互采用 `--ease: cubic-bezier(0.2, 0.8, 0.2, 1)`（`160ms`）与快出软着陆 `--ease-out: cubic-bezier(0.23, 1, 0.32, 1)`；弹出框与折迭列表采用 `cubic-bezier(0.22, 1, 0.36, 1)`；主题明暗切换使用 `250ms` 全局色彩交叉渐变；普通按钮与芯片按下微缩 `scale(0.96)`，方形图标按钮按下微缩 `scale(0.90)`，而**侧边栏导航行按下绝不缩放**（改用背景加深反馈，还原原生桌面边栏触感）。所有动画必须响应系统的减少动态效果偏好。

### Buttons & Icon Controls
- **Character:** 轻盈、边界清晰，按压瞬间有 `0.96` 干脆回弹但静态时不抢占列表视觉重心。
- **Text / Ghost Button:** 默认高自适应，文字 `12px` 控件静默灰，内边距 `3px 7px`，圆角 `6px`；悬停出现胶囊底色，不可逆删除文字按钮悬停切换危险红底与红字。
- **Action Button:** 描边操作按钮，高度 `27px`，水平内边距 `10px`，纯白/深炭卡片底配 `1px` 边框与微弱 `1px` 阴影，悬停边框加深至弱提示灰。
- **Primary Button:** 填充主强调色背景（`#4F46E5` / `#A5B4FC`）配反白/深墨文字，`500` 字重，悬停亮度提升至 `108%`。
- **Icon Button:** `26×26px` 圆角 `7px`，常态 `14px` 图标呈静音灰，悬停或激活出现胶囊灰底与主文本色；窗口置顶图钉按钮激活时内部实心填充；加载态图标仅旋转内部路径绕 `viewBox` 中心转动（`0.9s linear`），防止整框旋转在亚像素下产生晃动。

### Pop-up Field Controls
- **Character:** Magpie 最具辨识度的行内原子控件，一眼可识别为可点按的弹出选择器。
- **Shape & Style:** 高度 `25px`（托盘浮窗 `24px`、`12px` 字号），圆角 `6px`，内边距 `上0 右5 下0 左8px`，填充胶囊底色；内部依次排布 `14px` 图标、极淡前缀标签（`11.5px`）、当前值（`500` 字重、等宽数字、超长单行省略）与右对齐的极淡下拉箭头。
- **States:** 悬停底色加深；展开弹出菜单时保持悬停底并亮起 `1px` 强调色内描边；若所属行发生配置漂移，模型字段框切换 `38%` 珊瑚红内描边警示。针对无需文字的附加微开关（如推理强度/快速模式），使用 `24×24px` 居中方格控件，启用时右上角出现 `5px` 强调色圆点。

### Segmented Controls & Morphing Navigation
- **Character:** 互斥切换器依靠柔和的底层轨道与亮起的实体滑块区分状态。
- **Segmented Control:** `2px` 内边距的 `7px` 圆角胶囊轨，内部选项高 `22px`、圆角 `5px`、水平内边距 `10px`（紧凑排序条高 `20px`、`11px` 字）；多选项（如 Regions、API 协议或长表单选项）在窄容器下支持平滑横向滚动或自动换行并伴随滑块坐标追踪。
- **Header Tabs vs. Sidebar:** 顶栏居中胶囊无灰底轨道，仅激活项显示高 `24px`、圆角 `6px` 的实体滑块；切换至侧栏模式时，一级项高 `30px`（`7px` 圆角），由独立的浮动高亮滑块以弹簧物理插值在不同行间滑动切换。

### Lists, Rows & Drag-Sorting
- **Character:** 呼吸均匀、以 `1px` 极细水平线分割行与行，不堆积多余卡片边框。
- **List Card & Rows:** 外框圆角 `12px`（托盘 `10px`）、`1px` 边框、纯白/深炭底；主窗口单行最小高 `48px`，图标 `22px`，名称 `500` 字重与副标题 `11.5px` 静音灰垂直居中；行间以 `1px` 淡线分隔。
- **Collapsed & Drifted States:** 漂移警示胶囊与重启胶囊紧随名称之后横向排列（`20px` 高全圆角胶囊）；拖拽排序时，被拖动行浮起（`Drag-Sort Lift` 投影），其余兄弟行以 `220ms` 缓动实时让位滑动。

### Inputs, Framed Editors & Sliders
- **Character:** 精密对齐的表单网格，兼顾长 JSON 编辑与分段刻度调节。
- **Text & JSON Inputs:** 标准输入框高 `27px`（移动端网页自动扩至 `44px`、`16px` 字号防 iOS 自动缩放）、圆角 `7px`、`1px` 边框，聚焦呈现强调色边框与 `3px` 半透明光晕；多行代码/请求头文本域使用等宽字体 `12px / 1.5`，`tab-size: 2`，校验错误切换危险红边框。
- **Framed Editor Alignment:** 编辑表单采用「标签列 `fit-content(132px)` 右对齐 / 控件列 `minmax(0, 1fr)`」双列网格，间隙 `10px 14px`；默认全部按首行文字基线对齐（`first baseline`），保证文字标签与开关、单行文本、选项组天然齐平；对于包含文本输入框的行改用顶部对齐并计算垂直居中偏移，防止 WebKit 在重排基线时误触发页面自动滚动回顶部。
- **Effort Range Slider:** `20px` 高度轨道内置 `4px` 进度条，进度条上按档位嵌有 `3px` 圆点刻度（已越过档位呈反白半透明），配 `16px` 纯白圆形拇指（悬停 `1.08×`、按下 `0.94×`、聚焦叠强调色外环）。

### Picker Popover & Side Icon Rail
- **Character:** 从触发按钮中心（`--ox`）生长出来的磨砂搜索选择器，兼顾海量模型检索与单手分类切换。
- **Container:** 固定宽 `320px`、最大高 `340px`、圆角 `11px`、磨砂浮层底色与高弥散阴影；弹出时带 `-6px` 纵移与 `0.94 → 1.0` 放大入场（`240ms`），关闭时快速收拢沉回按钮（`150ms`）。
- **Search & Side Rail:** 顶部为 `36px` 无框搜索输入区（`1px` 淡底线，键盘输入中底线高亮强调色）；主体左侧可选挂载 `43px` 宽垂直服务商图标导轨（`31×31px` 方块项、`8px` 圆角、带滑动选框背景及悬停右侧弹出反色标签提示）；右侧列表项高 `30px`、`7px` 圆角，悬停或选中呈现微标、收藏星标、极速闪电标与对勾图标。

### KPI Strip, Tables & Progress Bars
- **Character:** 紧致的数据看板密度与无干扰的配额进度阅读体验。
- **4-Column KPI Strip:** 4 等分网格中间以 `1px` 边框色作为细分隔缝，外围包 `12px` 圆角卡片框；每格内边距 `上12px 左右14px 下11px`，核心大数字 `20px / 600` 配 `11px` 大写指标标题与可选下标。
- **Quota Cards & Sticky Table:** 卡片内边距 `10px 12px 11px`（圆角 `10px`），多账户卡片内部用 `8px` 圆角次级底色子卡独立隔开；进度条极度克制（高 `4px`、圆角 `2px`，聚合概览条高 `3px`），触顶满额自动转为琥珀色。切换为表格视图时，首列账户标识在横向滚动中粘性固定，表头 `10.5px` 静音灰、行底 `1px` 实线分隔。

### Modals, Confirmations & Floating Toasts
- **Modal Dialog:** 标准宽 `min(600px, 100%)`（宽敞模式按 `56vw` 弹性扩至上限 `880px`）、圆角 `14px`；内部采用固定 `48px` 顶栏（底 `1px` 线）+ 独立居中滚动表单体 + 固定 `48px` 底栏（顶 `1px` 线）三段式框架，并预留顶栏高度作为模态顶部留白与窗口拖拽条，保证弹窗打开期间依然能拖动桌面窗口。
- **Action Confirm:** 破坏性操作确认独立置顶弹出，宽 `min(420px, calc(100vw - 32px))`，内边距 `22px`，圆角 `14px`，明确区分次级取消键与高危实底红确认键。
- **Floating Status Pill:** 主窗口底部不占固定页脚高度，仅当操作产生即时反馈时在视口底部居中 `18px` 处浮现 `11px` 圆角提示胶囊（内容色与卡片底按 `16%` 混色并配 `30%` 边框描边）；纯提示态透传鼠标点击不阻挡底层列表操作，错误与警告态自动开启文本可选中复制并支持多行折行（最大宽 `560px`、最大高 `40vh`）。

### Signature Patterns
- **Torchlight Sidebar Hover:** 在支持 `oklab` 混色的环境下，鼠标划过侧边栏项目文字与图标时，触发以指针横坐标为圆心（`36px × 400px` 径向渐变）的聚光灯文字高亮效果，指针附近的字符被提亮至纯正主前景色，周围柔和衰减过渡 `15%`。
- **Scroll-Unroll Accordion:** 折叠面板展开采用 `grid-template-rows: 0fr → 1fr`（`260ms` 合拢 / `340ms` 展开），动画过程中动态为容器下缘叠加 `32px` 渐隐遮罩，内部行按索引错峰延迟 `24ms` 伴随 `10px` 下滑与 `0.985 → 1.0` 微放依次落定。
- **Update Pill with Corner Dismiss:** 顶栏更新提示表现为高 `22px` 的胶囊芯片，鼠标悬停其上时，右上角浮现一枚 `14×14px` 悬浮小圆叉按钮（外置偏移 `-9px / -3px` 避开胶囊点击热区），允许用户临时静音更新提示。
- **Scroll-Ends Frosted Capsule:** 当页面滚过一屏后，视口右下角 `16px` 处柔和淡入一枚包含「置顶 / 置底」双键的磨砂胶囊（`9px` 圆角、`26×24px` 按钮、中间 `1px` 短分割线）。
- **Loading Bird & Shimmer Skeleton:** 异步数据载入时显示线性渐变扫描骨架屏（卡片、标题条与两段短线）；未关闭吉祥物开关时，一只 `22×22px` 的线描小喜鹊会站在加载区块或漫游于界面角落拍打翅膀（`0.16s` 交替扇动），赋予极度理性的控制面板一丝克制的生命力。

## Do's and Don'ts

### Do:
- **Do** 保持默认中性冷灰画布与卡片（浅色 `#F4F4F6` / `#FFFFFF`，深色 `#1A1A1E` / `#232327`）克制退让，把色彩与视觉识别度留给真实品牌图标与关键状态胶囊。
- **Do** 让列表右侧的弹出式选择器组使用固定列宽网格，确保同一页面中所有下拉箭头保持垂直对齐。
- **Do** 在卡片内部或胶囊按钮的静默说明文字中使用高对比度控件灰（浅色 `#63636B` / 深色 `#9C9CA6`），保证所有辅助文本满足 `4.5:1` 对比度，并完整配套高对比度模式覆盖与 Okabe–Ito 色盲图表序列。
- **Do** 为所有可折叠/动态高度的内容区保留滚动条沟槽并扣除滚动条宽度，且为表格数据、配额、端口与版本号统一启用等宽数字。
- **Do** 为 Windows 平台同时指定 `Segoe UI Variable Text`、`Cascadia Mono` 与 `Microsoft YaHei UI` 回退，彻底规避小字号宋体渲染缺陷；并在 Windows 桌面壳层中关闭全屏模态遮罩的高斯模糊。

### Don't:
- **Don't** 仅用红/绿圆点区分成败状态——失败圆点必须绘制明确的 `×` 几何形状以确保无障碍可辨。
- **Don't** 给主窗口的静态卡片或列表添加明显的投影，也不要让列表常驻显示拖拽点阵抓手（仅悬停/拖拽/聚焦时在左外缘显现）。
- **Don't** 让侧边栏导航行在按下时产生 `scale(0.96)` 缩放，侧栏列表应通过底色加深回应点按，只有独立按钮与弹出芯片才缩放。
- **Don't** 在主窗口底部保留常驻的空白状态页脚条浪费垂直空间——状态反馈应以浮动胶囊形态按需现身并透传非错误态点击。
- **Don't** 让实心铺满矩形的第三方品牌图标按 `100%` 尺寸与线框图标混排——实心块状图标须按 `82%` 光学缩尺绘制以平衡视觉重心。
