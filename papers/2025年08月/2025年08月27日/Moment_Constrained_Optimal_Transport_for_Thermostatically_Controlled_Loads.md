# 面向温控负荷的矩约束最优传输

发布时间：2025年08月27日

`其他` `能源与环保`

> Moment Constrained Optimal Transport for Thermostatically Controlled Loads

# 摘要

> 控制大量恒温控制负载（TCLs）（如热水器）面临着平衡全局约束（例如电网稳定性）与个体需求（例如物理限制和服务质量）的重大挑战。本研究提出一种基于矩约束最优传输（MCOT）的新型框架，用于TCLs的分布式控制。通过将控制问题表述为带矩约束的最优传输问题，我们的方法将全局消耗约束与物理可行性条件融入控制设计。这一高（或无限）维问题可简化为低得多的有限维问题，其结构使得通过生成TCLs轨迹，能够利用蒙特卡洛方法计算梯度。与以往研究不同，我们的MCOT框架允许选择采样规律，从而显著加快计算速度。相较于现有方法，该算法减少了对大量状态空间离散化的需求，大幅降低了计算复杂度。热水器案例的数值实验表明，基于MCOT的方法能有效协调各类约束下的TCLs。我们进一步将该方法扩展至在线场景，并基于SMACH（家庭人类活动多智能体模拟）平台的模拟数据验证了其实际适用性。

> Controlling large populations of thermostatically controlled loads (TCLs), such as water heaters, poses significant challenges due to the need to balance global constraints (e.g., grid stability) with individual requirements (e.g., physical limits and quality of service). In this work, we introduce a novel framework based on Moment Constrained Optimal Transport (MCOT) for distributed control of TCLs. By formulating the control problem as an optimal transport problem with moment constraints, our approach integrates global consumption constraints and physical feasibility conditions into the control design. This problem with high (or infinite) dimensionality can be reduced to a much lower finite-dimensional problem. The structure of this problem allows for computing the gradient with Monte Carlo methods by generating trajectories of TCLs. Contrary to all previous work, in our MCOT framework, it is possible to choose the sampling law, which considerably speeds up the calculations. This algorithm mitigates the need for extensive state-space discretization and significantly reduces computational complexity compared to existing methods. Numerical experiments in a water heater case study demonstrate that our MCOT-based method effectively coordinates TCLs under various constraints. We further extend our approach to an online setting, illustrating its practical applicability on simulated data from the SMACH (Multi-agent Simulation of Human Activity in the Household) platform.

[Arxiv](https://arxiv.org/abs/2508.20059)