# 深度强化学习在Re=1000三维流动分离机翼主动流动控制中的应用

发布时间：2025年09月12日

`强化学习` `工业与制造`

> Deep Reinforcement Learning for Active Flow Control around a Three-Dimensional Flow-Separated Wing at Re = 1,000

# 摘要

> 本研究探索利用深度强化学习（DRL）实现主动流动控制（AFC），旨在减少机翼在大迎角下的气流分离现象。具体来说，DRL智能体负责调控三维NACA0012机翼剖面的气流，在雷诺数Re=1000、迎角AoA=20度的条件下，借助实时气流数据和以提升气动性能为目标的奖励函数，自主确定最优控制策略。该框架通过Redis内存数据库，将GPU加速的计算流体动力学（CFD）求解器SOD2D与TF-Agents DRL库无缝集成，从而实现快速训练。本研究在以往DRL流动控制研究的基础上，进一步展现了DRL在应对复杂气动难题、突破传统AFC方法瓶颈方面的巨大潜力。

> This study explores the use of deep reinforcement learning (DRL) for active flow control (AFC) to reduce flow separation on wings at high angles of attack. Concretely, here the DRL agent controls the flow over the three-dimensional NACA0012 wing section at the Reynolds number Re = 1,000 and angle of attack AoA = 20 degrees, autonomously identifying optimal control actions through real-time flow data and a reward function focused on improving aerodynamic performance. The framework integrates the GPU-accelerated computational fluid dynamics (CFD) solver SOD2D with the TF-Agents DRL library via a Redis in-memory database, enabling rapid training. This work builds on previous DRL flow-control studies, demonstrating DRL potential to address complex aerodynamic challenges and push the boundaries of traditional AFC methods.

[Arxiv](https://arxiv.org/abs/2509.10195)