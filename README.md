<center>
<br>
<font color="#3C7E9F" style="font-size:32px"> Markdown 基础语法</font>
  
  ![](https://ws3.sinaimg.cn/large/006tKfTcgy1frl3wwlw7mj30cv0a90su.jpg)
  
<br>
</center>

### 执行概要

<font color="#3C7E9F">**内容：**</font>
  
1. Markdown 是什么？
2. Markdown 是谁创造的？
3. 为什么要使用Markdown?
4. Markdown怎么使用？
5. Markdown 都有哪些人在用？
6. 尝试一下Markdown的使用！
7. Markdown 进阶语法！
<br/>

<font color="#3C7E9F">**学习目标**</b></font>

通过学习，能对Markdown语法有个比较全面的认知，对日常工作写作排版尽量放弃Word、txt等文本工具，改直接用Markdown语言写文档。

<font color="#3C7E9F">**学习思路**</font> 

1. 一开始，先记住 `# 这是标题`、`## 这是二级标题`、`### 这是三级标题`、...这时候你写一般小文章会开始感觉 MD 不错。
2. 然后，你发现标题不适合做列表，记住了用`1. 第一点`、`- 这一点`来列表超级方便。
3. 好吧，写作总要有些重点吧，`**加粗**`、`*斜体*`、`~~删除线~~`开始派上用场了。这时你基本不会打开 Word 那样的笨重软件了。
4. 如果你不幸是码农：  
 `\`这是单行代码\``


//这是代码段，四个空格或一个制表符缩进
        int i;

    > 这是引用
    
      
5.你越来越喜欢，自然会去查查维基（Markdown）还有什么语法，加上多用，很快就基本掌握了。MD 还有表格、锚、注脚、贴图等。强烈推荐 Mou，按 ⌘＋R 可以快速查看语法。

6.慢慢，你会发现，总有小「bugs」，如列表内无法内嵌代码段。上网查查，你开始理解 MD 的缩进内嵌机制等高级隐形内容，这样你就 Master 了！

以下是 Mou 下面的效果，多漂亮：

![](https://ws1.sinaimg.cn/large/006tKfTcgy1frl4s74fd9j31ki1iwn44.jpg)

#### 正文

#### 一、Markdown是什么？
Markdwon 是一种轻量级<font color="red"> **标记语言** </font>，它以纯文本形式（易读、易写、易更改）编写文档，并最终以HTLM格式发布。Markdown也可以理解为将以 MARKDOWN语法编写的语言转换成HTML内容的工具。

#### 二、Markdown是谁创造的？

它是由 [**Aaron Swartz**](www.aaronsw.com/) 和 [**John Gruber**](https://baike.baidu.com/item/John Gruber/18550453?fr=aladdin) 共同设计， Aaron Swartz 就是那位（2013年1月11日）自杀，有着开挂一般人生经历的程序员。 维基百科对他的[**介绍**](https://zh.wikipedia.org/wiki/亚伦·斯沃茨)是：**软件工程师**、**作家**、**政治组织者**、**互联网活动家**、**维基百科人**。

他有着足以让你跪拜的人生经历。

-   **14岁**参与RSS 1.0规格标准制订。
-   **2004年**入读斯坦福大学，之后退学。
-   **2005年**创建 [Infogami](http://www.infogami.org/),之后与[Reddit](https://www.reddit.com/)合并成为其合伙人。
-   **2010年**创立示进会（Demand Preogress）,积极参与禁止网络盗版法案（SOPA）活动，最终该提案被撤回。
-   **2011年7月19日**,因被控从MIT和JSTOR下载480万篇学术论文并以免费形式上传于网络被捕。
-   **2013年1月**自杀身亡。

![](https://ws2.sinaimg.cn/large/006tKfTcgy1frl7pl8xg0j30b50fhgm1.jpg)

            
#### 三、为什么要使用Markdown?
-   它是易读（看起来舒服😌）、易写（语法简单）、易更改（纯文本）。处处体现着极简主义的影子。
-   兼容HTML,可以转换为HTML格式发布。
-   跨平台使用。
-   越来越多的网站支持Markdown.
-   更方便清晰的组织你的电子邮件。（Markdown-here,Airmail）。
-   **摆脱Word,txt！！！**

#### 四、Markdown怎么使用？
<font color="red">如果不算扩展，Markdown的语法绝对简单到让你爱不释手！</font>

Markdown语法分为如下几大部分：

▸ **标题**

▸ **段落**

▸ **区块引用**

▸ **代码区块**

▸ **强调**

▸ **列表**

▸ **分割线**

▸ **链接**

▸ **图片**

▸ **反斜杠**

▸ **符号**

▸ **表格**

▸ **流程图**

##### 4.1 标题 
两种形式
1）使用 `=` 和 `-` 标记 `一级` 和`二级` 标题。 

<font color ="red">示例md代码:</font>

```
一级标题
=
二级标题
-
```

示例效果：

![](https://ws1.sinaimg.cn/large/006tKfTcgy1frl8xwwftpj30ap02u742.jpg)

2）使用 <font color ="red">**#**</font>,可以表示 <font color="red">**1-6级**</font> 标题。
  
 <font color ="red">示例md代码:</font>

```
# 第一级标题 `<h1>` 
## 第二级标题 `<h2>` 
### 第三级标题 `<h3>` 
#### 第二四级标题 `<h4>` 
##### 第五级标题 `<h5>` 
###### 第六级标题 `<h6>` 
```
示例效果：

![](https://ws3.sinaimg.cn/large/006tKfTcgy1frl8037731j30d705y0sk.jpg)

##### 4.2 段落
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用**两个以上空格加上回车**（引用中换行省略回车）

##### 4.3 区块引用
在段落的每行或者只在第一行使用符号 <font color="red">**>**</font> ,还可使用多个嵌套引用，如：

 <font color ="red">示例md代码:</font>
 
 ``` 
> 区块引用
> > 嵌套引用
> > >三嵌套引用
> > > > 四嵌套引用
```
示例效果：

![](https://ws3.sinaimg.cn/large/006tKfTcgy1frl905dyryj30ax054glf.jpg)

##### 4.4代码区块
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如普通段落：

 <font color ="red">示例md代码:</font>
 
 ```
 fun main(args: Array<String>) {
    println("Hello World!")

    println("sum = ${sum(34, 67)}")
    println("sum = ${sum(34, 67)}")
    println("sum = ${sum(34, 6, 57, 34)}")

    printSum(237, 57)
    printSum(234, 567, 8)
    vars(1, 4, 6, 78, 0, 6, 9, 8)


    val sumLambda: (Int, Int) -> Int = { x, y -> x + y }
    println("sumLambda = ${sumLambda(3, 6)}")


//    if (args.size < 2) {
//        println("Two integers expected")
//        return
//    }
    testFor()


    val a: Int = 1000
    println(a === a)//true 值相等，对象地址相等

    //经过了装箱，创建了两个不同的对象
    val boxedA: Int? = a
    val anotherBoxedA: Int? = a

    //虽然经过了装箱，但是值是相等的，都是10000
    println(boxedA === anotherBoxedA) //  false，值相等，对象地址不一样
    println(boxedA == anotherBoxedA) // true，值相等
}
 ```
 
 <font color="red"> 示例效果：</font> 
 
 ![](https://ws2.sinaimg.cn/large/006tKfTcgy1frl98o1o2jj30es0653yk.jpg)
 
 **注意⚠️：需要和普通段落之间存在空行！**
 #####4.5 强调
在强调内容两侧分别加上 <font color="red"><b>*</b></font> 或者 <font color="red"><b> - </b></font>,如：

 <font color ="red">示例md代码:</font>
 
 ```
 *斜体* ，_斜体_
 **加粗**，__粗体__
 ```
  <font color ="red">示例效果</font>

 ![](https://ws4.sinaimg.cn/large/006tKfTcgy1frl99i5iejj30d7024741.jpg)
 
 
#####4.6 列表 （有序，无序）
使用 <font color="red">**.** </font>、<font color="red">**+**</font>、或<font color="red"> **-** </font> 标记无序列表，如：

 <font color ="red">示例md代码:</font>
 
    
    
    -   第一项
    +   第二项
    -   第三项
    +   第四项
    -   第五项
    +   第六项
    
    <font color="red">示例效果:</font> 
    
    #####4.7 分割线 
分割线最常使用就是三个或以上的 <font color="red"> `*` </font> ，<font color="red"> `====== `</font>还可以使用 <font color="red"> `- `</font>和 <font color="red">`_ `</font>。


 <font color ="red">示例md代码:</font>
 
``` 
***
---
_____ 
======
```

<font color ="red">示例效果:</font>

![](media/15269527485461/15269723447956.jpg)



#####4.8链接
链接可以由两种形式生成，<font color="red">**行内式**</font> 和 <font color="red">**参考式**</font>。

**行内式：**

 <font color ="red">示例md代码:</font>
 
```
[GitHub](http://github.com)
自动生成连接  <http://www.github.com/>
```

<font color ="red">示例效果:</font>
![](media/15269527485461/15269732553813.jpg)


**参考试：**

```
[GitHub][1]
[1]:http://github.com
自动生成连接  <http://www.github.com/>
```
<font color ="red">示例效果:</font>
![](media/15269527485461/15269734287099.jpg)

**注意：**上述的[1]:http://github.com不出现在区块中。


#####4.9 图片
添加图片形式和链接相似，只需要在链接的基础上前方加一个 <font color="red"> **！**</font>号。

 <font color ="red">示例md代码:</font>

```
![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)
格式: ![Alt Text](url)
```
![GitHub set up](http://zh.mweb.im/asset/img/set-up-git.gif)

##### 4.10 反斜杠  '\'
相当于<font color="red">**反转义**</font>作用。使符号成为普通符号。

#####4.11 符号 ``
起到标记作用，如标签：

`Ctrl+A` 、`Ctrl+C`、`Ctrl+V`

<br>

#####4.12 表格 

 <font color ="red">示例md代码:</font>
     
```txt
第一格表头 | 第二格表头
---------| -------------
内容单元格 第一列第一格 | 内容单元格第二列第一格
内容单元格 第一列第二格 多加文字 | 内容单元格第二列第二格
内容单元格 第一列第三格 多加文字 | 内容单元格第二列第三格
内容单元格 第一列第四格 多加文字 | 内容单元格第二列第四格
```

<font color ="red">示例效果:</font>
![](media/15269527485461/15269744915851.jpg)


<br>

#####4.12 流程图

##### 示例

```flow
st=>start: Start:>https://www.jpjbp.com/
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```

##### 更多语法参考：[流程图语法参考](http://adrai.github.io/flowchart.js/)

####五、Markdown都哪些人在用？
Markdown 的使用作者：

- Github
- 简书
- StackOverFlow
- Apollo
- Moodle
- Reddit
- CSDN
- 等等

####六、尝试一下Markdown的使用！

+ Chrome下的插件诸如stackedit与markdown-here等非常方便，也不用担心平台受限。
+ 在线的dillinger.io评价也不错
+ Windowns下的MarkdownPad也用过，不过免费版的体验不是很好
+ Mac下的Mou是国人贡献的，口碑很好。
+ Linux下的ReText不错。


## TOC

Markdown 语法：

```
[TOC]
```

效果如下：

[TOC]

    
