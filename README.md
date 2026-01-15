# SWUFE LaTeX Resume Template（中文）

本仓库提供一个面向**西南财经大学**场景的中文一页简历 **LaTeX 模板**，包含模板源码与效果图预览。  
简历入口文件：`resume-zh_CN.tex`（如仓库实际入口不同，请以项目文件为准）。

> 本模板基于开源项目进行二次改造与个性化设计（见“致谢与来源”），并针对中文排版、版式与展示风格做了调整。

---

## 预览效果

![preview](./template_resume_01.png)

---

## 特性

- **一页式简历布局**，适合校招/实习/科研简历
- 结构清晰：教育背景 / 科研经历 / 项目经历 / 比赛经历 / 技能特长
- 易于定制：通过宏命令与统一样式快速增删内容
- 支持 Unicode 中文排版，推荐使用 **XeLaTeX**
- 可选头像、页眉色条、分节标题色块等视觉样式（以仓库实现为准）

---

## 使用方法

### 方法 A：Overleaf 在线使用（推荐）

1. 下载本仓库源码（ZIP）或 `git clone` 到本地
2. 上传到 Overleaf（New Project → Upload Project）
3. 设置编译器为：**XeLaTeX**
4. 编译入口文件：`resume-zh_CN.tex`


## 字体说明（非常重要）

本模板历史上存在两种中文字体方案（以仓库实际文件为准）：

- `zh_CN-Adobefonts_internal`：系统已安装 Adobe 中文字体时使用
- `zh_CN-Adobefonts_external`：从外部字体目录（例如 `./fonts/`）加载

## 文件结构（参考）

```text
.
├─ resume-zh_CN.tex          # 入口文件（示例/模板）
├─ resume.cls                # 模板 class（样式定义）
├─ *.sty                     # 样式/功能扩展
├─ template_resume_01.png    # 预览图
└─ assets/                   # 图片资源（建议）
```

---

## 致谢与来源

本模板修改自项目：

- [billryan/resume](https://github.com/billryan/resume/)

并参考/受启发于：

- [zachscrivena/simple-resume-cv](https://github.com/zachscrivena/simple-resume-cv)
- [res (CTAN)](https://www.ctan.org/pkg/res)
- [JianXu's CV](http://www.jianxu.net/en/files/JianXu_CV.pdf)
- [paciorek's CV/Resume template](http://www.stat.berkeley.edu/~paciorek/computingTips/Latex_template_creating_CV_.html)
- [How to write a LaTeX class file and design your own CV (Part 1) - ShareLaTeX](https://www.sharelatex.com/blog/2011/03/27/how-to-write-a-latex-class-file-and-design-your-own-cv.html)
- [How to write a LaTeX class file and design your own CV (Part 2) - ShareLaTeX](https://www.sharelatex.com/blog/2013/06/28/how-to-write-a-latex-class-file-and-design-your-own-cv.html)

---

## License

MIT License

> Copyrighted fonts are not subjected to this License.  
> 请勿在本仓库中分发受版权保护的字体文件（如 Adobe 字体）。
