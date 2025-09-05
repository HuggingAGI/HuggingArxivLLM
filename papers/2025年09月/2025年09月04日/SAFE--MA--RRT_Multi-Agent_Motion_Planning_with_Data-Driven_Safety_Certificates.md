# SAFE--MA--RRT：数据驱动安全证书的多智能体运动规划

发布时间：2025年09月04日

`Agent` `工业与制造`

> SAFE--MA--RRT: Multi-Agent Motion Planning with Data-Driven Safety Certificates

# 摘要

> 本文针对在共享且布满障碍物的工作空间中运行、且无法获取显式系统模型的同构线性多智能体系统，提出了一种完全数据驱动的运动规划框架。每个智能体通过求解凸半定规划从实验数据中独立学习闭环行为，该规划可生成局部不变椭球及相应的状态反馈增益。这些椭球以网格航点为中心，能验证短程过渡的动态可行性并界定安全操作区域。基于采样的规划器构建此类航点树，仅当相邻椭球重叠时才允许过渡，以此确保不变椭球间的过渡及持续安全性。所有智能体同步扩展各自的树，并通过时空预留表协调，该表通过避免同时占用和正面碰撞来保障智能体间安全。树中每条成功的边都配有独立的局部控制器，可在运行时无需重新求解优化问题即可执行。生成的轨迹不仅动态可行，而且在环境约束和智能体间碰撞方面均具有可证明的安全性。仿真结果表明，该方法仅借助数据和凸优化工具，就能在共享动力学与约束条件下有效为多智能体合成同步且安全的轨迹。

> This paper proposes a fully data-driven motion-planning framework for homogeneous linear multi-agent systems that operate in shared, obstacle-filled workspaces without access to explicit system models. Each agent independently learns its closed-loop behavior from experimental data by solving convex semidefinite programs that generate locally invariant ellipsoids and corresponding state-feedback gains. These ellipsoids, centered along grid-based waypoints, certify the dynamic feasibility of short-range transitions and define safe regions of operation. A sampling-based planner constructs a tree of such waypoints, where transitions are allowed only when adjacent ellipsoids overlap, ensuring invariant-to-invariant transitions and continuous safety. All agents expand their trees simultaneously and are coordinated through a space-time reservation table that guarantees inter-agent safety by preventing simultaneous occupancy and head-on collisions. Each successful edge in the tree is equipped with its own local controller, enabling execution without re-solving optimization problems at runtime. The resulting trajectories are not only dynamically feasible but also provably safe with respect to both environmental constraints and inter-agent collisions. Simulation results demonstrate the effectiveness of the approach in synthesizing synchronized, safe trajectories for multiple agents under shared dynamics and constraints, using only data and convex optimization tools.

[Arxiv](https://arxiv.org/abs/2509.04413)