# StayLens DevLog

> 从 2025-05-13 起开始记录。此前开发历史未归档。

---

## 2025-05-13 项目规范化节点

### 当前状态快照
- 单文件 HTML 架构，index.html 共 4854 行
- 三种评价模式（通用/度假/商旅）已实现
- 多种文案输出风格已实现
- 对比记录、草稿自动保存已实现
- 已公开发布：https://heyyeqi.github.io/StayLens/

### 已知未解决问题（存档）
- 草稿恢复失败时无用户反馈（index.html:4806）
- 无 JSON 草稿导入/导出能力
- 多处 catch 静默失败，可观测性差

### 备注
从此节点起，每次 Codex 完成任务后必须追加 devlog 记录。

## 2026-05-13 项目规范文件入库

### 做了什么
- 将下载目录中的 `CLAUDE.md` 和 `devlog.md` 放入 `StayLens` 仓库根目录
- 根据 `CLAUDE.md` 约定，补记本次操作到项目 `devlog.md`

### 改动位置（行号）
- `CLAUDE.md:1`
- `devlog.md:1`

### 遗留问题
- `index.html:4806` 的草稿恢复失败仍然只有 `console.error`，没有用户可见提示
