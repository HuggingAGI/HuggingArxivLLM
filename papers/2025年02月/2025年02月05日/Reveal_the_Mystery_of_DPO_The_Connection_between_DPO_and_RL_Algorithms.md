# 揭秘DPO：DPO与RL算法的关联

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要讨论了基于人类反馈的强化学习（RLHF）算法，特别是直接偏好优化（DPO）和近端策略优化（PPO）之间的差异和关系。论文通过分析损失函数的构建、算法收敛的目标分布以及关键组件的影响，深化了对这些算法的理解。这些内容属于对大型语言模型（LLMs）的理论研究，特别是关于如何通过算法改进模型的安全性和与人类偏好的一致性。因此，这篇论文应归类为“LLM理论”。` `人工智能`

> Reveal the Mystery of DPO: The Connection between DPO and RL Algorithms

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，基于人类反馈的强化学习（RLHF）算法层出不穷，旨在提升模型的安全性和与人类偏好的一致性。这些算法可分为两大类：基于演员-评论家的近端策略优化（PPO）和基于对齐的直接偏好优化（DPO）。DPO与PPO之间的差异，如DPO使用人类偏好数据驱动的分类损失，引发了DPO是否应归类为强化学习（RL）算法的争议。为澄清这一困惑，我们聚焦于DPO、RL及其他RLHF算法的三个关键方面：（1）损失函数的构建；（2）算法收敛的目标分布；（3）损失函数中关键组件的影响。具体而言，我们首先基于损失函数的构建，建立了一个名为UDRRA的统一框架，将这些算法串联起来。随后，我们在该框架内揭示了它们的目标策略分布。最后，我们深入研究了DPO的关键组件，探讨其对收敛速度的影响。本研究深化了对DPO、RL及其他RLHF算法关系的理解，为改进现有算法提供了新的视角。

> With the rapid development of Large Language Models (LLMs), numerous Reinforcement Learning from Human Feedback (RLHF) algorithms have been introduced to improve model safety and alignment with human preferences. These algorithms can be divided into two main frameworks based on whether they require an explicit reward (or value) function for training: actor-critic-based Proximal Policy Optimization (PPO) and alignment-based Direct Preference Optimization (DPO). The mismatch between DPO and PPO, such as DPO's use of a classification loss driven by human-preferred data, has raised confusion about whether DPO should be classified as a Reinforcement Learning (RL) algorithm. To address these ambiguities, we focus on three key aspects related to DPO, RL, and other RLHF algorithms: (1) the construction of the loss function; (2) the target distribution at which the algorithm converges; (3) the impact of key components within the loss function. Specifically, we first establish a unified framework named UDRRA connecting these algorithms based on the construction of their loss functions. Next, we uncover their target policy distributions within this framework. Finally, we investigate the critical components of DPO to understand their impact on the convergence rate. Our work provides a deeper understanding of the relationship between DPO, RL, and other RLHF algorithms, offering new insights for improving existing algorithms.

[Arxiv](https://arxiv.org/abs/2502.03095)