# CorrA：借助大型语言模型助力自动驾驶车辆动态避障

发布时间：2025年03月03日

`LLM应用` `自动驾驶` `控制理论`

> CorrA: Leveraging Large Language Models for Dynamic Obstacle Avoidance of Autonomous Vehicles

# 摘要

> 本文提出Corridor-Agent（CorrA）框架，将大型语言模型（LLMs）与模型预测控制（MPC）相结合，解决自动驾驶车辆的动态避障难题。我们利用LLM的推理能力，生成适合基于sigmoid的边界函数参数，这些函数定义了障碍物周围的无障碍走廊，有效缩减了受控车辆的状态空间。框架根据实时车辆数据动态调整边界，确保无碰撞轨迹，同时兼顾计算效率与轨迹最优性。该问题被建模为最优控制问题，通过微分动态规划（DDP）进行有约束优化求解，并嵌入MPC框架。仿真与实验证明，与基线MPC方法相比，CorrA在复杂动态环境中展现出更优的安全性和效率。

> In this paper, we present Corridor-Agent (CorrA), a framework that integrates large language models (LLMs) with model predictive control (MPC) to address the challenges of dynamic obstacle avoidance in autonomous vehicles. Our approach leverages LLM reasoning ability to generate appropriate parameters for sigmoid-based boundary functions that define safe corridors around obstacles, effectively reducing the state-space of the controlled vehicle. The proposed framework adjusts these boundaries dynamically based on real-time vehicle data that guarantees collision-free trajectories while also ensuring both computational efficiency and trajectory optimality. The problem is formulated as an optimal control problem and solved with differential dynamic programming (DDP) for constrained optimization, and the proposed approach is embedded within an MPC framework. Extensive simulation and real-world experiments demonstrate that the proposed framework achieves superior performance in maintaining safety and efficiency in complex, dynamic environments compared to a baseline MPC approach.

[Arxiv](https://arxiv.org/abs/2503.02076)