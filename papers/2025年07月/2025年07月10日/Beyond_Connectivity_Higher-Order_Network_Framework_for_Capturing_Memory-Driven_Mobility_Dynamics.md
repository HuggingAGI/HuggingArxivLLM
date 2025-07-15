# 超越连通性：高阶网络框架用于捕捉记忆驱动的移动模式

发布时间：2025年07月10日

`其他` `网络分析`

> Beyond Connectivity: Higher-Order Network Framework for Capturing Memory-Driven Mobility Dynamics

# 摘要

> 理解并预测交通网络中的移动性动态对于基础设施规划、韧性分析和交通管理至关重要。然而，传统图模型通常假设移动性是无记忆的，这限制了它们捕捉真实世界移动模式中固有的顺序依赖关系的能力。

在这项研究中，我们引入了一种新颖的高阶网络框架，用于建模交通系统中的记忆依赖动态。通过将经典图表示扩展为高阶马尔可夫链和de Bruijn图结构，我们的框架能够编码遍历路径的空间和时间顺序，从而更精确地分析结构上和功能上关键的组件。

我们将关键网络分析指标，包括介于中心性、PageRank和下一步预测，推广到高阶设置，并在Sioux Falls交通网络上使用MATSim生成的基于智能体的轨迹数据验证了我们的方法。实验结果表明，在多个任务中，高阶模型的表现优于一阶基线模型，其中三阶模型在预测准确性和模型复杂性之间达到了最佳平衡。

这些发现突出了在基于网络的交通分析中纳入记忆效应的重要性，并为捕捉基础设施系统中复杂的移动行为提供了一种可扩展的数据驱动方法。

> Understanding and predicting mobility dynamics in transportation networks is critical for infrastructure planning, resilience analysis, and traffic management. Traditional graph-based models typically assume memoryless movement, limiting their ability to capture sequential dependencies inherent in real-world mobility patterns. In this study, we introduce a novel higher-order network framework for modeling memory-dependent dynamics in transportation systems. By extending classical graph representations through higher-order Markov chains and de Bruijn graph structures, our framework encodes the spatial and temporal ordering of traversed paths, enabling the analysis of structurally and functionally critical components with improved fidelity. We generalize key network analytics, including betweenness centrality, PageRank, and next-step prediction, to this higher-order setting and validate our approach on the Sioux Falls transportation network using agent-based trajectory data generated with MATSim. Experimental results demonstrate that higher-order models outperform first-order baselines across multiple tasks, with the third-order model achieving an optimal balance between predictive accuracy and model complexity. These findings highlight the importance of incorporating memory effects into network-based transportation analysis and offer a scalable, data-driven methodology for capturing complex mobility behaviors in infrastructure systems.

[Arxiv](https://arxiv.org/abs/2507.07727)