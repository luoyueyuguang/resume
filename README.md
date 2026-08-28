# Resume — 简洁优雅的 XeLaTeX 简历模板

本仓库是一个基于 [**billryan/resume**](https://github.com/billryan/resume) 二次开发的
简洁优雅的 **XeLaTeX 简历模板**（中文版），并在此基础上整理了我的个人简历
（入口：`resume-zh_CN.tex`）。

> 编译：`make zh_CN`（XeLaTeX · 外部中文字体已内置于 `fonts/`，开箱即用）

---

## 本仓库的特性（相对原模板的修改）

- 支持 **FontAwesome 6.6.0**，新增若干基本信息（邮箱、电话、GitHub、主页、code 等）
- 支持多种标题行样式：`\settitlelinestyle{default | partialbg | fullbg}`
- 支持定义高亮色 `accentcolor` 与命令 `\texthl{}`
- 优化 PDF 目录生成，解决中文乱码，新增 `bookmark`
- 优化仓库文件组织结构与 `Makefile`
- 新增 **GitHub Actions**：TeX Live 容器 + XeLaTeX 自动编译并上传简历 PDF

## 我的简历内容

- **工作经历**：北京开源芯片研究院 (BOSC)，AI 软件栈开发工程师（实习转正）
- **项目经历**：Qwen3-0.6B C 演示（公司项目）、MinivLLM 推理引擎（个人项目）
- 简历 PDF 见仓库 Actions 构建产物，或 [最新 Release](../../releases)

---

## 🙏 致谢 Acknowledgements

本模板 **Fork 自 [billryan](https://github.com/billryan) 的 [resume](https://github.com/billryan/resume)**——
一个简洁优雅、无痛支持中英文的 XeLaTeX 简历模板。原作者的模板设计精巧、易于定制，
本仓库的很多优良特性（分节、基本信息、`\datedsubsection` 等）都直接继承自原项目。
**在此向 billryan 及原项目表示由衷的感谢！**

同时感谢以下项目与作者：

- **[gvgramazio/latex-fontawesome6](https://github.com/gvgramazio/latex-fontawesome6)**：
  FontAwesome 6 的 XeLaTeX 绑定，本仓库的 `stys/fontawesome6.sty` 在它的基础上做了
  少量调整（删旧、新增部分图标）。
- **[Font Awesome](https://fontawesome.com)**（6.6.0 Free）：简历中的图标字体来源。
- 原 README 中列出的众多灵感来源与教程，包括：
  - [zachscrivena/simple-resume-cv](https://github.com/zachscrivena/simple-resume-cv)
  - [res（CTAN）](https://www.ctan.org/pkg/res)
  - [JianXu's CV](http://www.jianxu.net/en/files/JianXu_CV.pdf)
  - [paciorek 的 CV/Resume 模板](http://www.stat.berkeley.edu/~paciorek/computingTips/Latex_template_creating_CV_.html)
  - [ShareLaTeX 的 LaTeX 简历教程](https://www.sharelatex.com/blog/2011/03/27/how-to-write-a-latex-class-file-and-design-your-own-cv.html)
  - `moderncv` 等经典简历模板

> **再次向 billryan 及所有开源贡献者致以诚挚的感谢！** 开源精神让这份简历模板得以不断完善。

## 原始说明

原作者的完整 README（含详细使用说明、FontAwesome 使用方法、编译方式等）已完整保留在
[`README-original.md`](./README-original.md)，欢迎查阅。

---

## License

[The MIT License (MIT)](http://opensource.org/licenses/MIT)

不含版权字体（Copyrighted fonts are not subjected to this License）。
