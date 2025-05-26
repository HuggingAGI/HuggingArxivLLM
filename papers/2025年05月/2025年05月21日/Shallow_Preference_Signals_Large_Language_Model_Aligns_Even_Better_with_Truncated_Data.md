# 浅层偏好信号：大语言模型与截断数据对齐度更高？

发布时间：2025年05月21日

`LLM理论` `人工智能`

> Shallow Preference Signals: Large Language Model Aligns Even Better with Truncated Data?

# 摘要

> 对齐大型语言模型 (LLMs) 与人类偏好仍是 AI 领域的关键挑战。基于偏好的优化方法，如基于人类反馈的强化学习 (RLHF) 和直接偏好优化 (DPO)，依赖于人类标注的数据集来改善对齐效果。在这项研究中，我们发现现有学习方法的一个关键特性：在偏好的响应中获得的区分信号往往集中在早期的 token 中。我们将这一现象称为浅层偏好信号。

为了探索这一特性，我们系统地在不同点截断偏好数据集，并在截断数据上训练奖励模型和 DPO 模型。令人惊讶的是，仅保留前半部分或更少 token 的截断数据集训练出的模型，其性能与使用完整数据集训练的模型相当甚至更优。例如，基于 Skywork-Reward-Preference-80K-v0.2 数据集训练的奖励模型，在使用 40% 截断数据集时表现优于完整数据集。这一模式在多个数据集上保持一致，表明浅层偏好信号的普遍存在。

我们进一步通过解码策略研究奖励信号的分布。我们提出了两种简单的解码策略，即长度控制解码和 KL 阈值控制解码，这两种策略均受到浅层奖励信号现象的启发，能够利用浅层偏好信号来优化对齐与计算效率之间的平衡。实验结果表明，这些策略的性能甚至更优，再次验证了我们的假设。

浅层偏好信号的现象凸显了 LLM 对齐中潜在的问题：现有的对齐方法往往仅关注响应的初始 token，而未考虑整个响应。这可能导致与现实世界中人类偏好的不一致，从而产生次优的对齐性能。

> Aligning large language models (LLMs) with human preferences remains a key challenge in AI. Preference-based optimization methods, such as Reinforcement Learning with Human Feedback (RLHF) and Direct Preference Optimization (DPO), rely on human-annotated datasets to improve alignment. In this work, we identify a crucial property of the existing learning method: the distinguishing signal obtained in preferred responses is often concentrated in the early tokens. We refer to this as shallow preference signals.
  To explore this property, we systematically truncate preference datasets at various points and train both reward models and DPO models on the truncated data. Surprisingly, models trained on truncated datasets, retaining only the first half or fewer tokens, achieve comparable or even superior performance to those trained on full datasets. For example, a reward model trained on the Skywork-Reward-Preference-80K-v0.2 dataset outperforms the full dataset when trained on a 40\% truncated dataset. This pattern is consistent across multiple datasets, suggesting the widespread presence of shallow preference signals.
  We further investigate the distribution of the reward signal through decoding strategies. We consider two simple decoding strategies motivated by the shallow reward signal observation, namely Length Control Decoding and KL Threshold Control Decoding, which leverage shallow preference signals to optimize the trade-off between alignment and computational efficiency. The performance is even better, which again validates our hypothesis.
  The phenomenon of shallow preference signals highlights potential issues in LLM alignment: existing alignment methods often focus on aligning only the initial tokens of responses, rather than considering the full response. This could lead to discrepancies with real-world human preferences, resulting in suboptimal alignment performance.

[Arxiv](https://arxiv.org/abs/2505.17122)