---

layout: post
title: 技术人员的产品思维
category: 技术
tags: Product
keywords: Product thinking

---

## 简介（持续更新）

## app

我是喜马拉雅app的忠实粉丝，有一次跟产品的鹏哥闲聊：我看到很多产品经常加班很辛苦，但感觉我们的app 一年了没什么变化啊。后来我琢磨了下：为什么很多特性我不知道，发现我对app的使用路径是:打开 ==> 肚脐眼（记录了上一次播放） ==> 郭德纲相声下一首 ==> 设置播放完自动关闭 ==> 锁屏睡觉。

这有两个方面的问题

1. 我对我们的app 不够熟悉，不能够理解功能演化背后的产品逻辑，以致于不知道或者知道了也不认为某个新特性的用处
2. 我或许是一个少数群体
	* **我对app的使用场景是明确的，就是睡前**。很多新功能特性是基于用户会“闲逛”的假设，可能效果会有限。举个例子， 如果某个产品主打青年男性群体，那么应该在各类游戏、社交、社交app上投广告，而在大街上投广告的作用会很有限，因为他们很少逛街。 
	* **我对app的使用目的是非常明确的**，就是助眠。此时，只有助眠类的声音才会中断我常规的使用路径，助眠或许可以提成一个专门的声音分类，晚上的时候个性化推荐可以增加助眠类声音的权重，类似的还有开车等。 

我们的产品还停留在 各路大V 赶紧来我们的平台做节目，给用户提供更多更好地内容。那么反过来， 我们是否可以通过用户的收听行为感知到用户的需要，进而可以影响声音的“供给”。比如我们通过搜索敏感词、某一类音频的收听指数提高 来感知比如 机器学习的 热度上升，就可以给相关的节目提供商更高的报价/降低该门类的付费门槛吸引更多主播。阿里新零售的一个重要概念之一就是，阿里可以知道一个便利店方圆1000米大部分人群的收入构成、职业及消费习惯，然后就可以估算出来该门店明天应该进货多少个5块的包子、3块的包子。
	
## 平台系统

如果你做了一个框架，接入很麻烦，那么基本是没什么人用的。使用文档1页最好，超过2页基本没人细看，很少有人看到第3页，所以你写那么多“注意事项”都只是给自己加戏。

如果原先有一个老系统，你做了一个新系统，这个时候技术先进性什么的都没有价值，迁移新系统是需要成本的，新系统hold 不住迁移成本，再多的宣传都作用不大。

尽量润物细无声，搭顺风车，将自己的功能挂在一个已有的系统、流程里面。

我一直在组内推研发协作工具，每周五（有时会忘）下午会去小组群里发：大家同步下teambition，发下周报。但还是搞不起来，因为有事大家还是习惯IM直接说，我老拿忘发周报说事也不好。teambition 是比IM 更好的协作方式，好但不是足够好

1. 需要一个组织文化+开发流程的加持。
2. 很多时候人和人的沟通是不可避免的，甚至文字沟通都是不够的，面对面的表情、语气也很重要。面对面/IM沟通必不可免 ==> 面对面/IM沟通时顺带手沟通了 其实不需要 IM 沟通的事项。这个时候，用teambition再排一遍就显得多余。你不能假设开发、测试都在“闲庭信步”，大部分时候他们都是“焦头烂额”，根本不想理会哪怕一点多余的事情。

所以我的一个想法是，如果teambition 能够支持根据feature完成情况自动生成周报的功能。一个是大家不用再写周报了，另一个是大家自然就会多用teambition（用的越多，周报越充实）。



