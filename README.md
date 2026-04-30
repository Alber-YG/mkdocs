# 部门文档模板仓库

本仓库为部门内部 Markdown 文档模板与规范仓库，按“方案 / 产品 / 研发 / 实施”四类组织，支持：
- 统一 frontmatter（元数据）规范与校验
- MkDocs (Material) 生成文档站点（可部署到 GitHub Pages / 内网）
- CI 自动 lint、构建、链接检查与 embeddings 占位任务

使用步骤（快速开始）：
1. 克隆仓库并修改 `mkdocs.yml` 的站点信息和 `docs/` 下内容。
2. 本地测试：`pip install -r requirements.txt`（或按需安装 mkdocs-material）然后 `mkdocs serve`
3. 提交到 GitHub，启用 GitHub Actions 自动构建与校验。

请参阅 `docs/templates/frontmatter-template.md` 以获取 frontmatter 模板。
