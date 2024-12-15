# LoRANN：用于近似最近邻搜索的低秩矩阵分解技术

发布时间：2024年10月24日

`其他` `机器学习` `数据库`

> LoRANN: Low-Rank Matrix Factorization for Approximate Nearest Neighbor Search

# 摘要

> 近似最近邻（ANN）搜索在众多现代机器学习流程中是关键一环；近期的应用案例涵盖检索增强生成（RAG）和向量数据库。基于聚类的 ANN 算法，采用基于乘积量化（PQ）的得分计算方式，因其具备可扩展性，且适用于分布式和基于磁盘的实现，所以常用于工业规模的应用。但它们的查询速度比领先的基于图的 ANN 算法要慢。在本研究中，我们基于内积近似是一个多元（多输出）回归问题这一发现，提出了一种新的有监督得分计算方法，该问题能够通过降秩回归有效解决。我们的实验表明，在现代高维数据集中，所提出的降秩回归（RRR）方法在查询延迟和内存使用方面都优于 PQ。我们还推出了 LoRANN，这是一个基于聚类的 ANN 库，它运用了所提出的得分计算方法。LoRANN 能与领先的基于图的算法相媲美，并且在高维数据集上超越了最先进的 GPU ANN 方法。

> Approximate nearest neighbor (ANN) search is a key component in many modern machine learning pipelines; recent use cases include retrieval-augmented generation (RAG) and vector databases. Clustering-based ANN algorithms, that use score computation methods based on product quantization (PQ), are often used in industrial-scale applications due to their scalability and suitability for distributed and disk-based implementations. However, they have slower query times than the leading graph-based ANN algorithms. In this work, we propose a new supervised score computation method based on the observation that inner product approximation is a multivariate (multi-output) regression problem that can be solved efficiently by reduced-rank regression. Our experiments show that on modern high-dimensional data sets, the proposed reduced-rank regression (RRR) method is superior to PQ in both query latency and memory usage. We also introduce LoRANN, a clustering-based ANN library that leverages the proposed score computation method. LoRANN is competitive with the leading graph-based algorithms and outperforms the state-of-the-art GPU ANN methods on high-dimensional data sets.

[Arxiv](https://arxiv.org/abs/2410.18926)