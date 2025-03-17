# MUSS: 多级子集选择，兼顾相关性和多样性

发布时间：2025年03月14日

`RAG` `推荐系统` `问答系统`

> MUSS: Multilevel Subset Selection for Relevance and Diversity

# 摘要

> 相关且多样化的子集选择问题在推荐系统和检索增强生成（RAG）等领域有着广泛应用。以推荐系统为例，用户不仅希望获得相关推荐，还期待这些推荐具有多样性。受约束的子集选择问题属于NP难问题，而广受欢迎的MMR方法采用贪心策略进行选择。尽管许多实际应用涉及海量数据，但传统的MMR方法并未考虑分布式选择的场景。这一局限性后来被DGDS方法突破，该方法通过随机划分数据实现了分布式设置。在此基础上，我们进一步挖掘数据内在结构，提出了一种名为MUSS的新方法，该方法采用多级策略实现相关且多样化的选择。我们进行了严格的理论分析，证明了该方法能够逼近最优目标的常数因子近似。在推荐系统场景下，MUSS不仅达到了与现有方法相当的性能，还实现了4.5到20倍的速度提升。此外，MUSS在基于RAG的问题回答任务中也表现出色，准确率比现有方法高出6个百分点。


> The problem of relevant and diverse subset selection has a wide range of applications, including recommender systems and retrieval-augmented generation (RAG). For example, in recommender systems, one is interested in selecting relevant items, while providing a diversified recommendation. Constrained subset selection problem is NP-hard, and popular approaches such as Maximum Marginal Relevance (MMR) are based on greedy selection. Many real-world applications involve large data, but the original MMR work did not consider distributed selection. This limitation was later addressed by a method called DGDS which allows for a distributed setting using random data partitioning. Here, we exploit structure in the data to further improve both scalability and performance on the target application. We propose MUSS, a novel method that uses a multilevel approach to relevant and diverse selection. We provide a rigorous theoretical analysis and show that our method achieves a constant factor approximation of the optimal objective. In a recommender system application, our method can achieve the same level of performance as baselines, but 4.5 to 20 times faster. Our method is also capable of outperforming baselines by up to 6 percent points of RAG-based question answering accuracy.

[Arxiv](https://arxiv.org/abs/2503.11126)