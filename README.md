# uix

技术栈无关的 `DESIGN.md` 设计体系合集，遵循 [impeccable](https://github.com/pbakaus/impeccable) / Stitch 规范。

## 已收录风格

| 类别 | 名称 | 路径 |
|---|---|---|
| Desktop | Claude Desktop | [`desktop/claude/DESIGN.md`](desktop/claude/DESIGN.md) |
| Desktop | Codex Desktop | [`desktop/codex/DESIGN.md`](desktop/codex/DESIGN.md) |
| Desktop | Devin Desktop | [`desktop/devin/DESIGN.md`](desktop/devin/DESIGN.md) |
| Web | v0 by Vercel | [`web/v0/DESIGN.md`](web/v0/DESIGN.md) |

## 快速开始

### 使用 impeccable

将下面这段提示词发给你的 AI（按需替换风格路径与末尾需求）：

```text
/impeccable 先从 https://raw.githubusercontent.com/kurerere/uix/main/desktop/claude/DESIGN.md 下载并保存为当前项目根目录的 DESIGN.md，锁定这份视觉体系不要重新选风格，然后基于它开始设计并实现：<你的需求>
```

### 未使用 impeccable 时

去掉开头的 `/impeccable`，直接发送同一段提示词即可，AI 会将 `DESIGN.md` 落盘并按其中的色板、排版、间距与组件规范实现界面。
