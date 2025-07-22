# 基于分布式一致性算法的观测器设计，用于方位测量的目标状态估计

发布时间：2025年07月18日

`Agent` `机器人学`

> Distributed consensus-based observer design for target state estimation with bearing measurements

# 摘要

> 本文提出了一种创新的基于分布式共识的观测器设计，使一组智能体能够在无向通信网络中实现目标跟踪，其中目标被建模为任意阶数的积分器链。每个智能体不仅了解自身位置，还能实时测量相对于目标的方位向量。我们首先介绍了一种适用于状态动态为积分器链且测量模型具有特定非线性形式的通用连续时间观测器设计。该设计通过结合创新和共识组件的校正项，使得每个智能体只需向邻居广播部分状态估计，从而有效降低了网络数据流量。为了确保系统的统一指数稳定性，我们引入了一个针对广义观测器形式下非线性闭环系统的新型理论结果，并将其作为主要工具来推导观测器增益的稳定性条件。通过利用正交投影矩阵的特性，我们成功将该设计应用于分布式目标跟踪问题，并得出了明确的稳定性条件，这些条件依赖于目标与智能体之间的几何排列。我们通过一阶、二阶和三阶积分器动力学模型的目标实例，展示了设计过程和稳定性条件的应用。最后，数值实验结果验证了所提算法的有效性。

> This paper introduces a novel distributed consensus-based observer design that enables a group of agents in an undirected communication network to solve the problem of target tracking, where the target is modeled as a chain of integrators of arbitrary order. Each agent is assumed to know its own position and simultaneously measure bearing vectors relative to the target. We start by introducing a general continuous time observer design tailored to systems whose state dynamics are modeled as chains of integrators and whose measurement model follows a particular nonlinear but observer-suited form. This design leverages a correction term that combines innovation and consensus components, allowing each agent to broadcast only a part of the state estimate to its neighbours, which effectively reduces the data flowing across the network. To provide uniform exponential stability guarantees, a novel result for a class of nonlinear closed-loop systems in a generalized observer form is introduced and subsequently used as the main tool to derive stability conditions on the observer gains. Then, by exploring the properties of orthogonal projection matrices, the proposed design is used to solve the distributed target tracking problem and provide explicit stability conditions that depend on the target-agents geometric formation. Practical examples are derived for a target modeled as first-, second-, and third-order integrator dynamics, highlighting the design procedure and the stability conditions imposed. Finally, numerical results showcase the properties of the proposed algorithm.

[Arxiv](https://arxiv.org/abs/2507.14300)