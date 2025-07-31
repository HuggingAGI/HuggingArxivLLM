# 基于输入凸性动作修正的安全离线强化学习部署

发布时间：2025年07月30日

`Agent` `化学工程` `过程控制`

> Safe Deployment of Offline Reinforcement Learning via Input Convex Action Correction

# 摘要

> # 研究摘要
离线强化学习（Offline RL）为化学过程系统的控制策略开发提供了一种有前景的解决方案，通过历史数据实现控制优化，避免了在线实验的风险和成本。本研究聚焦于离线强化学习在间歇式放热聚合连续搅拌釜式反应器的安全与高效控制中的应用。

我们开发了一个与Gymnasium兼容的仿真环境，精准模拟了反应器的非线性动态特性，包括反应动力学、能量平衡和操作约束。该环境支持三种工业场景：启动、降级切换和升級切换。此外，我们还提供了通过随机调整参数的比例-积分控制器生成的可重复离线数据集，为评估离线强化学习算法在现实过程控制任务中的性能提供了基准。

我们选取行为克隆和隐式Q学习作为基线算法进行评估，揭示了离线代理在实际应用中面临的挑战，包括稳态偏移和接近设定点时的性能下降问题。针对这些挑战，我们创新性地提出了一种部署时安全层，该层利用输入凸神经网络（PICNNs）作为已学习成本模型，通过基于梯度的动作校正实现策略优化。PICNN能够在不重新训练或与环境交互的情况下，实现实时的、可微分的策略动作校正，通过下降一个凸的、状态相关的成本曲面来提升控制性能。

实验结果表明，离线强化学习，特别是结合凸动作校正时，不仅超越了传统控制方法，还在所有场景下保持了系统稳定性。这些发现不仅验证了将离线强化学习与可解释且安全感知的校正相结合在高风险化学过程控制中的可行性，更为工业系统中更可靠的基于数据的自动化奠定了理论和实践基础。

> Offline reinforcement learning (offline RL) offers a promising framework for developing control strategies in chemical process systems using historical data, without the risks or costs of online experimentation. This work investigates the application of offline RL to the safe and efficient control of an exothermic polymerisation continuous stirred-tank reactor. We introduce a Gymnasium-compatible simulation environment that captures the reactor's nonlinear dynamics, including reaction kinetics, energy balances, and operational constraints. The environment supports three industrially relevant scenarios: startup, grade change down, and grade change up. It also includes reproducible offline datasets generated from proportional-integral controllers with randomised tunings, providing a benchmark for evaluating offline RL algorithms in realistic process control tasks.
  We assess behaviour cloning and implicit Q-learning as baseline algorithms, highlighting the challenges offline agents face, including steady-state offsets and degraded performance near setpoints. To address these issues, we propose a novel deployment-time safety layer that performs gradient-based action correction using input convex neural networks (PICNNs) as learned cost models. The PICNN enables real-time, differentiable correction of policy actions by descending a convex, state-conditioned cost surface, without requiring retraining or environment interaction.
  Experimental results show that offline RL, particularly when combined with convex action correction, can outperform traditional control approaches and maintain stability across all scenarios. These findings demonstrate the feasibility of integrating offline RL with interpretable and safety-aware corrections for high-stakes chemical process control, and lay the groundwork for more reliable data-driven automation in industrial systems.

[Arxiv](https://arxiv.org/abs/2507.22640)