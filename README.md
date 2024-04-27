# 0孤立点，1线性，2矩阵，3树，4图，4.5语义网，5超图

知识拷贝与知识组织结构（如何将孤立点集变成复杂且有序的结构体或非结构逻辑语义体）。

> 元数据根序列笔记，借鉴Linux的根目录概念。归纳整理所有笔记的元信息或规则。
>
> 分离内容和笔记结构。
> 
> 面向内容，分离数据和软件，不把内容当处理对象的研究软件都是玩软件和新鲜感罢了。
> 
> 确定以“可搜索”为笔记组织评价指标，评价笔记组织结构的好坏。

## [笔记的树图逻辑数据结构](./GrowthK2S)

![tree](./Attachment/c6341a3b82cbba841ff6d1bf3a5074d9.jpg)

知识组织的拓扑结构：==0孤立点，1线性，2矩阵，3树，4图，4.5语义网，5超图==。其中语义网包含逻辑结构，非结构化笔记，非关系型数据库。描述从简单的孤立笔记结构逐渐发展为最复杂的超图笔记结构的过程。

知识本身可能像彩虹一个是一个整体，只不过叙述的时候需要细分成不同的色带，然后读取这个叙述，最后还原成整体。对孤立点的有序的结构化。本质上可能是对孤立点的一种排列和组合。为孤立点寻找一种结构容器。

概念的 内涵 和 外延 可能分别对应：主题法和标签法

**缩进列表文档 ≈ XML ≈ DOM ≈ 文档树**；树逻辑结构 ≈ 层级嵌套列表；XML 和基于 XML 的语言的整个结构是建立在标签（Tag）之上的。

> Alan Kay 在 2012 年的 SCIx 上提到，每当你创造一个工具的时候，你既做了一个增强器又做了一个假肢。汽车在一定程度上增强了我们，同时在另一方面弱化了我们的身体。 虽然通过 P.A.R.A + Notion 能极大的增强我们对于「第二大脑」的建设，但是这一切的价值还是建立在「第一大脑」的背后——因为所谓的知识和智慧，目前来看，只有第一大脑才能生成。

以树作为载体，以图作为树的延伸。用树存储，用图链接和表现。从 点或线性 到 树🌲 到 图。树结构是最简单实用的存储方式。以树为基础，用树去承载高阶的图。根到叶子和节点的路径、全部叶子或节点 就是 所有的（笔记、元素）文件；叶子或节点之间的相互连接就是图或者别的数据结构。

思维是网状形态，内容是树状结构，文本则是线性呈现。要管理信息，输出有价值的内容，根问题就是协调网、树、线三种形态。

关于笔记的层次：
1. 元素内容：笔记文件的内容的记载（笔记包含什么）
2. 元素本身：笔记本身以及笔记的定义属性或字段（笔记的本身）
3. 元素群的组织：笔记的组织索引。（多笔记的组织索引）

关于笔记的功能：
1. 笔记＝复用➕快速索引，笔记不能代替自己的大脑思考，笔记只能是我们大脑记忆的延伸。也就是辅助记忆的工具。
2. 复用（写入和读取）笔记的读和写操作。查询优化。
	1. 内化的辅助工具
	2. 记忆的辅助工具
3. 启发性
4. 记录思考过程
5. 快速检索
6. 笔记就是一个外置存储器，关注速度和检索就好了
7. 相互连接笔记、写自己的想法
8. 所有外部输入信息（记忆、笔记）都必须通过在脑中重建才可以发挥作用。正如一个老师脑子中的知识通过语言和教育方式在学生头脑中的重建后，才能使学生理解问题并灵活解决。
9. 弥补人脑记忆短板，在记忆方面增强人类的工作记忆，帮助人类思考（就像做数学题目）。
10. 真正的内容在卢曼的脑子里，卡片不是知识的载体，而是起到提示作用！卡片并不是在减轻工作记忆，而是在激活知识网络的不同部分产生更多的想法和发现。
11. 我还想加入自己注释和关联？

关于笔记的作用：
1. 帮助我们存储信息
2. 帮助我们思考和理解信息
3. 创造知识与知识之间的链接

## “当我想找一篇文章，它一定在这里。”

> 软件多少是伪命题，真相在集中存储 
>
> 关于All in one还是什么N+1的争论一直没停下过。 
>
> 但实际上这不是问题，问题是：你必须能在一个地方，尽可能找到你储存的全部信息。 
>
> “当我想找一篇文章，它一定在这里。” 
>
> 有这种感觉就够了。


## 正文

1. 分而治之：将每个软件都纳入工作流程的一部分，每一个软件承担各种的流程。收集的软件就承担收集工作，整理软件就承担整理工作。整理软件就承担整理工作。
    小米笔记（时间序列）、印象笔记（同步）  、 OneNote 、 obsidian、Tiddlywiki。

2. 剪藏&创作，使用是否为自己书写简单区分为这两类。

## 多样性

1. 概念专用名词解释
2. 说明文。

## 盖尔定律

### 定义

"All complex systems that work evolved from simpler systems that worked. [And conversely...] A complex system designed from scratch never works and cannot be patched up to make it work."

所有切实可行的复杂系统势必是从切实可行的简单系统发展而来的。一个一开始就设计复杂系统永远无法运行，也无法通过修补使其工作。你必须从一个简单的系统开始。

盖尔定律说明了设计高度复杂的系统很可能会失败。它们很难一蹴而就，更多的是从简单的系统逐渐演变而来。

#### 阐述

仔细观察可以发现，无论是一个互联网软件系统的架构，还是一个城市的建设，载人航天飞机的建造，都不是一开始就事无巨细设计好的，没有任何人可以模拟真实场景中的各种内外部因素，也就是说在一个系统逐步成熟和复杂化的过程中，是不断对外部无数变量进行响应和调整的过程。

---

## 附加

**元数据**（英语：metadata）又称**元资料**、**诠释资料**、**后设资料**、**中继资料**、**中介资料**等等，为描述其他[资料](https://zh.wikipedia.org/wiki/資料)[信息](https://zh.wikipedia.org/wiki/資訊)的资料。

**反射**是指[计算机程序](https://baike.baidu.com/item/计算机程序?fromModule=lemma_inlink)在[运行时](https://baike.baidu.com/item/运行时?fromModule=lemma_inlink)（Run time）可以访问、检测和修改它本身状态或行为的一种能力。

**元知识**（英语：metaknowledge）是关于描述、使用一般[知识](https://zh.wikipedia.org/wiki/知识)的知识[[1]](https://zh.wikipedia.org/wiki/元知识#cite_note-陈-1)。元知识常被宽泛地依照字面意思称为“关于知识的知识”。

**元对象**（metaobject）是操纵、创建、描述或实现对象（包括自身）的[对象](https://zh.wikipedia.org/wiki/对象_(计算机科学))。适用于元对象的对象叫做基础对象。元对象可以定义的一些信息包括：基础对象的[类型](https://zh.wikipedia.org/wiki/类型系统)、[接口](https://zh.wikipedia.org/wiki/接口_(计算机科学))、[类](https://zh.wikipedia.org/wiki/类_(计算机科学))、[方法](https://zh.wikipedia.org/wiki/方法_(计算机科学))、[特性](https://zh.wikipedia.org/wiki/特性_(计算机科学))、[解析树](https://zh.wikipedia.org/wiki/解析树)等。元对象是计算机科学[反射](https://zh.wikipedia.org/wiki/反射_(计算机科学))概念的例子，这里的系统（通常在运行时间）能访问它自己的内部结构。反射在根本上确使一个系统能现场重写自身，在其运行时改变自己的实现。

## 许可证

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">知识共享署名-相同方式共享 4.0 国际许可协议</a>进行许可。
