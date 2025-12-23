# learn-Markdown

本文基于markdown的相关文档整理：

## Markdown基本语法:

Markdown常见的基本语法主要分为以下几个方面：标题、段落、换行、强调、引用、列表、代码、分割线、链接、图片、转义字符等等。

### 标题语法：

在创建标题时，需要在单词或者短语前面加上井号（#）。# 号的数量代表着标题的级别。

代码：

    # heading level1
    ## heading level2
    ### heading level3
    #### heading level4

格式：

    ># heading level1
    >## heading level2
    >### heading level3
    >#### heading level4


### 段落语法：

要创建段落时，请使用空白行将一行或多行文本进行分割。

代码：

    I like using markdown.

    I really like using markdown.

格式：

I like using markdown.

I really like using markdown.


### 换行语法：

换行语法只需要在需要换行的那一行的行末尾添加两个或多个空格，之后按回车键即可创建一个换行。
(部分编辑器不支持结尾加两个空格进行换行，可以在换行末尾加上<br>即可换行。)

代码：

    this is the first line.<br>
    and this is the second markdown.<br>

格式：

this is the first line.<br>
and this is the second markdown.<br>  


### 强调语法：

常见的强调格式有粗体与斜体两种形式：

**粗体**

要加粗文本，可以在单词或者短语的前后各添加两个星号，或者下划线。如需加粗一个单词或者短语的中间部分表示强调的话，请在需要加粗的部分两侧各自添加两个星号。

代码：

    I just love **bold text**.
    I just love __bold text__.

格式：

I just love **bold text**.
I just love __bold text__.

*斜体*

要用斜体显示文本时，请在单词或者短语前后各自添加一个星号或者下划线。要斜体突出单词的中间部分，请在字母前后各添加一个星号，中间不要带空格。

代码：

    Italicized text is the *cat is meow*.
    A*cat*meoew.

格式：

Italicized text is the *cat is meow*.
A*cat*meoew.

粗体和斜体

要同时使用斜体突出显示文本，请在单词或者短语的前后各自添加三个星号或者下划线。要加粗并用斜体显示单词或者短语的中间部分，请在要突出显示的部分前后各添加三个星号，中间不要带空格。

代码：

    This text is ***really important***.
    This text is *__really important__*.

格式：

This text is ***really important***.
This text is *__really important__*.


### 引用语法：

要创建一个引用时，请在需要引用的段落前添加一个>符号。

代码：

    >Dorothy followed her through many of beautiful rooms in her castle.

格式：

>Dorothy followed her through many of beautiful rooms in her castle.

嵌套块引用：

块引用可以嵌套。在要嵌套的段落前的添加一个>>符号。

代码：

    >Dorithy followed her through many of the beautiful rooms in her castle.
    >
    >>The witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.


格式：

>Dorithy followed her through many of the beautiful rooms in her castle.
>
>>The witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood. 


### 列表语法：

在Markdown中，可以将多个条目组织成有序或者无序的列表。

有序列表：

要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学顺序排列，但是列表应当以数字1起始。

代码：

    1. first item
    2. second item
    3. third item
    4. fourth item

格式：

1. first item
2. second item
3. third item
4. fourth item

无序列表：

要创建无序列表，请在每个列表项之前添加- * 或者 + 。缩进一个或多个列表项可创建嵌套列表。

代码：

    - first item
    - second item
    - third item
    - fourth item

    * first item
    * second item
    * third item
    * fourth item

格式：

- first item
- second item
- third item
- fourth item

* first item
* second item
* third item
* fourth item

### 代码语法：

要将单词或短语表示为代码，请将其包裹在反引号`` ` `` 中。

转义反引号：

如果你要表示为代码的单词或者短语中包含一个或多个反引号，则可以通过将单词或短语包裹在双反引号（`` ` ``）中。

代码块：

要创建代码块，请将代码块的每一行至少缩进四个空格或者一个制表符。

### 分割线语法：

要创建分割线，请在单独一行上使用三个或多个 * 号，（或-, _）

### 链接语法：

链接文本放在中括号内，链接地址放在后面的括号中，链接title可选。

超链接markdown语法代码：

[链接](https://vscode.dev/github/analys-world/learn-Markdown/blob/main/README.md#L204)

给链接增加显示：

链接title是当鼠标悬停在链接上时会出现的文字，这个title是可选的，它放在圆括号中链接地址的后面，跟链接地址之间以空格分隔。

[链接](https://vscode.dev/github/analys-world/learn-Markdown/blob/main/README.md#L204 "链接 ")

网址和email地址：

使用尖括号可以很方便的把url或者email变成可点击的链接。

<baidu.com>

带格式化的链接：

强调链接：在链接语法前后增加星号。要将链接表示为代码，请在方括号中添加反引号。

引用类型的链接：



### 图片语法：

要添加图像，请使用感叹号（！），然后在方括号内增加替代文本，图片链接放在圆括号内，括号里的链接后可以增加一个可选的图片标题文本。



### 转义字符语法：

### 内嵌HTML标签：



## 扩展语法：

