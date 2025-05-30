# 探讨基于 LLM 的多智能体系统中通信网络结构对信息传播的影响

发布时间：2025年05月29日

`Agent` `人工智能` `计算机科学`

> Understanding the Information Propagation Effects of Communication Topologies in LLM-based Multi-Agent Systems

# 摘要

> 大型语言模型（LLM）为基础的多智能体系统中的通信拓扑结构从根本上决定了智能体之间的协作模式，对集体决策的效率和效果产生关键影响。近期关于通信拓扑自动化设计的研究虽然倾向于构建稀疏结构以提高效率，但它们往往忽略了稀疏和密集拓扑在何时以及为何有助于或阻碍协作。本文中，我们提出了一种因果框架，用于分析在不同稀疏度的拓扑结构下，智能体输出（无论正确与否）如何传播。我们的实证研究表明，适度稀疏的拓扑结构通常能够实现最佳任务性能，这类拓扑结构既能有效抑制错误传播，又能保持有益信息的扩散。基于这一见解，我们提出了一种新型拓扑设计方法EIB-learner，通过融合密集和稀疏图的连接模式，平衡错误抑制和有益信息传播。大量实验表明，EIB-learner在有效性、通信成本和鲁棒性方面均表现出色。

> The communication topology in large language model-based multi-agent systems fundamentally governs inter-agent collaboration patterns, critically shaping both the efficiency and effectiveness of collective decision-making. While recent studies for communication topology automated design tend to construct sparse structures for efficiency, they often overlook why and when sparse and dense topologies help or hinder collaboration. In this paper, we present a causal framework to analyze how agent outputs, whether correct or erroneous, propagate under topologies with varying sparsity. Our empirical studies reveal that moderately sparse topologies, which effectively suppress error propagation while preserving beneficial information diffusion, typically achieve optimal task performance. Guided by this insight, we propose a novel topology design approach, EIB-leanrner, that balances error suppression and beneficial information propagation by fusing connectivity patterns from both dense and sparse graphs. Extensive experiments show the superior effectiveness, communication cost, and robustness of EIB-leanrner.

[Arxiv](https://arxiv.org/abs/2505.23352)