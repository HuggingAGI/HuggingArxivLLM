# 汤普森采样在在线RLHF中的应用与泛化函数近似

发布时间：2025年05月29日

`LLM理论` `机器学习`

> Thompson Sampling in Online RLHF with General Function Approximation

# 摘要

> 基于人类反馈的强化学习（RLHF）在使大型语言模型（LLMs）与人类偏好对齐方面取得了显著的实证成功。因此，从理论上研究RLHF算法的统计效率具有重要意义。本研究聚焦于在线RLHF设置，其中偏好数据在学习过程中逐步揭示，并深入探讨动作值函数近似。我们设计了一种基于汤普森采样灵感的无模型后验采样算法，用于在线RLHF，并提供了其理论保证。具体而言，我们采用贝尔曼混杂（BE）维度作为函数类的复杂度度量，并为所提出的算法建立了$O(\sqrt{T})$的遗憾上界，其中其他乘法因子依赖于时间范围、BE维度和函数类的对数分段数。此外，在分析中，我们首先基于最大似然估计器（MLE）的泛化界限，建立了平方贝尔曼误差界的集中不等式，这在获得混杂型遗憾界中起到了关键作用，并且可能具有独立的研究价值。


> Reinforcement learning from human feedback (RLHF) has achieved great empirical success in aligning large language models (LLMs) with human preference, and it is of great importance to study the statistical efficiency of RLHF algorithms from a theoretical perspective. In this work, we consider the online RLHF setting where the preference data is revealed during the learning process and study action value function approximation. We design a model-free posterior sampling algorithm for online RLHF inspired by Thompson sampling and provide its theoretical guarantee. Specifically, we adopt Bellman eluder (BE) dimension as the complexity measure of the function class and establish $O(\sqrt{T})$ regret bound for the proposed algorithm with other multiplicative factor depending on the horizon, BE dimension and the $log$-bracketing number of the function class. Further, in the analysis, we first establish the concentration-type inequality of the squared Bellman error bound based on the maximum likelihood estimator (MLE) generalization bound, which plays the crucial rules in obtaining the eluder-type regret bound and may be of independent interest.

[Arxiv](https://arxiv.org/abs/2505.23927)