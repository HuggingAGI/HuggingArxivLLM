# 优化通信机制与设备聚类在集群联邦学习中的应用：采用差分隐私

发布时间：2025年07月09日

`其他`

> Optimizing Communication and Device Clustering for Clustered Federated Learning with Differential Privacy

# 摘要

> 本文提出了一种安全且通信高效的集群联邦学习（CFL）设计方案。在我们的模型中，多个具备异构任务处理能力的基站（BSs）与持有非独立同分布（non-IID）数据的多个用户协同完成集成差分隐私（DP）技术的CFL训练。由于每个基站仅能处理部分学习任务，且可用的无线资源块（RBs）数量有限，无法充分满足联邦学习（FL）模型参数传输需求，因此需要对RB分配和用户调度进行联合优化以提升CFL性能。同时，我们考虑的CFL方法要求设备利用自身有限的数据和FL模型信息确定任务身份，这可能带来额外的通信开销。我们建立了一个优化问题，目标是在考虑设备聚类、RB分配、DP噪声以及FL模型传输延迟的情况下，最小化所有学习任务的训练损失。为解决该问题，我们提出了一种新型动态惩罚函数辅助的价值分解多智能体强化学习（DPVD-MARL）算法，使分布式基站能够独立确定其连接用户、RB分配以及连接用户的DP噪声，同时联合优化所有基站上的学习任务训练损失。与现有MARL方法不同，我们提出了一种新型惩罚分配方案，根据无法满足通信约束（如延迟）的设备数量来分配惩罚，这可以引导MARL方案快速找到有效动作，从而提高收敛速度。仿真结果表明，与独立Q学习相比，DPVD-MARL可以将收敛速率提高20%，并将最终累积奖励提升15%。

> In this paper, a secure and communication-efficient clustered federated learning (CFL) design is proposed. In our model, several base stations (BSs) with heterogeneous task-handling capabilities and multiple users with non-independent and identically distributed (non-IID) data jointly perform CFL training incorporating differential privacy (DP) techniques. Since each BS can process only a subset of the learning tasks and has limited wireless resource blocks (RBs) to allocate to users for federated learning (FL) model parameter transmission, it is necessary to jointly optimize RB allocation and user scheduling for CFL performance optimization. Meanwhile, our considered CFL method requires devices to use their limited data and FL model information to determine their task identities, which may introduce additional communication overhead. We formulate an optimization problem whose goal is to minimize the training loss of all learning tasks while considering device clustering, RB allocation, DP noise, and FL model transmission delay. To solve the problem, we propose a novel dynamic penalty function assisted value decomposed multi-agent reinforcement learning (DPVD-MARL) algorithm that enables distributed BSs to independently determine their connected users, RBs, and DP noise of the connected users but jointly minimize the training loss of all learning tasks across all BSs. Different from the existing MARL methods that assign a large penalty for invalid actions, we propose a novel penalty assignment scheme that assigns penalty depending on the number of devices that cannot meet communication constraints (e.g., delay), which can guide the MARL scheme to quickly find valid actions, thus improving the convergence speed. Simulation results show that the DPVD-MARL can improve the convergence rate by up to 20% and the ultimate accumulated rewards by 15% compared to independent Q-learning.

[Arxiv](https://arxiv.org/abs/2507.07320)