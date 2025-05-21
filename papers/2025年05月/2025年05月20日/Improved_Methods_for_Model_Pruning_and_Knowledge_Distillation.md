# 改进的模型剪枝与知识蒸馏方法

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Improved Methods for Model Pruning and Knowledge Distillation

# 摘要

> 模型剪枝是一种优化大型语言模型（如R1或o3-mini）性能的技术。然而，现有的剪枝方法往往会导致性能大幅下降，或者需要进行大量重新训练和微调。该技术的目标是识别并移除在人机交互阶段不太可能做出贡献的神经元和连接。我们的目标是获得一个更小、更快的知识蒸馏模型，能够快速生成几乎与未剪枝模型一样优秀的内容。我们提出了一种改进的剪枝方法，名为MAMA剪枝（全称：运动与幅度分析）。该方法在有效减小模型尺寸和计算复杂度的同时，即使在极端剪枝水平下，也能保持与原始未剪枝模型相当的性能。改进的方法基于预训练阶段固定的权重、偏置，以及后训练阶段验证的GRPO奖励，作为我们的新型剪枝指标。初步的实验结果表明，我们的方法在不同剪枝水平和各种下游计算语言学任务中，都优于并可与现有最先进的方法相媲美。

> Model pruning is a performance optimization technique for large language models like R1 or o3-mini. However, existing pruning methods often lead to significant performance degradation or require extensive retraining and fine-tuning. This technique aims to identify and remove neurons, connections unlikely leading to the contribution during the human-computer interaction phase. Our goal is to obtain a much smaller and faster knowledge distilled model that can quickly generate content almost as good as those of the unpruned ones. We propose MAMA Pruning, short for Movement and Magnitude Analysis, an improved pruning method that effectively reduces model size and computational complexity while maintaining performance comparable to the original unpruned model even at extreme pruned levels. The improved method is based on weights, bias fixed in the pre-training phase and GRPO rewards verified during the post-training phase as our novel pruning indicators. Preliminary experimental results show that our method outperforms and be comparable to state-of-the-art methods across various pruning levels and different downstream computational linguistics tasks.

[Arxiv](https://arxiv.org/abs/2505.14052)