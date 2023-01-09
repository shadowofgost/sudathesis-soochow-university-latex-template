<!--:
 #  @Author           : Albert Wang
 #  @Time             : 2023-01-04 13:42:01
 #  @Description      :
 #  @Email            : shadowofgost@outlook.com
 #  @FilePath         : /Sudathesis-Bachelor-Template/README.md
 #  @LastTime         : 2023-01-09 17:45:29
 #  @LastAuthor       : Albert Wang
 #  @Software         : Vscode
 #  @ Copyright Notice : Copyright (c) 2023 Albert Wang 王子睿, All Rights Reserved.
 # : -->
<img src="./help/sudamark.jpg" width = "20%" />

![readme](https://img.shields.io/badge/standard-readme-brightgreen)
![XeLaTex](https://img.shields.io/badge/XeLaTex-pass-brightgreen)
![overleaf](https://img.shields.io/badge/overleaf-pass-brightgreen)
# Sudathesis-Bachelor-Template

Naive LaTex Template For Soochow University Thesis (Bachelor Degree),Based on ThuThesis 苏州大学毕业论文LaTex模板 (学士学位)，基于[清华大学学位论文 LaTeX 模板](https://github.com/tuna/thuthesis)打造


## 简介

本模板是为了方便苏州大学本科生毕业设计（论文）的撰写而制作的LaTex模板，适配`苏州大学本科毕业设计（论文）装订及打印格式（2020 版）`的要求

本模板目前暂未针对苏州大学硕士、博士论文或其他学术论文格式进行相关优化。

**希望本模板能够帮助到你！**
**也希望有识之士能参与贡献搭建苏州大学的Latex模板（涵盖本硕博毕业论文以及日常论文的latex模板）**

本模板是使用[清华大学学位论文 LaTeX 模板](https://github.com/tuna/thuthesis)的发布版本修改而成，开发版见原版内容。
* 发布版：
  * [GitHub Releases](https://github.com/shadowofgost/Sudathesis-Bachelor-Template/releases)：最新版的及时发布途径。
  * [Overleaf](https://www.overleaf.com/latex/templates/thuthesis-tsinghua-university-thesis-latex-template/wddqnwbyhtnk)：Overleaf 的模板。
* 开发版：[GitHub](https://github.com/tuna/thuthesis)

## 特点

> 现有的关于苏大毕业论文LaTex模板的内容包括[@huhamhire](https://github.com/maxogden) 的项目[sudathesis](https://github.com/huhamhire/sudathesis)、[@hinesboy](https://github.com/hinesboy)的[SUDA-Latex](https://github.com/hinesboy/SUDA-Latex)和[@tianhaoo](https://github.com/tianhaoo/Soochow-University-Thesis-Overleaf-LaTeX-Template)。

但是以上项目都是以研究生毕业论文为主，并未有针对本科生的论文模板，所以自己在清华latex模板的基础上参照本科生毕业论文2020要求进行了修改，使之适配本科生毕业论文的格式要求，并对完全跨平台编译做了适配，使之运行在 [Overleaf 平台](https://www.overleaf.com/)上，同时也实现了多平台（windows，mac，linux）同样的输出效果，如果你有如下的痛点，则可以考虑使用本项目：

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
* `data`：摘要、论文主题的源码
* `figures`：存放图片的文件夹和插入的pdf文件夹
* `reference`：存放引用文献的文件夹
* `help`：存放帮助文件的帮助文档
* `main.tex`：编译的主体文件
* `setup.tex`：配置文件，在编译前请设置查看注释设置一下
* `sudathesis.cls`：模板文件
* `main.pdf`：编译生成的pdf文件也是论文
* `help.pdf`：帮助文档，里面有详细的关于模板的使用说明，可以参考相关的tex文件比对查看

## 适配`苏州大学本科毕业设计（论文）装订及打印格式（2020 版）`的要求

### 内容框架

1. 中文标题、中文摘要及关键词
2. 英文标题、英文摘要及关键词
3. 目录
4. 论文正文
5. 结论
6. 参考文献
7. 致谢
8. 附录

### 毕业设计（论文）文本打印格式（参照国家标准 GB/T 7713.1-2006）

* （一）毕业设计（论文）一律使用 A4 纸单面打印。
* （三）
  * 中文标题采用小二号黑体字，
  * 中文摘要、关键词采用小四号宋体字，
  * 外文标题采用小二号 Times New Roman 字体，
  * 外文摘要、关键词采用小四号 Times New Roman 字体。
* （四）
  * 目录采用四号宋体字，
  * 分章节的毕业设计（论文）目录中每章题目用四号黑体字，
  * 每节题目用四号宋体字，
  * 并注明各章节起始页码，
  * 题目和页码用“……”相连

```
理工农医类建议格式示例：
目录
第 1 章 XXXX┈┈┈┈┈┈ 1
第 1．1 节 XXXX ┈┈┈┈ 2
```

* （五）毕业设计（论文）正文版式
  * 1
    * 正文内容中文采用宋体字，
    * 外文采用 Times New Roman 字体，
    * 标题加粗，
    * 章节题目采用小三号字，
    * 正文采用小四号字，
    * 章节题目、每节题目与正文之间空一个标准行
  * 2 页面设置
    * 页边距上 3.3cm，下 2.7cm，左 2.5cm，右 2.5cm
    * 左侧装订线 0.5cm
    * 行距为 1.5 倍，段前、段后均为 0 磅，
    * 段落首行缩进 2 个字符
  * 3 页眉页脚
    * 页眉距离 2.6cm，页脚距离 2cm
    * 页眉居中，以小五号宋体字键入“苏州大学本科生毕业设计（论文）”，带横线，
    * 页脚插入页码，居中
  * 4 页码
    * 封面、独创性声明以及使用授权声明不设置页码
    * 摘要和目录部分采用小写罗马数字连续编排，如 i、ii、iii、…；
    * 正文开始采用阿拉伯数字编排页码，数字左右加连字符，如-1-、-2-、-3-、…；
    * 参考文献、附录、致谢等接正文部分连续编排页码，格式要求与正文部分相同。
  * 5 外文翻译、文献综述或读书报告格式参照上述对论文正文的要求提交，不需要编排页码
* （六）毕业设计（论文）的参考文献
  * 1，2，3，4
  * 5 参照国家标准 GB/T 7714-2015

## 排版格式

* 1. 摘要设置
  * 中文标题采用小二号黑体字，
  * 中文摘要、关键词采用小四号宋体字，
  * 外文标题采用小二号 Times New Roman 字体，
  * 外文摘要、关键词采用小四号 Times New Roman 字体。
* 2. 目录设置
  * 目录标题：四号宋体，居中
  * 目录一级标题：四号黑体，行距 22 磅
  * 目录二级标题：四号宋体，行距 22 磅，
  * 题目和页码用“……”相连
* 3. 论文正文设置
  * 外文字体一律使用 Times New Roman
  * 论文大标题：二号黑体，居中，上空 1.5 行，下空 1 行
  * 正文一级标题：小三号黑体，居中，上下各空一行
  * 正文二级标题：四号黑体，顶格，上下各空一行
  * 正文三级标题：小四号黑体，缩进两字
  * 正文四级标题：小四号宋体，缩进两字，正文接后
  * 正文字体：小四号宋体，行距为 1.5 倍，段前、段后均为 0 磅，段落首行缩进 2 个字符
  * 表格及插图标题：五号黑体，居中
  * 特殊章节标题：小三号黑体，居中，上下各空一行
* 4. 页面设置
    * 页边距上 3.3cm，下 2.7cm，左 2.5cm，右 2.5cm
    * 左侧装订线 0.5cm
    * 行距为 1.5 倍，段前、段后均为 0 磅
    * 段落首行缩进 2 个字符
* 5. 页眉页脚
    * 页眉距离 2.6cm，页脚距离 2cm
    * 页眉居中，以小五号宋体字键入“苏州大学本科生毕业设计（论文）”，带横线，横线长度与“苏州大学本科生毕业设计（论文）”长度相同
    * 页脚插入页码，居中
* 6. 页码
    * 封面、独创性声明以及使用授权声明不设置页码
    * 摘要和目录部分采用小写罗马数字连续编排，如 i、ii、iii、…；
    * 正文开始采用阿拉伯数字编排页码，数字左右加连字符，如-1-、-2-、-3-、…；
    * 参考文献、附录、致谢等接正文部分连续编排页码，格式要求与正文部分相同。
* 7. 外文翻译、文献综述或读书报告格式参照上述对论文正文的要求提交，不需要编排页码
* 8. 插图索引：对所有插图索引。标题为“插图索引”，用黑体小三号字，段前40pt，段后20pt，行距20pt。内容部分中文采用宋体小四号字，英文采用Times New Roman小四号字，行距用固定值20pt，段前6pt，段后0pt。
* 9. 表格索引：对所有表格索引。标题为“表格索引”，用黑体小三号字，段前40pt，段后20pt，行距20pt。内容部分中文采用宋体小四号字，英文采用Times New Roman小四号字，行距用固定值20pt，段前6pt，段后0pt。

## 进阶

* 如果有以下情况：
    * 对`overleaf.com`网站在线编译的速度有要求
    * 对文章内容隐私性有要求
    * 梯子不快的同学，可以考虑在内网的强悍服务器上搭建一个[本地的Overleaf平台](https://github.com/overleaf/overleaf)，现已支持docker


## 相关仓库

- [sudathesis](https://github.com/huhamhire/sudathesis) — LaTeX template for bachelor's thesis in Soochow University
- [SUDA-Latex](https://github.com/hinesboy/SUDA-Latex) — 苏州大学-硕士毕业大论文-Latex模版（附安装使用说明）
- [Overleaf](https://github.com/overleaf/overleaf) - A web-based collaborative LaTeX editor

## 维护者

[@shadowofgost](https://github.com/shadowofgost)。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/shadowofgost/Sudathesis-Bachelor-Template/issues) 或者提交一个 Pull Request。

如果有问题可以到[GitHub Issues](https://github.com/tuna/thuthesis/issues)

Sudathesis-Bachelor-Template 遵循 [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) 行为规范。


## 使用许可

[LPPL 1.3c](LICENSE) © shadowofgost
