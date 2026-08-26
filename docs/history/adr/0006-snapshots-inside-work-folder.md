# 快照存放在作品目录内的元数据区

快照随作品走：存放在作品文件夹内的约定元数据目录（例如 `.teller/snapshots/`），与 `chapters/`、`settings/` 分离。拷贝或备份作品目录即带走历史；不采用应用全局快照库，也不把「仅手动导出 zip」当作唯一版本手段。

> **修订（2026-08-25）**：快照已升级为类 git 版本管理（commit + branch，无自动 merge），仍存作品目录元数据区；详见 `docs/prd/08-version-control.md`。
