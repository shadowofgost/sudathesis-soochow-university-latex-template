<!--:
 #  @Author           : Albert Wang
 #  @Time             : 2023-01-04 13:42:01
 #  @Description      :
 #  @Email            : shadowofgost@outlook.com
 #  @FilePath         : /sudathesis-soochow-university-latex-template/README.md
 #  @LastTime         : 2024-05-07 17:07:24
 #  @LastAuthor       : Albert Wang
 #  @Software         : Vscode
 #  @ Copyright Notice : Copyright (c) 2023 Albert Wang 王子睿, All Rights Reserved.
 # : -->
<img src="./help/sudamark.jpg" width = "20%" />

![readme](https://img.shields.io/badge/standard-readme-brightgreen)
![XeLaTex](https://img.shields.io/badge/XeLaTex-pass-brightgreen)
![overleaf](https://img.shields.io/badge/overleaf-pass-brightgreen)

# sudathesis-soochow-university-latex-template

Naive LaTex Template For Soochow University Thesis,Based on ThuThesis 苏州大学毕业论文LaTex模板，适用于本科、硕士和博士还有日常论文写作，基于[清华大学学位论文 LaTeX 模板](https://github.com/tuna/thuthesis)打造

## 简介

本模板是为了方便苏州大学本科生、硕士生、博士生毕业论文和日常论文的撰写而制作的LaTex模板，适配`苏州大学本科毕业设计（论文）装订及打印格式（2020 版）`和`苏州大学研究生学位论文基本格式（2018版）`的要求

**希望本模板能够帮助到你！**
**也希望有识之士能参与贡献搭建苏州大学的Latex模板（涵盖本硕博毕业论文以及日常论文的latex模板）**

本模板是使用[清华大学学位论文 LaTeX 模板](https://github.com/tuna/thuthesis)的发布版本修改而成，开发版见原版内容。

* 发布版：
  * [GitHub Releases](https://github.com/shadowofgost/sudathesis-soochow-university-latex-template/releases)：最新版的及时发布途径。
  <!--:
  * [Overleaf](https://www.overleaf.com/latex/templates/thuthesis-tsinghua-university-thesis-latex-template/wddqnwbyhtnk)：Overleaf 的模板。
  : -->
  * [TexPager](https://www.texpage.com/template/c05aaf0d-7a14-4a1c-96b5-938556f726b1)
  * [Overleaf](https://www.overleaf.com/latex/templates/sudathesis-soochow-university-latex-template-v2-dot-3-0/tmdsxjgmdfyq)：Overleaf 的模板。
* 开发版：[GitHub](https://github.com/tuna/thuthesis)

## 特点

> 现有的关于苏大毕业论文LaTex模板的内容包括[@huhamhire](https://github.com/maxogden) 的项目[sudathesis](https://github.com/huhamhire/sudathesis)、[@hinesboy](https://github.com/hinesboy)的[SUDA-Latex](https://github.com/hinesboy/SUDA-Latex)和[@tianhaoo](https://github.com/tianhaoo)的项目[Soochow-University-Thesis-Overleaf-LaTeX-Template](https://github.com/tianhaoo/Soochow-University-Thesis-Overleaf-LaTeX-Template)。

但是以上项目都是以研究生毕业论文为主，并未有针对本科生、研究生和博士生的论文模板，所以自己在清华latex模板的基础上参照本科生毕业论文2020要求和研究生学位论文基本格式2018版进行了修改，使之同时满足本科生、硕士生和博士生毕业论文的格式要求，并对完全跨平台编译做了适配，使之运行在 [Overleaf 平台](https://www.overleaf.com/)上，也可以在vscode平台上使用，同时也实现了多平台（windows，mac，linux）同样的输出效果，如果你有如下的痛点，则可以考虑使用本项目：

* 厌倦了臃肿的本地latex开发环境和被texlive搞乱的系统环境变量

* 修改大论文时各种版本的pdf文件传来传去，在版本对齐中浪费了大量时间，无法多人协作

* 本地latex环境的依赖冲突问题或者其他问题导致编译出现莫名bug，本地编译器无法正常运行

* VScode的插件`LaTeX Workshop`出bug不会调试，自带编辑器`TexWorks editor`又慢又老掉牙

* 在实验室电脑配置了论文环境，对该电脑百般呵护生怕数据丢失，离开实验室后无法在其他设备上写毕业论文

* 本地word格式调整，图片章节编码令人烦躁，工作量大

* overleaf上字体输出效果与windows版本有区别，在不同平台字体输出效果与windows版本有区别不是正常的word版本的宋体黑体楷体。

## 相关文件文件夹介绍

* **模板的初始状态就介绍了模板的使用教程，help文件夹中的help.pdf是使用教程的编译结果，如有问题请参考教程**
* `.vscode`：存放着vscode的插件`LaTeX Workshop`的配置文件
* `bibstyle`：参考文献的样式设置
* `contents`：摘要、论文主题的源码
* `fonts`：存放字体的文件夹
* `figures`：存放图片的文件夹和插入的pdf文件夹
* `reference`：存放引用文献的文件夹
* `help`：存放帮助文件的帮助文档
* `standards`：存放论文格式标准的文件夹
* `main.tex`：编译的主体文件
* `setup.tex`：配置文件，在编译前请设置查看注释设置一下
* `sudathesis.cls`：模板文件,根据使用的平台不同使用所在平台的字体，默认使用fonts内的windows字体保证跨平台编译一致性。
* `main.pdf`：编译生成的pdf文件也是论文
* `help.pdf`：帮助文档，里面有详细的关于模板的使用说明，可以参考相关的tex文件比对查看

## 使用方法

1. 下载 最新的release 文件
2. 在`overleaf.com` 中 `New Project -> Upload Project -> select a .zip file`, 上传刚才下载的zip文件
3. 在左上角 `Menu -> Compiler` 中选择编译器为XeLaTex， 然后右上角ReCompile

模板有三种使用方式，Overleaf，本地编译，或者 Container 编译：

* Overleaf 是一个线上 LaTeX 编辑器，可以在不安装任何工具的情况下编写 LaTeX 文档，同时也可以和其他人共享文档，共同编辑。
* 本地编译比 Overleaf 更快，而且本地编译可以使用 Git 来记录版本。推荐有能力的同学设置本地编译环境，并推荐使用 Visual Studio Code 配合 LaTeX workshop 插件 (vscode 使用方式见[FAQ](./docs/FAQ.md))。本地也可以及借助vscode的devcontainer 插件快速地实现本地编译。
* Container 编译是使用 GitHub 提供的 Codespace 搭配 Container 来编译，这个环境提供了浏览器内的 VS Code 界面以及 TeX Live 的编译环境。这种方式适合熟悉 Container 与 GitHub Codespace 相关用法的同学使用。

### Overleaf

1. 下载最新的release 文件
2. 在`overleaf.com` 中 `New Project -> Upload Project -> select a .zip file`, 上传刚才下载的zip文件
3. 在左上角 `Menu -> Compiler` 中选择编译器为XeLaTex， 然后右上角ReCompile
   * 选择 "Compiler" 为 "XeLaTeX"
   * 选择 "TeX Live version" 为 "2022" 或者更新的版本

### 本地编译

1. 安装 TeXLive 工具包，编译需要 XeTeX 引擎。
2. 下载最新的release 文件
3. 在根目录下运行命令 `latexmk`（或者 `latexmk -xelatex`）即可。**请务必使用此 `latexmk` 命令进行编译（除非你已经了解 LaTeX 的工作机制），否则你可能遇到参考文献无法显示等问题**
4. 如需使用 LuaTeX 编译，可运行命令 `latexmk -pdflua`

> **注意**
>
> * 每年的三月底四月初会有 TeXLive 的版本升级，届时本模板会根据 TeXLive 的更新做出一定的修改，请在提交最终论文前查看并应用本模板的更新。
> * 如果不想花时间安装texlive工具包，可以使用vscode+devcontainer插件，实现本地的容器化开发，在本地创建开发容器。

### 使用容器编译

本模板提供了一套配置文件，用以支持在容器中安装TeX Live，项目使用的字体，以及VS Code上的[LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)插件，配合GitHub Codespaces可以做到开箱即用。

GitHub Codespace使用方法：

1. 创建个人的项目（直接fork，或自行clone并修改remote）
2. 在个人的项目主页点击"Code"
3. 点击"Codespaces"
4. 点击"New codespace"
5. 等待容器构建（这一过程约要2分钟）
6. 构建完成后，可以选择在VS Code（需要[GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)插件）中或在浏览器中打开，然后按照在本地的使用方式使用

> **注意**
>
> * 这一功能的初衷是为了方便性能较弱的设备（例如低功耗笔记本电脑）也能利用免费的云运算资源较快地完成编译，因此**不建议**在本地性能较强的机器上使用（请改用"本地编译"）。


## 论文格式标准的内容

* [本科生毕业论文格式标准](./standards/本科生模板设计格式.md)
* [硕士生和博士生毕业论文格式标准](./standards/研究生模板设计格式.md)

## 进阶

* 如果有以下情况：
  * 对`overleaf.com`网站在线编译的速度有要求
  * 对文章内容隐私性有要求
  * 梯子不快的同学，可以考虑在内网的强悍服务器上搭建一个[本地的Overleaf平台](https://github.com/overleaf/overleaf)，现已支持docker

## 相关仓库

* [sudathesis](https://github.com/huhamhire/sudathesis) — LaTeX template for bachelor's thesis in Soochow University
* [SUDA-Latex](https://github.com/hinesboy/SUDA-Latex) — 苏州大学-硕士毕业大论文-Latex模版（附安装使用说明）
* [Overleaf](https://github.com/overleaf/overleaf) - A web-based collaborative LaTeX editor
* [Soochow-University-Thesis-Overleaf-LaTeX-Template](https://github.com/tianhaoo/Soochow-University-Thesis-Overleaf-LaTeX-Template)。-苏州大学-硕士生毕业论文模板

## 维护者

[@shadowofgost](https://github.com/shadowofgost)。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/shadowofgost/sudathesis-soochow-university-latex-template/issues) 或者提交一个 Pull Request。

如果发现学校论文格式标准的内容有更新，可以及时提一个issue

sudathesis-soochow-university-latex-template 遵循 [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) 行为规范。

## 使用许可

[LPPL 1.3c](LICENSE) © shadowofgost

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=shadowofgost/sudathesis-soochow-university-latex-template&type=Date)](https://star-history.com/#shadowofgost/sudathesis-soochow-university-latex-template&Date)
