# DDIA 读书会

DDIA 读书分享会，会逐章进行分享，结合我在工业界分布式存储和数据库的一些经验，补充一些细节。每两周左右分享一次，欢迎加入，Schedule 在[这里](https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq)。我们有个对应的分布式&数据库讨论群，每次分享前会在群里通知。如想加入，可以加我的微信号：qtmuniao，简单自我介绍下，并注明：分布式系统群。另外，我的公众号：“木鸟杂记”，有更多的分布式系统、存储和数据库相关的文章，欢迎关注。

读书会安排和往期录屏: [https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq](https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq)
# 《DDIA 逐章精读》小册

在理解英文原文的基础上，结合我的一些工作经验，进行一些相应扩展，并参考 [github 上 Vonng 的中文翻译版](https://github.com/Vonng/ddia)，对每一章用中文重新组织，作为每次分享的文字稿，在此集结为一本开源小册，希望可以对有需要的同学有所帮助，水平所限，难免疏漏，如发现有任何有误之处，欢迎[提 issue](https://github.com/DistSysCorp/ddia/issues/new) 和 [PR](https://github.com/DistSysCorp/ddia/compare)。

## 目录

### [序](preface.md)
### 第一部分：数据系统基础

* [第一章：可靠、可扩展、可维护](ch01.md) [[视频](https://www.bilibili.com/video/BV1bY411L7HA)]
    * [本书为什么以数据系统为主题](ch01.md#本书为什么以数据系统为主题)
    * [可靠性](ch01.md#可靠性)
    * [可伸缩性](ch01.md#可伸缩性)
    * [可维护性](ch01.md#可维护性)
* [第二章：数据模型和查询语言](ch02.md) [[视频上](https://www.bilibili.com/video/BV19a411C7UN) [视频下](https://www.bilibili.com/video/BV1BZ4y1r79M)]
    * [概要](ch02.md#概要)
    * [关系模型 vs 文档模型](ch02.md#关系模型与文档模型)
    * [数据查询语言](ch02.md#数据查询语言)
    * [图模型](ch02.md#图模型)
* [第三章：存储与查询](ch03.md) [[视频上](https://www.bilibili.com/video/BV1mL411P72H/) [视频下](https://www.bilibili.com/video/BV1bL411A7ga)]
    * [底层数据结构](ch03.md#驱动数据库的底层数据结构)
    * [事务型还是分析型](ch03.md#事务型还是分析型)
    * [列式存储](ch03.md#列存)
* [第四章：编码和演进](ch04.md) [[视频](https://www.bilibili.com/video/BV1Aa411q7u9)]
    * [数据编码的格式](ch04.md#数据编码的格式)
    * [几种数据流模型](ch04.md#几种数据流模型)

### 第二部分：分布式数据

* [第五章：冗余](ch05.md) [[视频上](https://www.bilibili.com/video/BV1VR4y1K7eK) [视频下](https://www.bilibili.com/video/BV1ou4116779)]
    * [领导者与跟随者](ch05.md#领导者与跟随者)
    * [复制滞后问题](ch05.md#复制滞后问题)
    * [多主模型](ch05.md#多主模型)
    * [无主模型](ch05.md#无主模型)
* [第六章：分区](ch06.md) [[视频上](https://www.bilibili.com/video/BV1tY4y157Np) [视频下](https://www.bilibili.com/video/BV1AA4y1f7Hi)]
    * [分片与复制](ch06.md#分片与复制)
    * [键值对集的分片](ch06.md#键值对集的分片)
    * [分片和次级索引](ch06.md#分片和次级索引)
    * [分片均衡](ch06.md#分片均衡)
    * [请求路由](ch06.md#请求路由)
* [第七章：事务](ch07.md) [[视频上](https://www.bilibili.com/video/BV1d94y117pW) [视频中](https://www.bilibili.com/video/BV1u3411w765) [视频下](https://www.bilibili.com/video/BV1Qr4y1M7Zm)]
    * [棘手的概念](ch07.md#棘手的概念)
    * [几种弱隔离级别](ch07.md#几种弱隔离级别)
    * [可串行化](ch07.md#可串行化)
* 第八章：分布是系统中的麻烦事 [[视频上](https://www.bilibili.com/video/BV1Ad4y1D7Yy) [视频中](https://www.bilibili.com/video/BV1114y1L7wU)]
    * 正文会在分享完后上传


# 关于我

我是青藤木鸟，一个喜欢摄影的分布系统程序员，现主要做数据库方向。可以通过[b站](https://space.bilibili.com/30933812) ，[知乎](https://www.zhihu.com/people/qtmuniao) , 微信号(qtmuniao) 找到我。更多分布式系统文章欢迎关注我的公众号——木鸟杂记。同名博客：木鸟杂记 [https://www.qtmuniao.com](https://www.qtmuniao.com)

对于 DDIA，每章大概我自己要读两遍英文版，然后自己翻译一遍，再理顺一遍词句，再找相关资料补充一些背景，最后再讲一遍，因此每章最少都得花十几个小时甚至几十个小时（比如事务那一章）。创作不易，如果感觉感觉对你有帮助的话，不妨分享给更多的人~ 这将对我是莫大的鼓励和支持。当然，也可以通过这个页面请我[吃顿饭](https://dun.mianbaoduo.com/@qtmuniao) ，顺便留个言。

最后，如果你想对某些章节讨论的话，欢迎来我搭的一个专门的分布式系统论坛：https://distsys.cn/ 。 感谢阅读，感谢关注。
