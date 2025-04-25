# # 理解、划分与征服：通过多智能体分层强化学习探索特征子空间

发布时间：2025年04月24日

`LLM应用` `机器学习`

> Comprehend, Divide, and Conquer: Feature Subspace Exploration via Multi-Agent Hierarchical Reinforcement Learning

# 摘要

> 特征选择的目标是对目标数据集进行预处理，找到最优且最精简的特征子集，从而提升下游机器学习任务的表现。在基于过滤器、包装器和嵌入的方法中，基于强化学习（RL）的子空间探索策略提供了一种新的目标优化导向视角，并展现出令人期待的性能。然而，尽管性能有所提升，当前的强化学习方法在处理复杂数据集时仍面临与传统方法相似的挑战。这些挑战源于每个特征使用一个代理的低效范式，以及数据集中固有的复杂性。这一观察促使我们研究并解决上述问题，提出了一种新颖的方法，即层次强化学习特征选择（HRLFS）。我们的方法首先采用基于大型语言模型（LLM）的混合状态提取器，捕捉每个特征的数学和语义特性。基于此信息，对特征进行聚类，从而构建每个聚类和子聚类的分层代理。大量实验验证了我们方法的效率、扩展性和鲁棒性。与当代方法或基于每个特征一个代理的强化学习方法相比，HRLFS通过迭代特征子空间探索提升下游机器学习性能，同时通过减少代理数量加速总运行时间。

> Feature selection aims to preprocess the target dataset, find an optimal and most streamlined feature subset, and enhance the downstream machine learning task. Among filter, wrapper, and embedded-based approaches, the reinforcement learning (RL)-based subspace exploration strategy provides a novel objective optimization-directed perspective and promising performance. Nevertheless, even with improved performance, current reinforcement learning approaches face challenges similar to conventional methods when dealing with complex datasets. These challenges stem from the inefficient paradigm of using one agent per feature and the inherent complexities present in the datasets. This observation motivates us to investigate and address the above issue and propose a novel approach, namely HRLFS. Our methodology initially employs a Large Language Model (LLM)-based hybrid state extractor to capture each feature's mathematical and semantic characteristics. Based on this information, features are clustered, facilitating the construction of hierarchical agents for each cluster and sub-cluster. Extensive experiments demonstrate the efficiency, scalability, and robustness of our approach. Compared to contemporary or the one-feature-one-agent RL-based approaches, HRLFS improves the downstream ML performance with iterative feature subspace exploration while accelerating total run time by reducing the number of agents involved.

[Arxiv](https://arxiv.org/abs/2504.17356)