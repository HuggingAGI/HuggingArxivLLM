# Pre-DPO：通过引导参考模型优化直接偏好优化中的数据利用率

发布时间：2025年04月22日

`LLM理论` `人工智能` `机器学习`

> Pre-DPO: Improving Data Utilization in Direct Preference Optimization Using a Guiding Reference Model

# 摘要

> 直接偏好优化 (DPO) 通过直接优化人类偏好，无需显式奖励模型，为大型语言模型 (LLMs) 的基于人类反馈的强化学习 (RLHF) 提供了一种更简洁的解决方案。研究发现，在 DPO 训练过程中，参考模型扮演着数据权重调节器的角色。然而，DPO 中常见的策略模型与参考模型初始化相同的做法，不仅导致数据利用率低下，还为性能设定了上限。与此同时，简单偏好优化 (SimPO) 缺少参考模型导致训练鲁棒性下降，并需要更严格的条件以防止灾难性遗忘。为了解决这些问题，我们提出了 Pre-DPO，这是一种简单而有效的基于 DPO 的训练范式。通过引入引导参考模型，Pre-DPO 能够显著提升偏好优化性能。该参考模型能够预见到通过训练偏好数据可实现的最优策略状态，充当一种引导机制，自适应地为更适配模型的样本赋予更高权重，而对较不适配的样本赋予较低权重。在 AlpacaEval 2.0 和 Arena-Hard v0.1 基准测试上的大量实验表明，Pre-DPO 无需依赖外部模型或额外数据，即可持续提升 DPO 和 SimPO 的性能表现。

> Direct Preference Optimization (DPO) simplifies reinforcement learning from human feedback (RLHF) for large language models (LLMs) by directly optimizing human preferences without an explicit reward model. We find that during DPO training, the reference model plays the role of a data weight adjuster. However, the common practice of initializing the policy and reference models identically in DPO can lead to inefficient data utilization and impose a performance ceiling. Meanwhile, the lack of a reference model in Simple Preference Optimization (SimPO) reduces training robustness and necessitates stricter conditions to prevent catastrophic forgetting. In this work, we propose Pre-DPO, a simple yet effective DPO-based training paradigm that enhances preference optimization performance by leveraging a guiding reference model. This reference model provides foresight into the optimal policy state achievable through the training preference data, serving as a guiding mechanism that adaptively assigns higher weights to samples more suitable for the model and lower weights to those less suitable. Extensive experiments on AlpacaEval 2.0 and Arena-Hard v0.1 benchmarks demonstrate that Pre-DPO consistently improves the performance of both DPO and SimPO, without relying on external models or additional data.

[Arxiv](https://arxiv.org/abs/2504.15843)