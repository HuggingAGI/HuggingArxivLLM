# HYCO：数据驱动偏微分方程建模的混合协作学习

发布时间：2025年09月17日

`其他` `基础理论`

> HYCO: Hybrid-Cooperative Learning for Data-Driven PDE Modeling

# 摘要

> 我们提出混合协同学习（HYCO）——一种通过相互正则化机制迭代整合物理模型与数据驱动模型的混合建模框架。不同于传统方法直接对合成模型施加物理约束，HYCO 将物理与合成组件视为协同训练的智能体：它推动物理模型与合成模型达成一致，同时增强合成模型以更好地拟合可用数据。该协同学习方案天生具备可并行性，还能增强对噪声、稀疏或异构数据的鲁棒性。在静态与时间依赖问题上的大量数值实验证实，HYCO 性能超越传统物理方法与数据驱动方法，即便在不适定条件下也能准确恢复解与模型参数。此外，该方法可自然地从博弈论角度解释，不仅支持交替优化，更为未来的理论发展奠定基础。

> We present Hybrid-Cooperative Learning (HYCO), a hybrid modeling framework that iteratively integrates physics-based and data-driven models through a mutual regularization mechanism. Unlike traditional approaches that impose physical constraints directly on synthetic models, HYCO treats the physical and synthetic components as co-trained agents: the physical and synthetic models are nudged toward agreement, while the synthetic model is enhanced to better fit the available data. This cooperative learning scheme is naturally parallelizable and improves robustness to noise as well as to sparse or heterogeneous data. Extensive numerical experiments on both static and time-dependent problems demonstrate that HYCO outperforms classical physics-based and data-driven methods, recovering accurate solutions and model parameters even under ill-posed conditions. The method also admits a natural game-theoretic interpretation, enabling alternating optimization and paving the way for future theoretical developments.

[Arxiv](https://arxiv.org/abs/2509.14123)