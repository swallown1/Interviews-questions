## 推荐系统的其他问题

* 讲一下整个推荐系统的流程。
推荐系统一般分为两个阶段：召回和排序
召回主要做的是根据用户部分特征，从大量的数据中，快速找到一些用户潜在感兴趣的物品，然后将其交给排序在去精排。召回强调块 排序强调准。

细分的话分为四个阶段：
召回、粗排、精排和重排。
有时候因为每个用户召回环节返回的物品数量还是太多，怕排序环节速度跟不上，所以可以在召回和精排之间加入一个粗排环节，通过少量用户和物品特征，
简单模型，来对召回的结果进行个粗略的排序，在保证一定精准的前提下，进一步减少往后传送的物品数量，粗排往往是可选的，可用可不同，跟场景有关。
[https://zhuanlan.zhihu.com/p/100019681](https://zhuanlan.zhihu.com/p/100019681)

* 推荐系统的可解释性你了解吗？有哪些方法，基于深度学习的推荐系统可解释性你知道些什么。
* embedding维度如何选取，维度不一样拼接在一起会怎么样？
* 从推荐算法角度，怎么提高价格低的商品的曝光量



