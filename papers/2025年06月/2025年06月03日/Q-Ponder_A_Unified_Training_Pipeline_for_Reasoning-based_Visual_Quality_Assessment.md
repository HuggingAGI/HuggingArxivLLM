# Q-Ponder：基于推理的视觉质量评估统一训练流程

发布时间：2025年06月03日

`LLM应用` `视觉质量评估` `多模态模型`

> Q-Ponder: A Unified Training Pipeline for Reasoning-based Visual Quality Assessment

# 摘要

> 近期研究表明，多模态大型语言模型（MLLMs）能够通过可解释性评估高效地进行视觉质量评估。然而，现有方法通常将质量评分与推理描述视为分离的任务，各自具有不同的优化目标，导致了一种权衡：擅长质量推理描述的模型难以实现精准的分数回归，而专注于评分的模型则缺乏可解释性。这一局限性阻碍了MLLMs在视觉质量评估中的潜力发挥，因为准确性与可解释性本应相辅相成。

为了解决这一问题，我们提出了一种统一的两阶段训练框架，包括冷启动阶段和基于强化学习的微调阶段。具体来说，在第一阶段，我们通过专家设计的提示从教师模型中提炼高质量数据，利用交叉熵损失监督初始化推理能力。在第二阶段，我们引入了一种基于组相对策略优化（GRPO）的新奖励机制，以同时优化评分准确性和推理一致性。我们将这两个阶段训练得到的模型分别命名为Q-Ponder-CI和Q-Ponder。

通过广泛的实验，我们发现Q-Ponder在质量评分回归基准测试中达到了最先进（SOTA）的性能水平，在跨领域数据集上SRCC提升了高达6.5%。此外，Q-Ponder在描述准确性与合理性方面显著优于基于描述的SOTA模型，包括其教师模型Qwen-2.5-VL-72B，展示了其在多样化任务中的泛化潜力。

> Recent studies demonstrate that multimodal large language models (MLLMs) can proficiently evaluate visual quality through interpretable assessments. However, existing approaches typically treat quality scoring and reasoning descriptions as separate tasks with disjoint optimization objectives, leading to a trade-off: models adept at quality reasoning descriptions struggle with precise score regression, while score-focused models lack interpretability. This limitation hinders the full potential of MLLMs in visual quality assessment, where accuracy and interpretability should be mutually reinforcing. To address this, we propose a unified two-stage training framework comprising a cold-start stage and a reinforcement learning-based fine-tuning stage. Specifically, in the first stage, we distill high-quality data from a teacher model through expert-designed prompts, initializing reasoning capabilities via cross-entropy loss supervision. In the second stage, we introduce a novel reward with Group Relative Policy Optimization (GRPO) to jointly optimize scoring accuracy and reasoning consistency. We designate the models derived from these two stages as Q-Ponder-CI and Q-Ponder. Extensive experiments show that Q-Ponder achieves state-of-the-art (SOTA) performance on quality score regression benchmarks, delivering up to 6.5% higher SRCC on cross-domain datasets. Furthermore, Q-Ponder significantly outperforms description-based SOTA models, including its teacher model Qwen-2.5-VL-72B, particularly in description accuracy and reasonableness, demonstrating the generalization potential over diverse tasks.

[Arxiv](https://arxiv.org/abs/2506.05384)