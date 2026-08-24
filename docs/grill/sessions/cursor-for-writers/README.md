# Grill 会话：Cursor-for-Writers（长文写作场景的 Cursor）

- 开始日期：2026-08-07
- 技能：grill-with-docs
- 目的：在「Teller = 专门用于小说/长文写作的 Cursor」这一本质定位下，澄清产品最终形态
- 隔离说明：本会话产出只写在本目录；不直接改仓库根 `CONTEXT.md` 与 `docs/adr/`（那些可能被其它 grill 会话同时修改）。达成共识后可由你决定是否合并。

## 我对 Teller 的理解（开场基线）

**一句话：** Electron 桌面端、本地文件夹即作品的 AI 原生长文写作工作台；工作台心智对齐 VS Code/Cursor，内容对象是章节/设定而非源码。

**已从仓库吸收的要点（仅作背景，本会话可修正）：**

- 作品 = 本地目录；`chapters/` + `settings/` + 可自建同级资料夹（如 `reference/`）
- 三栏：左资源 / 中多标签编辑（可网格分屏）/ 右 AI；专注模式
- Markdown 文稿；自动保存；快照（含时间线与 diff）
- AI 交互对齐 Cursor（面板、内联、流式、接受/拒绝、@ 附加）；有 Agent 模式做多文件改写
- 本地优先、BYOK、无 Key 也能写

**本会话要钉死的核心张力：**

> Cursor 是「代码仓库上的 AI IDE」。Teller 若是「小说作品上的 Cursor」，哪些必须像 Cursor，哪些必须故意不像？

## 本目录结构

```
docs/grill/sessions/cursor-for-writers/
  README.md          ← 本文件
  grill-log.md       ← 问答过程
  CONTEXT.md         ← 本会话术语表（可合并到根 CONTEXT）
  adr/               ← 本会话 ADR
```
