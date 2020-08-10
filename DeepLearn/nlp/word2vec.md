### NLP之word2vec

1. word2vec的训练过程
2. Word2vec方法有哪些/区别 [参考](https://zhuanlan.zhihu.com/p/26306795) [参考2](https://zhuanlan.zhihu.com/p/43736169)
	Skip-gram 模型：用一个词语作为输入，来预测它周围的上下文
	CBOW 模型：拿一个词语的上下文作为输入，来预测这个词语本身
	
	输入：这里的词将转化成one-hot的形式进行输入。
	输出：也是一个one-hot的形式，对应一个词