# 混合强化学习与搜索在飞行轨迹规划中的应用

发布时间：2025年09月04日

`强化学习` `交通运输`

> Hybrid Reinforcement Learning and Search for Flight Trajectory Planning

# 摘要

> 本文将强化学习（RL）与基于搜索的路径规划器相结合，旨在加速客机飞行路径优化——在紧急场景中，快速重新规划路线往往起着关键作用。其核心思路是训练RL智能体，根据位置和大气数据预计算近最优路径，再在运行时利用这些路径约束底层路径规划求解器，使其在初始猜测值的一定范围内找到解决方案。这种方法能有效缩减求解器的搜索空间，大幅提升路线优化效率。虽然无法确保全局最优，但基于空客飞机性能模型的实证结果显示，燃油消耗与无约束求解器的结果几乎一致，偏差通常控制在1%以内；与此同时，计算速度较单独使用传统求解器最多提升50%。

> This paper explores the combination of Reinforcement Learning (RL) and search-based path planners to speed up the optimization of flight paths for airliners, where in case of emergency a fast route re-calculation can be crucial. The fundamental idea is to train an RL Agent to pre-compute near-optimal paths based on location and atmospheric data and use those at runtime to constrain the underlying path planning solver and find a solution within a certain distance from the initial guess. The approach effectively reduces the size of the solver's search space, significantly speeding up route optimization. Although global optimality is not guaranteed, empirical results conducted with Airbus aircraft's performance models show that fuel consumption remains nearly identical to that of an unconstrained solver, with deviations typically within 1%. At the same time, computation speed can be improved by up to 50% as compared to using a conventional solver alone.

[Arxiv](https://arxiv.org/abs/2509.04100)