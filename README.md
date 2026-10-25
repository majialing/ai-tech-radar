# AI Tech Radar

AI 前沿技术情报的累计 HTML 档案。

- 固定网页：https://majialing.github.io/ai-tech-radar/
- 发布文件：`main` 分支根目录的 `index.html`
- 发布方式：GitHub Pages，从 `main` 的 `/ (root)` 部署
- 日报时区：北京时间（Asia/Shanghai）

## 增量更新

更新前读取 `index.html` 的最新内容和 blob SHA。保留 `radar-data` JSON 中既有的 `issues`、`entries` 及其稳定 ID，去重后追加或修正条目，更新 `updatedAt`，并使用最新 SHA 提交同一个文件。不要用只包含当天数据的新页面覆盖历史档案。

首期内容沿用 2026-10-25 的 ChatGPT HTML 附件；后续日报由原 ChatGPT 定时任务生成。本仓库本身不运行新闻生成任务。
