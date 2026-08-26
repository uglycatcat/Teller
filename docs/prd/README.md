# Teller 产品需求文档（PRD）

本目录是 Teller 的一套完整、结构化产品需求文档组，整合自以下源文档：

- `README.md` — 项目定位与开发须知
- `docs/history/CONTEXT.md` — 产品模型主文档（30+ 概念定义 + 规避清单）
- `docs/history/adr/` — 72 份架构决策记录（ADR）
- `docs/history/grill/` — 多场 grill 问答记录，含 `sessions/full-product-refinement/`（Q68–Q95 增量，含快照→git、章节状态、AI 细节等）

## 文档组结构（建议按序阅读）

| 编号 | 文档 | 内容 |
|---|---|---|
| 01 | product-overview.md | 定位、背景、目标用户、价值、参考、边界 |
| 02 | glossary.md | 术语表：全部概念精确定义 + 规避清单（_Avoid_） |
| 03 | data-model.md | 作品目录结构、实体、frontmatter、状态机 |
| 04 | workbench.md | 工作区、三栏布局、窗口、分屏、欢迎页 |
| 05 | content-management.md | 章节、设定、其它文件、资源目录管理 |
| 06 | editor.md | 编辑器、Markdown、排版、专注模式、撤销/标签 |
| 07 | ai.md | AI 面板、内联、Agent、上下文、技能、规则、审阅 |
| 08 | version-control.md | 快照→git：commit、branch、checkout、历史 |
| 09 | search-stats-export.md | 搜索、字数统计、导出 |
| 10 | settings-platform.md | 设置、主题、跨平台、分发、隐私 |
| 11 | non-functional.md | 性能、安全、可靠性、本地优先 |
| 12 | adr-index.md | 决策记录索引（源 ADR + 本会话 ADR 映射） |
| 13 | art-and-interaction.md | 视觉语言、字体、动效、状态反馈、特定界面 |

## 约定

- 本文档组描述的是**完整产品形态**（PRD 范围），不按迭代切片；某功能的具体交付迭代另议。
- 冲突优先级：**本 PRD**（含 `full-product-refinement` 会话增量）> `docs/history/CONTEXT.md` > 旧 ADR。
- 每篇文档中的「规避清单」来自源文档的 `_Avoid_` 项，代表「刻意不做的行为」，与正向需求同等重要。
