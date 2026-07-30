# 西安瑞泰 (Brictec) — 网站内容整理 / Site Map

简短说明：
本仓库整理并备份 https://www.brictec.com/ 的中文站点结构与内容，便于离线编辑、版本控制与发布。README 保持为站点地图与快速概览，长篇条目（项目详情、完整团队简介、新闻稿）已拆分到 docs/ 目录以便维护。

Short summary:
This repository organizes content from the Chinese site for easier editing and publishing. README contains a concise site map; long articles live under docs/.

---

## 主要改动说明
- 修复编码与格式化建议：请确保所有 Markdown 文件使用 UTF-8 编码（见 CONTRIBUTING.md）。
- 将冗长条目（项目、团队、新闻）移动到 docs/ 目录，README 保持索引与快速概览。
- 添加 CONTRIBUTING.md、.gitattributes 来统一编码/编辑规范。

---

## 目录 (Table of Contents)
- 关于瑞泰
  - [企业概况](#关于瑞泰)
  - [技术团队（摘要）](docs/team.md)
  - [发展历程（摘要）](docs/history.md)
- 产品
  - 原料处理设备（摘要，详见 docs/products/）
  - 砖机挤出机
  - 自动化设备
  - 隧道窑
  - 打包设备
- [工程案例（摘要/链接）](docs/projects/README.md)
- 视频（外部链接集合）
- FAQ（常见问题）
- 服务（原料分析/设计/配件/升级/生产管理）
- 新闻（摘要，详见 docs/news/）
- 联系我们（地址、邮箱、WhatsApp/WeChat）
- [如何贡献](CONTRIBUTING.md)
- 许可（如需添加 LICENSE，请在仓库根目录添加）

---

## 快速说明 / Quick notes
- 编码/字符：所有 Markdown 文件请使用 UTF-8 编码，避免出现�之类的替代字符。
- 目录策略：README 作为目录与站点地图；docs/ 保存可独立编辑的长篇内容；images/ 存放必要的图像资源。
- 外部链接：README 中保留对原站点的外部引用；docs/ 中的详细内容可保留完整原文或用简短摘要并链接回原站点。

---

## 联系方式（概览）
- 公司：西安瑞泰建材科技有限公司 (Xi’an Brictec Engineering Co., Ltd)
- 地址：陕西省西安市雁塔区唐延南路10号中兴产业园B座B501
- Email: info@brictec.com
- WhatsApp/WeChat: +86 181 8262 2677
- Website: https://www.brictec.com/

---

## 下一步（维护建议）
1. 由仓库管理员审核 docs/ 中的项目与团队条目，恢复原文中被替换的片段（如遇编码问题，请用 GBK->UTF-8 转换工具恢复）。
2. 确认是否要在仓库中添加 LICENSE（推荐 MIT 或公司专用许可）。
3. 若需要国际化，添加 EN/ 子目录或在 README 顶部提供英文摘要的全文翻译。
