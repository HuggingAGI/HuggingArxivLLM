# Omni-Think：利用多任务强化学习结合混合奖励机制提升大规模语言模型的跨领域泛化能力

发布时间：2025年07月19日

`LLM理论`

> Omni-Think: Scaling Cross-Domain Generalization in LLMs via Multi-Task RL with Hybrid Rewards

# 摘要

> 通用人工智能的进步离不开大型语言模型（LLMs），它们在结构化推理到创造性生成等各项任务中表现出色。然而，监督微调（SFT）等后训练方法往往在泛化能力上表现欠佳，更倾向于记忆而非迁移学习。我们提出了Omni-Think，一个统一的强化学习（RL）框架，通过结合基于规则的可验证奖励和生成偏好信号（借助LLM评估），全面提升LLMs在多样化任务中的表现。我们的方法实现了跨任务类型的稳定优化，并将基于强化学习的训练扩展到主观领域。我们还深入研究了训练策略，发现从结构化任务到开放性任务的课程式递进能够显著提升性能并减少遗忘。实验结果显示，相较于联合训练和模型合并，课程学习在四个领域分别提升了5.2%和9.1%的性能。这些结果凸显了任务感知采样和混合监督在扩展基于强化学习的后训练对于通用LLMs的重要性。

> The advancement of general-purpose artificial intelligence relies on large language models (LLMs) that excel across a wide range of tasks, from structured reasoning to creative generation. However, post-training methods like Supervised Fine-Tuning (SFT) often struggle with generalization, favoring memorization over transferable learning. In this work, we introduce Omni-Think, a unified reinforcement learning (RL) framework that enhances LLM performance across diverse tasks by combining rule-based verifiable rewards with generative preference signals via LLM-as-a-Judge evaluations. Our approach enables consistent optimization across task types and scales RL-based training to subjective domains. We further investigate training strategies, demonstrating that a curriculum-based progression that orders tasks from structured to open-ended improves performance and reduces forgetting. Experimental results across four domains reveal that curriculum learning improves performance by 5.2\% over joint training and 9.1\% over model merging. These results highlight the importance of task-aware sampling and hybrid supervision in scaling RL-based post-training for general-purpose LLMs.

[Arxiv](https://arxiv.org/abs/2507.14783)