# 自适应样本调度在直接偏好优化中的应用

发布时间：2025年06月08日

`LLM理论` `人工智能` `机器学习`

> Adaptive Sample Scheduling for Direct Preference Optimization

# 摘要

> 直接偏好优化 (DPO) 已经成为一种有效对齐大型语言模型 (LLMs) 与人类偏好的方法。然而，其性能高度依赖于人类偏好数据的质量。为了解决这一瓶颈，先前的研究尝试了多种数据选择策略，但这些方法往往忽视了 DPO 过程中语言模型状态的动态变化。%包括主动查询、响应对选择和数据预选择。本文提出一个全新问题：DPO 中的样本调度问题，旨在根据模型状态的动态变化，在整个偏好优化过程中对训练样本进行动态自适应调度。为了解决这一问题，我们提出了一种高效且有效的算法 SamS，该算法基于 LLM 的学习反馈，在每个训练批次中自适应地选择样本，以最大化潜在的泛化性能。值得注意的是，在不修改核心 DPO 算法的情况下，只需简单地集成 SamS 即可显著提升任务性能，且额外计算开销极小。这项研究指出了一个有前景的新方向，通过更有效地利用固定偏好数据集，进一步提升 LLM 的对齐效果。

> Direct Preference Optimization (DPO) has emerged as an effective approach for aligning large language models (LLMs) with human preferences. However, its performance is highly dependent on the quality of the underlying human preference data. To address this bottleneck, prior work has explored various data selection strategies, but these methods often overlook the impact of the evolving states of the language model during the DPO process. %including active querying, response pair selection, and data pre-selection. In this paper, we introduce a novel problem: Sample Scheduling for DPO, which aims to dynamically and adaptively schedule training samples based on the model's evolving states throughout preference optimization. To solve this problem, we propose SamS, an efficient and effective algorithm that adaptively selects samples in each training batch based on the LLM's learning feedback to maximize the potential generalization performance. Notably, without modifying the core DPO algorithm, simply integrating SamS significantly improves performance across tasks, with minimal additional computational overhead. This work points to a promising new direction for improving LLM alignment through more effective utilization of fixed preference datasets.

[Arxiv](https://arxiv.org/abs/2506.17252)