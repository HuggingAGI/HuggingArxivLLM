# 面向公交车队控制的单智能体鲁棒深度强化学习

发布时间：2025年08月28日

`强化学习` `交通运输`

> Single Agent Robust Deep Reinforcement Learning for Bus Fleet Control

# 摘要

> 受交通状况和乘客需求随机性的影响，公交车辆集群仍是城市公共交通的一大难题。传统解决方案在环线场景中采用多智能体强化学习（MARL），却忽略了实际运营中异构路线、时刻表、波动需求及车队规模差异等特点。我们提出了一种新的单智能体强化学习（RL）公交驻站控制框架，在近现实模拟环境下可规避MARL的数据不平衡和收敛难题。我们构建了一个具备动态乘客需求的双向时刻表网络。核心创新点在于，通过在状态空间中除纳入数值特征（发车间隔、载客量、速度）外，还增加类别标识符（车辆ID、站点ID、时间段），将多智能体问题转化为单智能体问题。这种高维编码使单智能体策略能够捕捉智能体间的依赖关系，其原理类似于将不可分输入投影到更高维空间。我们进一步设计了与运营目标匹配的结构化奖励函数：不再对发车间隔偏差施加指数惩罚，而是采用脊形奖励平衡均匀发车间隔与时刻表准点率。实验表明，我们改进的软actor-critic（SAC）算法性能优于包括MADDPG在内的基准算法，且更稳定（例如，随机条件下性能值为-430k，而MADDPG为-530k）。这些结果表明，通过类别结构化和时刻表感知奖励增强的单智能体深度强化学习，能够有效管理非环线现实场景中的公交驻站问题。这种范式为MARL框架提供了稳健且可扩展的替代方案，尤其适用于智能体特定经验不平衡的场景。

> Bus bunching remains a challenge for urban transit due to stochastic traffic and passenger demand. Traditional solutions rely on multi-agent reinforcement learning (MARL) in loop-line settings, which overlook realistic operations characterized by heterogeneous routes, timetables, fluctuating demand, and varying fleet sizes. We propose a novel single-agent reinforcement learning (RL) framework for bus holding control that avoids the data imbalance and convergence issues of MARL under near-realistic simulation. A bidirectional timetabled network with dynamic passenger demand is constructed. The key innovation is reformulating the multi-agent problem into a single-agent one by augmenting the state space with categorical identifiers (vehicle ID, station ID, time period) in addition to numerical features (headway, occupancy, velocity). This high-dimensional encoding enables single-agent policies to capture inter-agent dependencies, analogous to projecting non-separable inputs into a higher-dimensional space. We further design a structured reward function aligned with operational goals: instead of exponential penalties on headway deviations, a ridge-shaped reward balances uniform headways and schedule adherence. Experiments show that our modified soft actor-critic (SAC) achieves more stable and superior performance than benchmarks, including MADDPG (e.g., -430k vs. -530k under stochastic conditions). These results demonstrate that single-agent deep RL, when enhanced with categorical structuring and schedule-aware rewards, can effectively manage bus holding in non-loop, real-world contexts. This paradigm offers a robust, scalable alternative to MARL frameworks, particularly where agent-specific experiences are imbalanced.

[Arxiv](https://arxiv.org/abs/2508.20784)