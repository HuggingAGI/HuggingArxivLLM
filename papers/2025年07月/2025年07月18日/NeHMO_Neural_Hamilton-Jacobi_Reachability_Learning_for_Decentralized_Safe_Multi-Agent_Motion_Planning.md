# NeHMO：基于神经网络的汉密尔顿-雅可比可达性学习应用于去中心化安全多智能体运动规划。

发布时间：2025年07月18日

`Agent` `机器人学` `多智能体系统`

> NeHMO: Neural Hamilton-Jacobi Reachability Learning for Decentralized Safe Multi-Agent Motion Planning

# 摘要

> 多智能体安全运动规划（MAMP）是机器人学中的重要难题。尽管技术不断进步，现有方法仍面临核心挑战：去中心化算法通常依赖于预测其他智能体行为、共享合约或维持通信来确保安全，而中心化方法则在可扩展性和实时决策方面力不从心。为突破这一瓶颈，我们提出了一种基于神经哈密尔顿-雅可比可达性学习（HJR）的去中心化多智能体运动规划方法。通过可扩展的神经HJR建模，我们成功应对了高维配置空间的挑战，并精确捕捉了智能体间的最坏碰撞与安全约束。进一步，我们开发了一种集成学习HJR解决方案的去中心化轨迹优化框架，实现了MAMP任务的实时求解。实验表明，我们的方法不仅具备出色的可扩展性，而且数据利用效率极高，能够在更高维度且复杂碰撞约束的场景中有效解决MAMP问题。该方法适用于多种动力学系统，包括12维的双臂设置，并在成功应对具有挑战性的MAMP任务方面超越了多种先进方法。更多演示请访问：https://youtu.be/IZiePX0p1Mc.

> Safe Multi-Agent Motion Planning (MAMP) is a significant challenge in robotics. Despite substantial advancements, existing methods often face a dilemma. Decentralized algorithms typically rely on predicting the behavior of other agents, sharing contracts, or maintaining communication for safety, while centralized approaches struggle with scalability and real-time decision-making. To address these challenges, we introduce Neural Hamilton-Jacobi Reachability Learning (HJR) for Decentralized Multi-Agent Motion Planning. Our method provides scalable neural HJR modeling to tackle high-dimensional configuration spaces and capture worst-case collision and safety constraints between agents. We further propose a decentralized trajectory optimization framework that incorporates the learned HJR solutions to solve MAMP tasks in real-time. We demonstrate that our method is both scalable and data-efficient, enabling the solution of MAMP problems in higher-dimensional scenarios with complex collision constraints. Our approach generalizes across various dynamical systems, including a 12-dimensional dual-arm setup, and outperforms a range of state-of-the-art techniques in successfully addressing challenging MAMP tasks. Video demonstrations are available at https://youtu.be/IZiePX0p1Mc.

[Arxiv](https://arxiv.org/abs/2507.13940)