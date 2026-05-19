# ContextLearn 智能语境单词阅读助手
<img width="1280" height="697" alt="image" src="https://github.com/user-attachments/assets/2e90d1e6-2ca9-424a-98f8-6992c3ef80e5" />
场景：`ContextLearn`是一个基于浏览器的纯前端工具，英语学习者在阅读 PDF/EPUB 电子书时，希望能根据自己上传的 Excel 词库，自动将书中的中文翻译替换回英文单词，从而在语境中复习。
用户上传一个 Excel 词库（两列：英文单词、中文释义）和一本电子书（PDF 或 EPUB）。
系统解析书籍文本，使用正则匹配算法将书中的`中文释义`替换为对应的`英文单词`，并加高亮和悬浮提示。

### 交互系统：
* 点击单词可以发音并加入侧边栏的`生词本`。
* 支持鼠标选中原文进行`快速摘抄`，并能记录笔记。
* 实现`阅读进度保存`，下次打开同一本书能自动跳转。
### 数据与技术栈：
* 数据保存在本地 LocalStorage，支持全量 JSON 备份以及导出为 Markdown 表格。
* **技术栈：** HTML5/CSS3/JS
* **使用外部库：** xlsx.js (Excel), pdf.js (PDF), jszip (EPUB/ZIP)
### 使用步骤
- 准备Excel 词库（两列：英文单词、中文释义）
- <img width="634" height="551" alt="image" src="https://github.com/user-attachments/assets/e7b5b547-6324-4275-b855-881a4940b9a0" />
- 一本电子书（PDF 或 EPUB）
- <img width="549" height="635" alt="image" src="https://github.com/user-attachments/assets/886132fc-7b82-4403-8df2-f77870f44204" />
- <img width="1280" height="699" alt="image" src="https://github.com/user-attachments/assets/e3714b01-cd91-4f7b-baeb-b1b8e11e7028" />
### 项目地址
https://catttid.github.io/ContextLearner/






