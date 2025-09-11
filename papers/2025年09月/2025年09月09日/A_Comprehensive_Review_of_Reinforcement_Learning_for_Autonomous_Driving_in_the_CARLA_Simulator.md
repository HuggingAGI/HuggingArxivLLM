# CARLA模拟器下自动驾驶强化学习的综合综述

发布时间：2025年09月09日

`强化学习` `交通运输`

> A Comprehensive Review of Reinforcement Learning for Autonomous Driving in the CARLA Simulator

# 摘要

> 自动驾驶研究领域近期纷纷将深度强化学习（RL）视为数据驱动决策的理想框架，然而对于这些算法当前的应用方式、基准测试及评估情况，我们仍缺乏清晰全貌。本综述通过系统分析约100篇在开源CARLA模拟器中训练、测试或验证RL策略的同行评审论文，填补了这一空白。我们首先按算法家族（无模型、基于模型、分层和混合）对文献分类并统计其应用普及度，结果显示超80%的现有研究仍依赖DQN、PPO和SAC等无模型方法。接着，我们解析了各研究中五花八门的状态、动作与奖励设计方案，剖析了不同研究中传感器模态（RGB、LiDAR、鸟瞰图、语义地图及CARLA运动学状态）、控制抽象（离散与连续）及奖励塑造的选择逻辑。我们还梳理了CARLA基准测试中常用的评估指标（成功率、碰撞率、车道偏离、驾驶分数）以及城镇、场景和交通配置，勾勒出评估场景全貌。而稀疏奖励、仿真到现实迁移、安全保障及行为多样性有限等核心挑战，则被提炼为亟待探索的开放研究问题，同时展望了基于模型的RL、元学习及更丰富的多智能体仿真等前沿方向。本综述通过构建统一分类体系、呈现定量统计数据并批判性讨论现有局限，力求为新手提供参考指南，同时为推动基于RL的自动驾驶走向实际部署绘制路线图。

> Autonomous-driving research has recently embraced deep Reinforcement Learning (RL) as a promising framework for data-driven decision making, yet a clear picture of how these algorithms are currently employed, benchmarked and evaluated is still missing. This survey fills that gap by systematically analysing around 100 peer-reviewed papers that train, test or validate RL policies inside the open-source CARLA simulator. We first categorize the literature by algorithmic family model-free, model-based, hierarchical, and hybrid and quantify their prevalence, highlighting that more than 80% of existing studies still rely on model-free methods such as DQN, PPO and SAC. Next, we explain the diverse state, action and reward formulations adopted across works, illustrating how choices of sensor modality (RGB, LiDAR, BEV, semantic maps, and carla kinematics states), control abstraction (discrete vs. continuous) and reward shaping are used across various literature. We also consolidate the evaluation landscape by listing the most common metrics (success rate, collision rate, lane deviation, driving score) and the towns, scenarios and traffic configurations used in CARLA benchmarks. Persistent challenges including sparse rewards, sim-to-real transfer, safety guarantees and limited behaviour diversity are distilled into a set of open research questions, and promising directions such as model-based RL, meta-learning and richer multi-agent simulations are outlined. By providing a unified taxonomy, quantitative statistics and a critical discussion of limitations, this review aims to serve both as a reference for newcomers and as a roadmap for advancing RL-based autonomous driving toward real-world deployment.

[Arxiv](https://arxiv.org/abs/2509.08221)