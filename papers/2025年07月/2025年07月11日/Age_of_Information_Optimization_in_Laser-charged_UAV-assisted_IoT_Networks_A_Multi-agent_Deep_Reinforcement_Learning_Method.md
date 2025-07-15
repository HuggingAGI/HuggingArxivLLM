# 激光充电无人机辅助物联网网络中的信息年龄优化：基于多智能体深度强化学习的方法

发布时间：2025年07月11日

`Agent` `无人机` `物联网`

> Age of Information Optimization in Laser-charged UAV-assisted IoT Networks: A Multi-agent Deep Reinforcement Learning Method

# 摘要

> 无人机与物联网的融合为高效数据采集带来了革命性解决方案，但无人机有限的能源容量仍是亟待攻克的难题。为此，我们提出了一种基于激光束导向器（LBDs）的无线充电技术，使无人机在运行中即可实现充电，从而无需频繁返回充电站，持续高效地完成数据采集任务。本研究聚焦于LBD供电的无人机辅助物联网网络中的信息年龄（AoI）优化问题，探讨多架无人机在激光充电的同时如何高效采集分布式物联网数据。我们构建了一个联合优化问题，目标是在确定最优无人机轨迹和激光充电策略的同时，实现峰值AoI的最小化。该问题因非凸特性、复杂的时序依赖性以及数据采集效率与能源消耗之间的平衡需求而极具挑战性。为此，我们提出了一种新型的多智能体近端策略优化框架——MAPPO-TM。该框架通过引入时间记忆机制捕捉无人机运行的动态特性，并在全局系统目标的指导下，通过去中心化学习实现多架无人机之间的高效协同。仿真结果表明，与传统方法相比，MAPPO-TM算法在峰值AoI最小化和能量效率方面表现优异，峰值AoI甚至可降低15.1%。

> The integration of unmanned aerial vehicles (UAVs) with Internet of Things (IoT) networks offers promising solutions for efficient data collection. However, the limited energy capacity of UAVs remains a significant challenge. In this case, laser beam directors (LBDs) have emerged as an effective technology for wireless charging of UAVs during operation, thereby enabling sustained data collection without frequent returns to charging stations (CSs). In this work, we investigate the age of information (AoI) optimization in LBD-powered UAV-assisted IoT networks, where multiple UAVs collect data from distributed IoTs while being recharged by laser beams. We formulate a joint optimization problem that aims to minimize the peak AoI while determining optimal UAV trajectories and laser charging strategies. This problem is particularly challenging due to its non-convex nature, complex temporal dependencies, and the need to balance data collection efficiency with energy consumption constraints. To address these challenges, we propose a novel multi-agent proximal policy optimization with temporal memory and multi-agent coordination (MAPPO-TM) framework. Specifically, MAPPO-TM incorporates temporal memory mechanisms to capture the dynamic nature of UAV operations and facilitates effective coordination among multiple UAVs through decentralized learning while considering global system objectives. Simulation results demonstrate that the proposed MAPPO-TM algorithm outperforms conventional approaches in terms of peak AoI minimization and energy efficiency. Ideally, the proposed algorithm achieves up to 15.1% reduction in peak AoI compared to conventional multi-agent deep reinforcement learning (MADRL) methods.

[Arxiv](https://arxiv.org/abs/2507.08429)