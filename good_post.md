# Good Post Good Idea to Ponder

## [源于移动腾讯网推荐系统embedding技术实践总结](https://mp.weixin.qq.com/s/Mv2Cji3UofaD-D-K3ZY6Lg)
- 分布式表示产生：one-hot稀疏、维度灾难、语义鸿沟 -> Embedding稠密、维度低、不同的词向量间可计算相似性，但不可解释。
- MF矩阵分解隐约看到Embedding的影子，1986年Hinton提出了Embedding概念，再到word2vec工业上成功实践。
- 移动腾讯网item主要是图文的embedding。