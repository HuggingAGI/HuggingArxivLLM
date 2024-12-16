# 用于大规模多智能体控制的分布式差分动态规划架构

发布时间：2022年07月27日

`Agent` `机器人` `多智能体控制`

> Distributed Differential Dynamic Programming Architectures for Large-Scale Multi-Agent Control

# 摘要

> 摘要：在本文中，我们针对机器人中的多智能体非线性最优控制问题，提出了两个全新的分散式优化框架。此工作旨在构建兼具微分动态规划（DDP）的计算效率与可扩展性，以及交替方向乘子法（ADMM）的分布式特性的架构。为此，引入了两个框架。其一为嵌套分布式DDP（ND-DDP），这是一个三级架构，采用ADMM促使所有智能体达成共识，利用增广拉格朗日层满足局部约束，以DDP作为每个智能体的优化器。第二种方法中，共识和局部约束均通过ADMM处理，形成了名为合并分布式DDP（MD-DDP）的两级架构，进一步降低了计算复杂度。两个框架均完全分散，所有计算均可在智能体间并行开展，且仅需本地通信。扩展至数千辆车和数百架无人机的仿真结果验证了这些方法的有效性。同时，还展现了相较于集中式DDP和集中/分散式二次规划，其在大规模系统中的出色可扩展性。最后，多机器人平台上的硬件实验证明了所提算法的适用性，也突显了优化反馈策略以增强应对不确定性的鲁棒性的重要性。包含所有结果的视频可在这个https URL获取。

> 
Abstract:In this paper, we propose two novel decentralized optimization frameworks for multi-agent nonlinear optimal control problems in robotics. The aim of this work is to suggest architectures that inherit the computational efficiency and scalability of Differential Dynamic Programming (DDP) and the distributed nature of the Alternating Direction Method of Multipliers (ADMM). In this direction, two frameworks are introduced. The first one called Nested Distributed DDP (ND-DDP), is a three-level architecture which employs ADMM for enforcing a consensus between all agents, an augmented Lagrangian layer for satisfying local constraints and DDP as each agent's optimizer. In the second approach, both consensus and local constraints are handled with ADMM, yielding a two-level architecture called Merged Distributed DDP (MD-DDP), which further reduces computational complexity. Both frameworks are fully decentralized since all computations are parallelizable among the agents and only local communication is necessary. Simulation results that scale up to thousands of vehicles and hundreds of drones verify the effectiveness of the methods. Superior scalability to large-scale systems against centralized DDP and centralized/decentralized sequential quadratic programming is also illustrated. Finally, hardware experiments on a multi-robot platform demonstrate the applicability of the proposed algorithms, while highlighting the importance of optimizing for feedback policies to increase robustness against uncertainty. A video including all results is available in this https URL.
    

[Arxiv](https://arxiv.org/pdf/2207.13255)