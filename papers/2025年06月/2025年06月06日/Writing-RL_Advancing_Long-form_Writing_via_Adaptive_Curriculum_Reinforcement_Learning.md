# Writing-RL：利用自适应课程强化学习提升长篇写作能力

发布时间：2025年06月06日

`LLM应用` `文本生成`

> Writing-RL: Advancing Long-form Writing via Adaptive Curriculum Reinforcement Learning

# 摘要

> # 摘要
近期在大型语言模型（LLMs）方面的研究进展使其在长文本生成任务中表现出色，然而现有监督微调（SFT）方法仍面临数据饱和和学习能力受限于教师信号等局限性。本文提出Writing-RL：一种自适应课程强化学习框架，旨在突破SFT限制，提升长文本生成能力。该框架包含三个关键组件：
- 基于学习潜力的样本筛选策略
- 无验证奖励条件下的对比奖励机制
- 根据模型性能动态调整任务难度的参考调度方法
实验结果表明，与强大的监督微调基线模型相比，我们的强化学习框架在长文本生成任务上取得了显著提升。此外，我们发现通过长文本输出强化学习训练的模型在长文本推理任务上也表现出色，这可能为重新思考长上下文训练提供了新视角。


> Recent advances in Large Language Models (LLMs) have enabled strong performance in long-form writing, yet existing supervised fine-tuning (SFT) approaches suffer from limitations such as data saturation and restricted learning capacity bounded by teacher signals. In this work, we present Writing-RL: an Adaptive Curriculum Reinforcement Learning framework to advance long-form writing capabilities beyond SFT. The framework consists of three key components: Margin-aware Data Selection strategy that prioritizes samples with high learning potential, Pairwise Comparison Reward mechanism that provides discriminative learning signals in the absence of verifiable rewards, and Dynamic Reference Scheduling approach, which plays a particularly critical role by adaptively adjusting task difficulty based on evolving model performance. Experiments on 7B-scale writer models show that our RL framework largely improves long-form writing performance over strong SFT baselines. Furthermore, we observe that models trained with long-output RL generalize surprisingly well to long-input reasoning tasks, potentially offering a promising perspective for rethinking long-context training.

[Arxiv](https://arxiv.org/abs/2506.05760)