# 1.引言
第一次使用Markdown来写文章，花一个小时简单学习了一下Markdown的语法，顺便写个文章总结一下，方便以后查阅。
# 2.常用语法
## 标题
在标题前添加特定数量的井号‘#’，一个井号是一级标题，两个是二级标题，以此类推。为了兼容性考虑，井号和标题之间添加一个空格。
## 段落
段落之间用空白行隔开。
## 换行
推荐使用的换行语法是在具体的末尾添加两个或更多的空格，然后按下回车。
## 强调
**粗体**的最佳实践是在需要加粗的文本两侧各加两个星号。例如：/**粗体**
*斜体*的最佳实践是在文本两个添加一个星号。
***同时粗体和斜体***是添加三个星号，是不是很简单。
## 引用
> 这里是引用块，引用块的语法是在要引用的段落前添加一个 > 符号

> 多段的引用需要在两个段落间的空白行添加一个 > 符号。
> '>
> 就像这样。

> 嵌套块引用，在要嵌套的段落前添加一个 >> 符号。
> > 这就是嵌套引用。

## 列表
有序列表
1. 每一项都以数字紧跟着英文句点开始。
6. 第一项必须是数字1。
9. 后面的数字是几无所谓。

无序列表
- 无序列表推荐语法是在每项前添加

在列表中保留其他元素，需要将该元素缩进四个空格或一个制表符。
- 这是一条列表
  > 这是列表中的引用。
## 代码
要将一段话中的`一个单词或短语`表示为代码，只需要用反引号 ` 将其包裹。反引号在键盘上的位置位于esc下方。

如果希望``代码单词的内部包含反引号 ` ``，则用双反引号 `` 将代码内容包裹。

```
Markdown中允许将每行缩进一个制表符来创建代码块。
但是简书中是使用两个制表符来创建代码块。
另外，可以使用三个反引号 ``` 来创建受保护的代码块。
```
## 分割线
要创建分割线，在单独一行使用三个或更多的星号 *** 、破折号 --- 或者下划线___
并且最好在分割线的前后均添加空白行，这是为了兼容性考虑。

***

## 链接
[链接文本](https://www.jianshu.com/writer#/notebooks/53141807/notes/105518790/preview "这是一个链接标签")放在中括号 [] 内，链接地址放在后面的括号中，格式如下：
`[链接文本](链接地址 "链接标签")`
用尖括号 <> 将网址或者email变成链接。`<www.baidu.com>`

在[方括号] [1]内添加反引号可以将链接表示为代码：[`代码中的链接`](https://www.jianshu.com/writer#/notebooks/53141807/notes/105518790/preview )



[1]: <https://www.jianshu.com/writer#/notebooks/53141807/notes/105518790/preview>