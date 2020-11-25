# 第13组 看画识作者

## 前言

**项目名称：**AI艺术鉴赏，看画猜作者

**项目简介：**“抽象是艺术史上的自然进步，然而算法捕捉到了这一点”。很多人认为理工男普遍缺乏艺术细菌，不懂欣赏艺术的抽象美，然后现在理工男设计的AI算法已经能够理解艺术。罗格斯大学的艺术与人工智能实验室制作出一套名为CAN（创造性对抗网络）的AI系统，CAN向我们证明人工智能可以理解艺术发展脉络和学习路径，所以软件的任务就是训练模型，识别名画的作者。数据集来自49位大师的作品，乔托·迪·邦多纳、毕加索、梵高、安德烈·鲁勃廖夫、提香·韦切利奥等。我们团队将会做成WEB版软件，由用户上传名画，而由系统返回该名画的作者信息。

## NABCD模型分析

**1）N（Need需求）**

随着时代的发展，人们不再单一地享受物质生活，而是追求精神生活，因此人们希望提高艺术品位，能够更好地理解与欣赏艺术。除此之外，对一些理工男、理工女来说，他们希望能够更加了解艺术，从而打破专业壁垒。大家都想提升自己的艺术鉴赏水平，可是世界名画种类繁多，名家更是数不胜数，面对一幅画，连它的作者都不知道，这无疑对人们的分析造成了影响。

我们也询问了身边的同学，发现他们都想提升自己的艺术鉴赏水平，并且除了梵高的向日葵等耳熟能详的作品外，不能辨别其他名画的作者。因此我们小组希望做出一款软件，帮助人们识别名画的作者，从而帮助他们更好地理解、欣赏这幅名画。

**2）A（Approach做法）**

1.在上学期学习了WEB框架设计的训练，掌握了JS、CSS等技术，将会用在设计网页，开发前后端方面；

2.这一学期学习了深度学习的技术，我们将用AI研习社和不同网站的数据进行不断的训练，然后提高我们的识别率；

3.会遇到深度学习以及网页构建方面的问题，但目前已经有成熟的技术可以供我们参考，我们将会在项目编写中不断进行学习和钻研。

4.之前没有学习Python的经验，这是我们组的重难点之一，需要我们从头开始学起。

除此之外，我们的项目还有以下特色：

1）网页会提供一部分画作，用户也可以上传一些画作，分析是哪一位大师的著作；

2）用户也可以上传自己的涂鸦画，看看与哪位大师的风格最接近；

**3）B（Benefit好处）**

从实际使用层面来说，我们能根据画作给出作者，能够满足用户想了解画作作者的需求。例如，有些时候我们看到一幅画，由于是图片的形式，我们难以检索出画作的作者。而我们的产品就是为了解决这样的需求而诞生，通过输入画作的图片信息从而给出画作的作者信息。能够帮助用户更好的了解艺术，加深对于世界名画的理解，帮助用户更好的理解艺术，满足用户的好奇心。从宏观来讲，对于艺术的普及也带来了一定的推动作用，对于提高全民的艺术素养贡献着我们自己的一份力量。

**4）C（Competitors竞争）**

对于许多搜索引擎自带识图搜索功能：比如百度的拍照搜索，它的优点是具有很全很广泛的识别功能，但缺点就是不够专业化。例如识别蒙拉丽莎的微笑，百度识图搜索会给出所有和图片信息有关的内容，但是却无法第一时间告诉用户名画的作者是达芬奇，以及达芬奇的相关简介。但是对于许多用户来说，他们早已习惯了百度搜索识图的使用，如何吸引这类用户改变习惯，结合一个新的软件（WEB版）来做到专业化的名画识别是一个问题。

对于一些具有名画识别功能的微信小程序：比如名画识别小程序，它对于名画识别的功能做的还不错。但是可能由于是小程序，加上宣传程度不是很大，并没有很多用户去体验。加大宣传力度、不断优化识别功能以及将页面做得更加精美会帮我们赢得竞争。

一、市场上有许多识图种类的软件APP，但是关于世界名画的APP，发现只有鉴赏类与壁纸类，而并没有一款可以直接识别的世界名画出自谁手的APP，因此我们组在该方面有着明显的优势，竞争能力会强。

二、市场上没有没有WEB版本识图种类的软件APP。而WEB具有多平台的优势，能够同时满足Windows端用户和移动端用户的需求，能够在市场上争取到更多的用户。

**5）D（Delivery交付，Data 数据）**

1 Delivery支付

我们会通过qq、微信等社交工具，向同学、朋友推荐我们的软件，让他们试用，并给予我们反馈。在做完用户调查得到反馈之后，再反过来改进我们的软件。具体来说，首先，需要考虑用户为什么用我们的产品。我们团队做的是AI识别乔托·迪·邦多纳、毕加索、梵高等49位大师的抽象画作品。仅仅通过同学朋友的推广，或者在其他网站媒体上宣传作用有限，因为这一课题不够“生活”，也算不上“娱乐”，普通人不一定会感兴趣，而感兴趣的可能也早已体验过谷歌等大公司的成熟产品了。因此，为了宣传我们的产品，还需要额外的噱头。提到抽象画，一直以来有这样一个问题：“抽象艺术与涂鸦有什么区别呢？“，可以以此为切入点，宣传时称”也可以上传自己的涂鸦画，看看与哪位大师的风格最接近。“

2 Data 数据

首先是准确率的数据，可以在显示系统识别结果后加一个反馈按钮，当用户发现系统对名画识别错误后可以通过这一功能进行反馈。其次是不同宣传途径传播效率的数据，这一问题网络上已经有很多解决方案了，比如不同平台的宣传分享链接添加额外的信息，并记录，就可以知道用户大多是通过何种途径了解到我们的产品了。

## 电梯演讲

Autumn帮助客户增强鉴赏能力，更加方便的快速了解名画的作者以及作者的故事，让理工直男也能对艺术品侃侃而谈。
