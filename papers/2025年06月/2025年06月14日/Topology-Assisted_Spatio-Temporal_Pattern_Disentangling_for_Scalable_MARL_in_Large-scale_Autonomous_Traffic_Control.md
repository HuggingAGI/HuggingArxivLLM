# # 摘要  
    本研究提出了一种基于拓扑辅助的时空模式分解方法，用于在大规模自主交通控制中实现可扩展的多智能体强化学习。

发布时间：2025年06月14日

`Agent` `智能交通` `城市交通管理`

> Topology-Assisted Spatio-Temporal Pattern Disentangling for Scalable MARL in Large-scale Autonomous Traffic Control

# 摘要

> 智能交通系统（ITSs）作为缓解城市交通拥堵的有前途的解决方案，其中交通信号控制（TSC）被视为关键组成部分。尽管多智能体强化学习（MARL）算法通过实时决策在优化TSC方面显示出了潜力，但它们的可扩展性和有效性在大规模和复杂环境中常常受到影响。通常，这些限制主要源于环境异质性驱动的状态空间指数增长与当前解决方案有限的建模能力之间的根本性不匹配。为了解决这些问题，本文提出了一种结合动态图神经网络（DGNNs）和拓扑数据分析（TDA）的新型MARL框架，旨在增强环境表示的表达能力并改进智能体协调。此外，受大型语言模型（LLMs）中的专家混合（MoE）架构启发，我们提出了一个拓扑辅助空间模式解耦（TSD）增强的MoE，该方法利用拓扑特征来分离图特征以进行专门化处理，从而提高了模型对动态和异质局部观察的表征能力。TSD模块还被集成到多智能体近端策略优化（MAPPO）算法的策略和价值网络中，进一步提高了决策效率和鲁棒性。在真实世界交通场景上的广泛实验，结合全面的理论分析，验证了所提出的框架的优越性能，突显了该模型在处理大规模TSC任务复杂性方面的可扩展性和有效性。

> Intelligent Transportation Systems (ITSs) have emerged as a promising solution towards ameliorating urban traffic congestion, with Traffic Signal Control (TSC) identified as a critical component. Although Multi-Agent Reinforcement Learning (MARL) algorithms have shown potential in optimizing TSC through real-time decision-making, their scalability and effectiveness often suffer from large-scale and complex environments. Typically, these limitations primarily stem from a fundamental mismatch between the exponential growth of the state space driven by the environmental heterogeneities and the limited modeling capacity of current solutions. To address these issues, this paper introduces a novel MARL framework that integrates Dynamic Graph Neural Networks (DGNNs) and Topological Data Analysis (TDA), aiming to enhance the expressiveness of environmental representations and improve agent coordination. Furthermore, inspired by the Mixture of Experts (MoE) architecture in Large Language Models (LLMs), a topology-assisted spatial pattern disentangling (TSD)-enhanced MoE is proposed, which leverages topological signatures to decouple graph features for specialized processing, thus improving the model's ability to characterize dynamic and heterogeneous local observations. The TSD module is also integrated into the policy and value networks of the Multi-agent Proximal Policy Optimization (MAPPO) algorithm, further improving decision-making efficiency and robustness. Extensive experiments conducted on real-world traffic scenarios, together with comprehensive theoretical analysis, validate the superior performance of the proposed framework, highlighting the model's scalability and effectiveness in addressing the complexities of large-scale TSC tasks.

[Arxiv](https://arxiv.org/abs/2506.12453)