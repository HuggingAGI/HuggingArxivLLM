# 快速多核估计的自平衡内存高效动态度量空间数据维护

发布时间：2025年04月24日

`其他` `机器学习` `生成模型`

> Self-Balancing, Memory Efficient, Dynamic Metric Space Data Maintenance, for Rapid Multi-Kernel Estimation

# 摘要

> 我们提出了一种动态自平衡八叉树数据结构，能够在动态度量空间中高效维护邻域关系，这是现代机器学习系统中的重要挑战。许多学习和生成模型作为动力学系统运行，其表示会在训练过程中不断演变，因此需要快速、自适应的空间组织。我们的双参数八叉树支持对数时间更新和查询，消除了数据分布变化时需要昂贵的完全重建需求。我们展示了它在四大领域的有效性：（1）通过支持更多粒子且更低开销来加速Stein变分梯度下降；（2）实现具有对数复杂度的实时增量KNN分类；（3）为检索增强生成提供高效动态索引和检索；（4）通过联合优化输入和潜在空间来提高样本效率。在所有应用中，我们的方法都实现了指数级加速，同时保持了准确性，特别是在高维空间中，自适应空间结构的维护至关重要。

> We present a dynamic self-balancing octree data structure that enables efficient neighborhood maintenance in evolving metric spaces, a key challenge in modern machine learning systems. Many learning and generative models operate as dynamical systems whose representations evolve during training, requiring fast, adaptive spatial organization. Our two-parameter octree supports logarithmic-time updates and queries, eliminating the need for costly full rebuilds as data distributions shift. We demonstrate its effectiveness in four areas: (1) accelerating Stein variational gradient descent by supporting more particles with lower overhead; (2) enabling real-time, incremental KNN classification with logarithmic complexity; (3) facilitating efficient, dynamic indexing and retrieval for retrieval-augmented generation; and (4) improving sample efficiency by jointly optimizing input and latent spaces. Across all applications, our approach yields exponential speedups while preserving accuracy, particularly in high-dimensional spaces where maintaining adaptive spatial structure is critical.

[Arxiv](https://arxiv.org/abs/2504.18003)