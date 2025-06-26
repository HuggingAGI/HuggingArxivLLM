# # **AnyMAC**: 通过预测下一个智能体实现连锁式灵活多智能体协作

发布时间：2025年06月21日

`Agent` `多智能体协作` `智能体交流`

> AnyMAC: Cascading Flexible Multi-Agent Collaboration via Next-Agent Prediction

# 摘要

> 大型语言模型（LLM）驱动的多智能体协作研究取得显著进展，揭示了结构化交流在集体智能中的巨大潜力。然而，现有的方法大多依赖于静态或基于图的智能体间拓扑结构，在交流的适应性和灵活性方面存在明显局限。本研究提出了一种创新框架，采用序列结构代替传统的图结构来重新构思多智能体协调机制，从而为多智能体交流提供了更大的拓扑空间。我们的方法主要关注两个核心方向：（1）下一步智能体预测，旨在每一步选择最合适的智能体角色；（2）下一步上下文选择（NCS），使每个智能体能够从任何之前的步骤中选择性地获取相关信息。这些组件共同构建了任务自适应的交流管道，支持智能体角色的灵活性和全局信息流动。在多个基准测试中，我们的方法不仅表现出色，还显著降低了交流开销。

> Recent progress in large language model (LLM)-based multi-agent collaboration highlights the power of structured communication in enabling collective intelligence. However, existing methods largely rely on static or graph-based inter-agent topologies, lacking the potential adaptability and flexibility in communication. In this work, we propose a new framework that rethinks multi-agent coordination through a sequential structure rather than a graph structure, offering a significantly larger topology space for multi-agent communication. Our method focuses on two key directions: (1) Next-Agent Prediction, which selects the most suitable agent role at each step, and (2) Next-Context Selection (NCS), which enables each agent to selectively access relevant information from any previous step. Together, these components construct task-adaptive communication pipelines that support both role flexibility and global information flow. Extensive evaluations across multiple benchmarks demonstrate that our approach achieves superior performance while substantially reducing communication overhead.

[Arxiv](https://arxiv.org/abs/2506.17784)