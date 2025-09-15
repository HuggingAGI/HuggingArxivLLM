# 6G边缘网络中隐私保护与能量感知资源管理的联邦多智能体强化学习

发布时间：2025年09月12日

`强化学习` `基础理论`

> Federated Multi-Agent Reinforcement Learning for Privacy-Preserving and Energy-Aware Resource Management in 6G Edge Networks

# 摘要

> 随着第六代（6G）网络迈向超密集、智能边缘环境，在严格的隐私、移动性及能源约束下，高效的资源管理已成为关键。本文提出了一种新颖的联邦多智能体强化学习（Fed-MARL）框架，其整合了MAC层与应用层的跨层编排，旨在为异构边缘设备实现高能效、隐私保护及实时资源管理。每个智能体利用深度循环Q网络（DRQN），基于本地观测（如队列长度、能量、CPU使用率及移动性）学习去中心化策略，以实现任务卸载、频谱接入和CPU能量自适应。为保障隐私，我们提出了一种基于椭圆曲线Diffie-Hellman密钥交换的安全聚合协议，该协议可在不向半诚实对手泄露原始数据的前提下，确保模型更新的准确性。我们将资源管理问题建模为部分可观测多智能体马尔可夫决策过程（POMMDP），该过程具有多目标奖励函数，能够在6G特定服务要求（如URLLC、eMBB和mMTC）下联合优化延迟、能量效率、频谱效率、公平性及可靠性。仿真结果表明，Fed-MARL在任务成功率、延迟、能量效率及公平性方面均优于集中式MARL和启发式基线，同时在动态、资源受限的6G边缘网络中实现了强大的隐私保护和可扩展性。

> As sixth-generation (6G) networks move toward ultra-dense, intelligent edge environments, efficient resource management under stringent privacy, mobility, and energy constraints becomes critical. This paper introduces a novel Federated Multi-Agent Reinforcement Learning (Fed-MARL) framework that incorporates cross-layer orchestration of both the MAC layer and application layer for energy-efficient, privacy-preserving, and real-time resource management across heterogeneous edge devices. Each agent uses a Deep Recurrent Q-Network (DRQN) to learn decentralized policies for task offloading, spectrum access, and CPU energy adaptation based on local observations (e.g., queue length, energy, CPU usage, and mobility). To protect privacy, we introduce a secure aggregation protocol based on elliptic curve Diffie Hellman key exchange, which ensures accurate model updates without exposing raw data to semi-honest adversaries. We formulate the resource management problem as a partially observable multi-agent Markov decision process (POMMDP) with a multi-objective reward function that jointly optimizes latency, energy efficiency, spectral efficiency, fairness, and reliability under 6G-specific service requirements such as URLLC, eMBB, and mMTC. Simulation results demonstrate that Fed-MARL outperforms centralized MARL and heuristic baselines in task success rate, latency, energy efficiency, and fairness, while ensuring robust privacy protection and scalability in dynamic, resource-constrained 6G edge networks.

[Arxiv](https://arxiv.org/abs/2509.10163)