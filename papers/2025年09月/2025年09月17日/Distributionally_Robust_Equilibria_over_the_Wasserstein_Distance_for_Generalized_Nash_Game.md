# 广义纳什博弈中基于Wasserstein距离的分布鲁棒均衡

发布时间：2025年09月17日

`Agent` `能源与环保`

> Distributionally Robust Equilibria over the Wasserstein Distance for Generalized Nash Game

# 摘要

> 广义纳什均衡问题（GNEP）是多自利智能体协同决策场景中的基础模型，广泛应用于各类实际问题。本文针对GNEP引入共享分布式鲁棒机会约束（DRCCs），旨在有效处理实际场景中不可避免的不确定性。DRCCs基于Wasserstein球定义，即便样本数据有限，仍可对其进行明确刻画。为求解GNEP的均衡，我们提出一种精确转化方法：借助Nikaido-Isoda函数，将原问题中计算难处理的部分转化为确定性模型。具体地，我们证明：当所有智能体的目标函数对各自变量均为二次形式时，均衡解可通过求解典型的混合整数非线性规划（MINLP）问题得到——该问题中整数变量与连续变量在目标函数和约束条件下均实现解耦。这种结构大幅提升了计算易处理性，充电站定价问题的案例研究验证了这一点。

> Generalized Nash equilibrium problem (GNEP) is fundamental for practical applications where multiple self-interested agents work together to make optimal decisions. In this work, we study GNEP with shared distributionally robust chance constraints (DRCCs) for incorporating inevitable uncertainties. The DRCCs are defined over the Wasserstein ball, which can be explicitly characterized even with limited sample data. To determine the equilibrium of the GNEP, we propose an exact approach to transform the original computationally intractable problem into a deterministic formulation using the Nikaido-Isoda function. Specifically, we show that when all agents' objectives are quadratic in their respective variables, the equilibrium can be obtained by solving a typical mixed-integer nonlinear programming (MINLP) problem, where the integer and continuous variables are decoupled in both the objective function and the constraints. This structure significantly improves computational tractability, as demonstrated through a case study on the charging station pricing problem.

[Arxiv](https://arxiv.org/abs/2509.13985)