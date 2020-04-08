# Update List

## Beta.V0.9.2 - 2020.03.14

### Fixed

* 重构宏包代码，重排了部分文本。

* 取消等宽字体的使用，一律使用 Times New Roman，并稍微修改了代码环境；

* 现在使用 `cite{}` 实现上标引用参考文献；

* 现在使用 `subcaption` 宏包来插入并列子图，而 `subfigure` 宏包好久没更新了；

* 一级编号列表环境的序号改变了样式；

* 修改章节标题间距、缩短插图后的间距，列表环境现在改为正常的行间距；

* 章、节、小节标题一律使用加粗的宋体，浮动体标签和数学定理内容改为宋体；

* “诚信申明”改为“诚信声明”；修正了“前言”的拼写错误；

* 在“结论”这一章标题中间加上了一个全角空格；

* 简化了“符号说明”的代码；

### Deleted

* 删除了在上个版本在摘要部分加入的作者及导师信息；

* 删除参考文献的文件 bibliography.tex，简化原来的代码并移动至主文件；

* 删除了一些宏包；

### Added

* 宏包载入多了选项：`TextBlack` 用于将超链接全部设置为黑色，`LessTOC` 将会取消将“第一章”之前的所有内容编目（这与《规范》的示例相同）。

## Beta.v0.9.1 - 2020.02.06

### Fixed

* 正文字号修正

* 摘要同页排版的环境（ `abstract*` 与 `abstracten*` ），关键词的代码( `\keywords` 和 `\keywordsen` ）和格式

* 行距调整至近似 Microsoft Word 中 22 磅

* 修改节标题的前间距、小节标题的前后间距

* 代码环境，关键字增设粗体、环境背景颜色减弱至浅灰色的10%

* 修改目录部分的缩进

* 改用数字带圈圈的脚注

* 修改列表环境的间距

* 删除了部分数学类的环境

* 更改了hyperref宏包设置，凸显超链接以便于查看

### Added

* 摘要部分的作者（ `\author` 和 `\authoren` ）、导师（ `\thesupervisor` 和 `\thesupervisoren` ）等信息

* 增加“设计图纸”编入目录的命令 `\designfig`

* 增加了化学类的宏包、算法的宏包

## Beta.v0.9.0 - 2020.01.23

The first version.Hello World!