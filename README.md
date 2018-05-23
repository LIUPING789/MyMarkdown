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
1）使用 <font color="red">**=**</font> 和 <font color ="red">**-**</font> 标记 <font color="red">一级</font> 和<font color = "red">二级</font> 标题。 

<font color ="red">示例md代码:</font>

```
一级标题
=
二级标题
-
```
