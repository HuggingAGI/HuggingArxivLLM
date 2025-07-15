# IteraOptiRacing：一个统一的规划控制框架，面向实时自动驾驶赛车，实现迭代最优性能。

发布时间：2025年07月13日

`Agent` `自动驾驶` `赛车竞技`

> IteraOptiRacing: A Unified Planning-Control Framework for Real-time Autonomous Racing for Iterative Optimal Performance

# 摘要

> 本文提出了一种名为IteraOptiRacing的统一规划控制策略，专为自动驾驶赛车环境设计，帮助 ego 赛车在与其他赛车竞争中占据优势。该策略基于迭代任务的迭代线性二次调节器（i2LQR），能够在复杂赛道环境中有效提升圈速表现。通过迭代分析 ego 赛车的历史数据，该策略同时兼顾多辆移动障碍物的避障需求和时间成本的优化，最终生成无碰撞且时间最优的行驶轨迹。得益于算法的低计算负担和对并行计算的友好支持，该策略能够在竞技赛车场景中实现实时操作。为了验证其性能，我们在高保真模拟器中进行了大量测试，模拟场景包含多个随机生成的动态代理。实验结果表明，与现有方法相比，所提出的策略在所有随机生成的自动驾驶赛车场景中表现更优，显著提升了 ego 赛车的操控性能。

> This paper presents a unified planning-control strategy for competing with other racing cars called IteraOptiRacing in autonomous racing environments. This unified strategy is proposed based on Iterative Linear Quadratic Regulator for Iterative Tasks (i2LQR), which can improve lap time performance in the presence of surrounding racing obstacles. By iteratively using the ego car's historical data, both obstacle avoidance for multiple moving cars and time cost optimization are considered in this unified strategy, resulting in collision-free and time-optimal generated trajectories. The algorithm's constant low computation burden and suitability for parallel computing enable real-time operation in competitive racing scenarios. To validate its performance, simulations in a high-fidelity simulator are conducted with multiple randomly generated dynamic agents on the track. Results show that the proposed strategy outperforms existing methods across all randomly generated autonomous racing scenarios, enabling enhanced maneuvering for the ego racing car.

[Arxiv](https://arxiv.org/abs/2507.09714)