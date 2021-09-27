# weekly-reading

weekly-reading 是我个人的每周阅读计划。

前身是前公司leader组织的daily-reading计划，项目地址为：https://github.com/daily-reading/daily-reading

因工作变动，本人离开了该项目，但仍然希望能够保存每周坚持阅读技术文章的习惯。

希望能延续这个阅读计划，以提升英文阅读能力与技术视野。

本项目按照时间可以划分为两个部分：

- 2021.9.27 以前的内容是过去在daily-reading项目中本人读书笔记的历史归档

- 2021.9.27 以后记录本人自己每周的读书笔记

## Index

* 2021/05/17 - [Monorepo: please do!](2021/5/17): 本文是对 [Monorepos: Please don't!](2021/3/9) 的回应。文章认为 Monorepo 可以提前发现 API 的不兼容性冲突，从而有利于大规模的代码库管理。
* 2021/04/21 - [It's time to say goodbye to the GPL](2021/4/21): 作者认为在现在的环境下，闭源软件已经不是问题，真正的问题是运行在各类云服务平台上的软件系统，一旦平台关闭，那么我们就不能再使用他们（想想 Google Reader）。所以在当前的环境下，GPL 不仅变得毫无意义，还成为了软件自由的阻碍。
* 2021/04/19 - [Layers in Software Architecture that Every Sofware Architect should Know](2021/4/19): 文章对经典三层架构做了简单的介绍，即展示层、业务层和数据访问层架构。
* 2021/03/29 - [How We Enable Airbnb Team Members to Code Like a Mobile Engineer](2021/3/29): Airbnb 通过一个内部学习计划，使 45 名工程师掌握了移动端开发的初级技能。本文简略描述了这项计划的步骤与效果。
* 2021/03/28 - [A Checklist For First-Time Engineering Managers](2021/3/28): 作为一名研发主管，我非常了解刚刚担任管理任务时那种孤独、缺少引导的感觉。这份 Checklist 涵盖了团队建设、交付、协作、愿景和专业成长等多个方面，为新晋的研发主管提供了一些很好的方向与参照标准。
* 2021/03/26 - [Get better at programming by learning how things work](2021/3/26): 「学习事情是如何运转的」有利于我们写出高质量的代码。平时工作中大部分的实现细节都被一层层抽象给屏蔽了，这在大部分情况下没什么问题。但当我们遇到一些 Bug，一些难以在抽象层之上去解释的行为时，问题会强迫我们去了解细节。学习实现细节对我们写出更好的代码有非常大的帮助，它可以帮助我们通过类比去了解其他陌生的领域。
* 2021/03/25 - [My Third Year as a Solo Developer](2021/3/25): 作者分享了做独立开发者的一系列故事，包括如何运营一款成功的硬件产品、如何运营博客、如何在 Hacker News 上做推广、如何放弃一个不成功的想法等等。
* 2021/03/23 - [Building a Healthy On-Call Culture](2021/3/23): SoundCloud 的 OnCall 实践分享，比如合适的 OnCall 频率、OnCall 团队大小、培养学习文化等等。
* 2021/03/10 - [An unlikely database migration](2021/3/10): 作者分享了在一家创业公司，从单文件存 JSON 到数据库的整个过程。中间分享了一些对于不同类型数据库的看法，包括 MySQL、PostgreSQL、SqlLite、Perkeep、CockroachDB 等等，最终他们选择了 etcd。
* 2021/03/09 - [Monorepos: Please don't!](2021/3/9): 作者认为 monorepo 主张的 VSC 对团队的收益率很低，列举了几个传统上认为 monorepo 具有的优势进行了反驳，同时给出了一些 monorepo 独有的缺陷。另外，作者还认为代码的组织是一家公司工程文化和领导才能的直接结果体现，与使用 monorepo 与 polyrepo 无关。
* 2021/03/08 - [Work, play, and motivation](2021/3/8): 作者认为工作和娱乐的一个主要区别是，娱乐有着更紧密的及时反馈，而工作往往是到最后才会收获。那么我们可以做的一个事情是，改变我们工作的计划，让反馈变得更加及时，从而带来更强的动力。
* 2021/03/07 - [Preparing for the Systems Design and Coding Interview](2021/3/7): 作者分享了准备技术面试所需要了解的书籍、知识、课程和其他相关资源。
* 2021/03/01 - [We Burnt $72K testing Firebase + Cloud Run and almost went Bankrupt](2021/3/1): 一次错误的上云决策，在 2 小时内给一个不到 10 人的创业小团队带来了 7 万美金的云服务账单。
* 2021/02/17 - [Why Is Naming Things Hard?](2021/2/17): Naming 永远是一个有趣的话题，口语表达永远是不精准的，但我们希望在代码表达时尽可能去精准，这导致命名一个变量、函数时非常困难。
* 2021/01/25 - [Whose Code is it Anyway?](2021/1/25): Yelp 建设了一个 Code Ownership 系统来追踪每一行代码的归属，这个系统可以很好地与 PagerDuty、Jira 一起合作去减少不同团队之间沟通的复杂性。
* 2021/01/24 - [Pairing Guidelines](2021/1/24): 一份简短的配对编程指南。
* 2021/01/12 - [What Does Mastery Look Like in Software Engineering?](2021/1/12): 这是关于 [一个 Hacker News 上的问题](https://news.ycombinator.com/item?id=25643940) 的总结分析，讨论了「专业软件工程师」独特的职业素养。
* 2021/01/11 - [Maximizing Developer Effectiveness](2021/1/11): 文章提出了一个优化研发团队生产效率的框架, 作者通过明确反馈回路、优化反馈循环，让研发团队的效率更高。
* 2021/01/02 - [State machines are wonderful tools](2021/1/2): 状态机是一个很强大的编程思想，作者用摩尔斯电码解析、UTF-8 解码、字数统计为例说明了如何用状态机写出清晰、易于扩展的代码。
* 2020/12/30 - [I've conducted over 600 technical interviews on interviewing.io. Here are 5 common problem areas I've see](2020/12/30): 作者分享了在过去 600 次面试过程中，总结出的候选人常见的 5 个问题。
* 2020/12/26 - [Life is Short](2020/12/26): 生命短暂，如何去使用这些宝贵的时间让自己感觉好一些？
* 2020/12/22 - [To listen well, get curious](2020/12/22): 一篇关于「倾听」的的 soft skill blog。前置技能是[非暴力沟通](https://book.douban.com/subject/3533221/)，一套简单、有效的沟通技巧。
* 2020/12/20 - [Understanding Linux CPU Load - when should you be worried?](2020/12/20): CPU Load 是一个既基础又容易被误解的知识点，这篇文章举了一个车过桥的例子，生动、简单的说明了 CPU Load 和 CPU 利用率之间的区别，以及对于不同程度的 CPU Load 我们应该关心什么。
* 2020/12/16 - [You don't have to be busy to be prolific](2020/12/16): 关于个人时间管理的实践，作者认为通过「创造性惯性」以提升工作效率是实现高效产出的最佳实践，而不是通过堆积工作时间让自己高产。
* 2020/12/02 - [Attention is your scarcest resource](2020/12/2): 一些关于个人时间管理的技巧。当一个人可以用 50% 的时间专注在同一个事上时，TA 就会成为一个团队中最耀眼的明星。
* 2020/11/28 - [Common Performance Review Biases: How to Spot and Counter Them](2020/11/28): 在绩效反馈中，我们并不总是可以收到清晰、公正的反馈，有些反馈会带有一些偏见。作者总结出了一些常见偏见模式，并且针对主管和成员都给出了很好的改正建议。
* 2020/11/25 - [Growth as a writer](2020/11/25): Linus Lee 作为一个非常高产的博主，提出了他认为的写作的三个阶段。
* 2020/11/23 - [How LinkedIn scales compatibility testing](2020/11/23): LinkIn 有 12,000 个代码仓库，这些仓库之间有复杂的依赖关系。如何确保代码更新时对上下游的兼容性是可靠的？LinkIn 在这篇文章中分享了一些实践。
* 2020/11/22 - [How do you write simple explanations without sounding condescending?](2020/11/22): 把复杂的事情讲简单是个强有力的能力，这篇文章给出了一些建议。
* 2020/11/15 - [Making the most of your one-on-one with your manager or other leadership](2020/11/15): 一篇小短文，讲怎么提升 one-on-one 会议的效率。
* 2020/11/02 - [What do we need to know to start making a difference?](2020/11/2): 讨论了关于学习和实践的关系，作者将知识分为两类，分别讨论了如何获取这两类知识。
* 2020/10/31 - [Engineering Onboarding Processes at Medium](2020/10/31): 了解 Medium 如何帮助新工程师融入环境。
