1.Google DeepMind 在 NeurIPS 2024 的文章<Recommender Systems with Generative Retrieval>
2.https://zhuanlan.zhihu.com/p/676663980
3.使用自回归等技术（自回归、聚类等）把item-id转化为多个语义id，然后使用transformer实现生成式推荐。个人理解，生成的时候会限制语义id的序列使得最终语义序列是有对应item-id的。
4.个人理解，优势是降维和泛化（softmax的查询空间变小），缺点是没有端到端更加直接信息更多。
