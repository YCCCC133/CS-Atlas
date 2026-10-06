# CS Atlas · 计算机考研资料库

整理计算机考研的 PDF 资料与 Markdown 笔记。PDF 保存原文，Markdown 作为可校对、可引用的知识条目，用于学习检索和构建 AI 知识库。

当前仓库提供目录和模板，尚未收录具体学习资料。

## 资料目录

| 科目 | PDF 原文 | Markdown 知识库 |
| --- | --- | --- |
| 数据结构 | [pdf/data-structures](pdf/data-structures) | [knowledge-base/data-structures](knowledge-base/data-structures) |
| 计算机组成原理 | [pdf/computer-organization](pdf/computer-organization) | [knowledge-base/computer-organization](knowledge-base/computer-organization) |
| 操作系统 | [pdf/operating-systems](pdf/operating-systems) | [knowledge-base/operating-systems](knowledge-base/operating-systems) |
| 计算机网络 | [pdf/computer-networks](pdf/computer-networks) | [knowledge-base/computer-networks](knowledge-base/computer-networks) |
| 数学 | [pdf/mathematics](pdf/mathematics) | [knowledge-base/mathematics](knowledge-base/mathematics) |
| 英语 | [pdf/english](pdf/english) | [knowledge-base/english](knowledge-base/english) |
| 政治 | [pdf/politics](pdf/politics) | [knowledge-base/politics](knowledge-base/politics) |
| 院校信息与其他资料 | [pdf/other](pdf/other) | [knowledge-base/other](knowledge-base/other) |

## 添加资料

1. 将 PDF 放入对应科目的 `pdf/` 目录，文件名建议为 `年份-主题-来源.pdf`。
2. 复制 [知识条目模板](templates/knowledge-entry.md) 到对应的 `knowledge-base/` 目录，按知识点拆分 Markdown。
3. 填写标题、科目、标签、来源 PDF 路径及原文页码，完成正文校对后更新 `reviewed`。
4. 目录下可以增加章节子目录。题目和解析建议分别使用清晰的小节标题。

扫描 PDF 可先经过 OCR 转换，再检查公式、表格、代码和图示。大型 PDF 可使用 Git LFS、Release 附件或注明来源的外部链接。

## 用于 AI 知识库

详见 [Markdown 编写与检索规范](knowledge-base/README.md)。入库时保留条目 ID、标题、科目、标签和来源信息，检索结果应能回溯到原文。

## 资料来源

上传可公开分享的资料，并保留作者、出处及原许可证。公开仓库不改变收录资料的版权；没有明确授权时，可以添加原始链接和自己的学习笔记。
