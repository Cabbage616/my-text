# CONTRIBUTING

感谢你愿意为本仓库贡献内容。为保持内容一致性，请遵守以下规则：

1. 编码与格式
   - 所有 Markdown 文件请使用 UTF-8 编码（无 BOM）。
   - 换行统一使用 LF。可在编辑器中设置保存编码为 UTF-8。

2. 文件组织
   - README.md：仅作站点地图与快速概览；不要在 README 中放置过长的技术文本。
   - docs/：长文本（项目详情、发展历程、新闻、视频列表等）应放在 docs/ 下的子目录中。
   - images/：所有需纳入仓库的图片放 images/ 下并使用相对路径引用。

3. 提交规范
   - 分支命名：feature/<短描述>、fix/<短描述> 或 improve/<短描述>
   - 提交信息示例："chore: improve README structure; move long content to docs/"

4. 编辑流程
   - 提交 PR 到主分支（通常为 main）。在 PR 描述中说明修改目的与是否已校验编码。
   - 对于恢复被替换的中文原文片段（原文中出现�或[...]），请同时说明原始来源页面链接或保留来源注释。

5. 工具建议
   - 编码转换：iconv（Linux/macOS）、Notepad++（Windows）或 VS Code 的“Reopen with Encoding”。

感谢你的贡献。