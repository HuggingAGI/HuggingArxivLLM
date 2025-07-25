# 多智能体引导下的策略优化

发布时间：2025年07月23日

`Agent` `多智能体系统`

> Multi-Agent Guided Policy Optimization

# 摘要

> 由于实际限制，如部分可观测性和有限的通信，集中式训练与分散式执行 (CTDE) 已成为合作型多智能体强化学习 (MARL) 中的主导范式。然而，现有的 CTDE 方法往往未能充分利用集中式训练，或缺乏理论保障。我们提出了多智能体引导策略优化 (MAGPO)，这是一种新型框架，通过将集中式指导与分散式执行相结合，更好地利用集中式训练。MAGPO 使用一种自回归联合策略，实现可扩展的协调探索，并显式地将其与分散式策略对齐，以确保在部分可观测性条件下的可部署性。我们提供了单调策略改进的理论保证，并在 6 个不同环境中的 43 个任务上进行了实证评估。结果表明，MAGPO 一致优于强健的 CTDE 基线方法，并在性能上与完全集中式方法持平或超越，为分散式多智能体学习提供了一种原理性和实用性的解决方案。我们的代码和实验数据可在 https://github.com/liyheng/MAGPO 获取。

> Due to practical constraints such as partial observability and limited communication, Centralized Training with Decentralized Execution (CTDE) has become the dominant paradigm in cooperative Multi-Agent Reinforcement Learning (MARL). However, existing CTDE methods often underutilize centralized training or lack theoretical guarantees. We propose Multi-Agent Guided Policy Optimization (MAGPO), a novel framework that better leverages centralized training by integrating centralized guidance with decentralized execution. MAGPO uses an auto-regressive joint policy for scalable, coordinated exploration and explicitly aligns it with decentralized policies to ensure deployability under partial observability. We provide theoretical guarantees of monotonic policy improvement and empirically evaluate MAGPO on 43 tasks across 6 diverse environments. Results show that MAGPO consistently outperforms strong CTDE baselines and matches or surpasses fully centralized approaches, offering a principled and practical solution for decentralized multi-agent learning. Our code and experimental data can be found in https://github.com/liyheng/MAGPO.

[Arxiv](https://arxiv.org/abs/2507.18059)