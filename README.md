# 江西理工大学硕士研究生开题报告与毕业论文LaTex模版
[![CTAN](https://img.shields.io/ctan/v/gbt7714.svg)](https://ctan.org/pkg/gbt7714)
[![GitHub release](https://img.shields.io/github/release/CTeX-org/gbt7714-bibtex-style/all.svg)](https://github.com/CTeX-org/gbt7714-bibtex-style/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/CTeX-org/gbt7714-bibtex-style/latest.svg)](https://github.com/CTeX-org/gbt7714-bibtex-style/commits/master)
![这是图片](/JXUST.png "JXUST")

# 关于封面

只需要在`thesis_cover.docx`填写个人信息，再另存为`thesis_cover.pdf`插入即可。  


# 关于LaTex

本项目使用XeLaTex编译，LaTex具体使用语法既技巧课参考刘海洋老师的书《LaTex入门》其中有详细介绍。编译环境可使用在线编译环境免除安装烦恼`https://www.overleaf.com/`

# 关于格式  

本文目录部分使用四号字体，两倍行距。一级标题使用三号黑体加粗，二级标题使用四号黑体加粗。正文部分使用四号宋体，行间距为1.25倍，文献引用格式使用是`GB/T 7714 2015`版本（将gbt7714-numerical.bst与.tex源文件放在同一目录下即可）。

鉴于目前学校没有固定格式，当前格式是综合了多种不同标准而来 

# 后期更新

后面会继续更新毕业论文模版，如有错误地方请多多指正。

# 2021.1.20更新

1、latex图片的标题默认带冒号--“：”，插入以下语句即可取消冒号。

    \usepackage{caption}
    \DeclareCaptionLabelSeparator{twospace}{\ ~} 
    \captionsetup{labelsep=twospace}
    
2、由于`GB/T 7714 2015`参考文献作者姓名全部大写，不被大多数人接受，这里以将`.bst`文件中的规则修改。（原始文件中`#1 'uppercase.name :=`，将其改为`#0 'uppercase.name :=`）

3、关于Visio如何保存图片为`.pdf`格式，[请参考此博客](https://blog.csdn.net/u014686356/article/details/87985796 "Visio转PDF")

