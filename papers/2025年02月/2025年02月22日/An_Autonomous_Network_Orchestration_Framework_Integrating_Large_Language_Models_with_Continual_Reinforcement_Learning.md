# 提出一种结合大型语言模型与持续强化学习的自主网络编排框架

发布时间：2025年02月22日

`LLM应用` `通信技术` `天地一体化网络`

> An Autonomous Network Orchestration Framework Integrating Large Language Models with Continual Reinforcement Learning

# 摘要

> 6G网络的目标是实现全球覆盖、海量连接以及超严格的性能要求。天地一体化网络（SAGINs）和语义通信（SemCom）是实现这些目标的关键技术，但它们在资源编排方面带来了巨大挑战。从机器人研究中汲取灵感，我们提出了一种基于大型语言模型（LLMs）的解决方案。尽管LLMs在网络编排中的应用近期受到关注，但现有方法尚未充分解决LLMs的幻觉问题及其对网络动态的适应性。为解决这一问题，本文提出了一种名为自主强化协调（ARC）的框架，用于支持语义通信的天地一体化网络。该框架通过基于LLMs的增强型检索生成器（RAG）实时监控服务、用户和资源，并对收集到的数据进行处理，同时层次化动作规划器（HAP）负责资源编排。ARC将编排任务分为两个层级，利用LLMs进行高层规划，并通过强化学习（RL）代理执行低层决策，这一设计与专家混合（MoE）的概念相契合。LLMs通过对比学习增强的链式推理（CoT）实现小样本学习，而RL代理则采用回放缓冲区管理进行持续学习，从而确保系统在效率、准确性和适应性方面达到最优。本文通过模拟实验验证了ARC的有效性，并对未来可能的研究方向进行了全面探讨，以进一步提升和优化ARC框架。

> 6G networks aim to achieve global coverage, massive connectivity, and ultra-stringent requirements. Space-Air-Ground Integrated Networks (SAGINs) and Semantic Communication (SemCom) are essential for realizing these goals, yet they introduce considerable complexity in resource orchestration. Drawing inspiration from research in robotics, a viable solution to manage this complexity is the application of Large Language Models (LLMs). Although the use of LLMs in network orchestration has recently gained attention, existing solutions have not sufficiently addressed LLM hallucinations or their adaptation to network dynamics. To address this gap, this paper proposes a framework called Autonomous Reinforcement Coordination (ARC) for a SemCom-enabled SAGIN. This framework employs an LLM-based Retrieval-Augmented Generator (RAG) monitors services, users, and resources and processes the collected data, while a Hierarchical Action Planner (HAP) orchestrates resources. ARC decomposes orchestration into two tiers, utilizing LLMs for high-level planning and Reinforcement Learning (RL) agents for low-level decision-making, in alignment with the Mixture of Experts (MoE) concept. The LLMs utilize Chain-of-Thought (CoT) reasoning for few-shot learning, empowered by contrastive learning, while the RL agents employ replay buffer management for continual learning, thereby achieving efficiency, accuracy, and adaptability. Simulations are provided to demonstrate the effectiveness of ARC, along with a comprehensive discussion on potential future research directions to enhance and upgrade ARC.

[Arxiv](https://arxiv.org/abs/2502.16198)