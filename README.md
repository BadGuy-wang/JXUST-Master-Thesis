# 江西理工大学硕士研究生毕业论文LaTex模版
[![CTAN](https://img.shields.io/ctan/v/gbt7714.svg)](https://ctan.org/pkg/gbt7714)
[![GitHub release](https://img.shields.io/github/release/CTeX-org/gbt7714-bibtex-style/all.svg)](https://github.com/CTeX-org/gbt7714-bibtex-style/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/CTeX-org/gbt7714-bibtex-style/latest.svg)](https://github.com/CTeX-org/gbt7714-bibtex-style/commits/master)
![这是图片](https://github.com/BadGuy-wang/JUST-master-student-thesis-template/blob/main/JXUST.png "JXUST")

# 关于封面

封面格式较为复杂，细节难以调控，所以这里直接使用学校word模版。只需要在“江西理工大学硕士论文封面.doc”中填好个人论文信息，然后导出为pdf文件，放在同一个目录下。

# 关于LaTex

本项目使用XeLaTex编译，LaTex具体使用语法既技巧课参考刘海洋老师的书《LaTex入门》其中有详细介绍。编译环境可使用在线编译环境免除安装烦恼`https://www.overleaf.com/`

# 关于格式  

本文目录部分使用小四号字体，两倍行距。一级标题使用三号黑体加粗，二级标题使用四号黑体加粗。正文部分使用四号宋体，行间距为1.25倍，文献引用格式使用是`GB/T 7714 2015`版本（将gbt7714-numerical.bst与.tex源文件放在同一目录下即可）。

由于不同导师，不同学院，不同年份情况下格式均会有所变化，格式没有同意标准。目前版本是参照“江西理工大学论文硕士格式模板.doc”的内容设定，在部分细节上有所不同，总体相近。

# 后期更新

后面会继续修订部分细节，如有错误地方请多多指正。

# 注

1、latex图片的标题默认带冒号--“：”，插入以下语句即可取消冒号。

    \usepackage{caption}
    \DeclareCaptionLabelSeparator{twospace}{\ ~} 
    \captionsetup{labelsep=twospace}
    
2、由于`GB/T 7714 2015`参考文献作者姓名全部大写，不被大多数人接受，这里以将`.bst`文件中的规则修改。（原始文件中`#1 'uppercase.name :=`，将其改为`#0 'uppercase.name :=`）

3、关于Visio如何保存图片为`.pdf`格式，[请参考此博客](https://blog.csdn.net/u014686356/article/details/87985796 "Visio转PDF")

4、开题报告模版[点击此处](https://github.com/BadGuy-wang/JUST-master-student-thesis-template "开题报告模版")

5、如有问题可以在issue中提交问题，或者邮箱handsomewhuai@gmail.com
