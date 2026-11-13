# Doc2X AI文档翻译解析插件（Zotero 7/8）

英文名：**doc2x-ai-translate**（1.1.12 及更早版本名为 doc2x-parse）

在 Zotero 里直接用 [Doc2X](https://doc2x.noedgeai.com) 处理论文 PDF：

- **保留排版翻译**：生成版式与原文一致的译文 PDF
- **双语对照**：原文与译文对照阅读
- **解析 / 翻译为 Markdown 笔记**：结果保存回论文条目
- 支持多选 PDF 顺序批量处理

**使用教程**：[Zotero 翻译插件教程：安装、登录、单篇与批量翻译](https://doc2x.noedgeai.com/help/zh-cn/faq/doc2x-zotero-plugin.html) · **插件介绍与下载**：[Doc2X Zotero 翻译插件](https://doc2x.noedgeai.com/zotero-translate/)

## 安装

1. 在 [Releases](https://github.com/NoEdgeAI/Doc2XZoteroPlugin/releases/latest) 下载 `doc2x-ai-translate.xpi`（不要解压）。
2. 打开 Zotero「工具 → 插件」，点齿轮菜单选「从文件安装插件」，选中 `.xpi`；也可以直接把文件拖进插件窗口。
3. 首次使用需登录 Doc2X 客户端并获取授权，步骤见[教程的客户端授权一节](https://doc2x.noedgeai.com/help/zh-cn/faq/doc2x-zotero-plugin.html#client-authorization)。

已安装的插件会自动更新。

| Zotero 版本 | 安装包 |
| --- | --- |
| 9、10、11 | [NoEdgeAI/Doc2XZoteroPlugin9](https://github.com/NoEdgeAI/Doc2XZoteroPlugin9/releases/latest) |
| 7、8 | 本仓库 |

本仓库只发布安装包和自动更新信息（`release` 标签下的 `update.json`）。

---

**doc2x-ai-translate** translates and parses PDFs in Zotero with Doc2X AI: layout-preserving translation, bilingual output, or Markdown notes. Download `doc2x-ai-translate.xpi` from [Releases](https://github.com/NoEdgeAI/Doc2XZoteroPlugin/releases/latest) and install it via *Tools → Plugins → ⚙ → Install Plugin From File*. For Zotero 9/10/11, use [NoEdgeAI/Doc2XZoteroPlugin9](https://github.com/NoEdgeAI/Doc2XZoteroPlugin9/releases/latest). Guide: [Zotero translation plugin tutorial](https://doc2x.noedgeai.com/help/en/faq/doc2x-zotero-plugin.html).
