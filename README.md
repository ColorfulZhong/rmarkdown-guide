---
editor_options: 
  markdown: 
    wrap: 72
---

# R Markdown 指南

《R Markdown 指南》是第一本系统介绍 R Markdown 技术的中文图书。

## 为什么要写这样一本书？

R Markdown 是一个生产力工具。她基于流行的 R 语言，通过
**knitr**，**rmarkdown**， **bookdown**，**tinytex** 等一系列 R
软件包实现其功能。自 2012 年初 knitr 发布 以来，R Markdown
技术不断发展和丰富，已经成为当前制作动态文档、演示文稿、PDF
文档、建设网站，以及著书的主流工具之一。

基于 R Markdown 技术实现的动态文档，可以自行将文档内包含的代码编译执行，
并将运行的结果（如绘图、控制台输出、LaTeX 数学公式、图片、源代码等）动态
整合到最终文档中，最大程度上实现了技术文档的自动化。

与另一个流行的功能密切相关的生产力工具 Jupyter Notebook 相比，R Markdown
是 R 语言用户的第一选项。且R Markdown 在 RStudio
中具有原生支持，这大大降低了 学习的难度，提高了日常使用 R Markdown
的效率。另外，虽然R Markdown 基于 R 语言实现，但是她也支持在文档中使用
Python、Bash 等其它编程语言。

由于 R Markdown
具有上述种种优势，使其成为一种一旦掌握就能受益终身的通用技能。
在学校，适合写作业，在职场，适合做工作汇报，在学术届，适合开展可重复研究等等。

现在网络上关于 R Markdown
的教程很多，但是对于一本图书而言，其系统、全面的优势是不可替代的。
因此，在外文图书市场上有多部 R Markdown 技术书籍。其中，仅 Chapman &
Hall 出版社（<https://www.crcpress.com/>） 已经先后出版了"bookdown:
Authoring Books and Technical Documents with R Markdown"、 "R Markdown
Cookbook"，"blogdown: Creating Websites with R Markdown"、"R Markdown:
The Definitive Guide"等多部以 R Markdown
技术为主要介绍对象的书籍。除此之外， 基于 R Markdown
进行技术类图书写作也成为日益流行的创作样式，包括本书以及上述书籍
在内都是依托 R Markdown 技术创建的。R 语言的经典教材和书籍（如"R for
Data
Science"等）也都是如此（<https://www.bookdown.org/>）。然而，在中文图书市场上，
尚没有任何一部系统介绍 R Markdown 的图书。

于是，我们就决定写了这本书。

## 本书是怎么写出来的？

本书是在谢益辉（[\@yihui](https://github.com/yihui)）
组织下，由王祎帆、闫求识、
高春辉、庄亮亮等共同创作完成的。书籍的创作主要参考了谢益辉所著的《R
Markdown Cookbook》 和《R Markdown: The Definitive
Guide》等资料。但是书籍创作过程并非严格的编译，
而是结合了作者在这一领域的经验和认识。

主要作者的基本信息如下（按加入项目的先后排序）：

-   王祎帆：中国人民大学统计学院博士生，统计之都成员， 《R Graphics
    Cookbook》 的译者；
-   闫求识：范德堡大学数据科学研究生；
-   高春辉：华中农业大学资源与环境学院青年教师；
-   庄亮亮：温州大学应用统计专业研究生，微信公众号"庄闪闪的 R
    语言手册"主编；
-   杨晓龙：东京大学政治科学的本科三年级。

如果你对参与到该项目中有兴趣，请先看[贡献者指南](Start.md)。

除此之外，你还可以在阅读本书在线版本的时候留下你的评论，或者提交一个
GitHub Issue 或者 Pull request 来帮助我们更好的完成这本书。

## 本书的创作理念是什么？

本书的目的是让更多人受益于 R Markdown
技术。在写作的过程中，我们尽可能系统、全面的介绍 R Markdown
技术，并将最佳实践呈现给读者。

## 本书主要有哪些内容？

目前本书主要有五大块主体内容：

1.  R Markdown 基础知识
2.  R Markdown 常用输出格式
3.  R Markdown 操作技巧
4.  R Markdown 进阶操作
5.  使用 R Markdown 开展工作

## 本书预计于什么时候出版？

本书目前仍处于草创阶段，目前仅有网上在线版可以访问。不过，我们同时也希望寻求专业的出版机构合作，在未来推出本书的印刷版本实体书。
