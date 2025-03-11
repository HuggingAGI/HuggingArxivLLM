# 通过课程强化学习提升视觉语言模型的泛化与推理能力

发布时间：2025年03月10日

`其他

理由：这篇论文主要讨论了视觉语言模型（VLMs）的训练方法，特别是针对小型模型提出了新的训练范式。虽然提到了大型语言模型（LLMs）作为比较对象，但论文的核心内容并不直接涉及LLMs的应用或理论，而是集中在视觉语言模型的优化上。因此，它更适合归类到其他类别。` `计算机视觉` `多模态`

> Boosting the Generalization and Reasoning of Vision Language Models with Curriculum Reinforcement Learning

# 摘要

> 当前的视觉语言模型（VLMs）在处理复杂的视觉文本任务时表现突出，但其成功高度依赖于模型规模的大幅扩展，这在实际应用中存在诸多限制。相比之下，小型VLMs作为一种更实用的选择，却在传统监督微调（SFT）方法下面临两大难题：域外（OOD）泛化能力和推理能力显著落后于当代大型语言模型（LLMs）。为了解决这些挑战，我们提出了一种专为小型VLMs设计的新型后训练范式——课程强化微调（Curr-ReFT）。受强化学习在LLMs中成功应用的启发，Curr-ReFT分为两个阶段：（1）课程强化学习，通过难度感知的奖励设计，引导模型能力从基础的视觉感知逐步提升至复杂的推理任务；（2）基于拒绝采样的自我改进，通过选择性学习高质量的多模态和语言示例，保持VLMs的核心能力。大量实验结果表明，采用Curr-ReFT范式训练的模型在各种视觉任务中均达到了当前最优的性能水平，无论是域内还是域外场景。值得注意的是，我们的30亿参数规模的Curr-ReFT增强模型在性能上已可与320亿参数规模的模型相媲美，这充分证明了高效的训练范式能够有效缩小小型与大型模型之间的性能鸿沟。

> While state-of-the-art vision-language models (VLMs) have demonstrated remarkable capabilities in complex visual-text tasks, their success heavily relies on massive model scaling, limiting their practical deployment. Small-scale VLMs offer a more practical alternative but face significant challenges when trained with traditional supervised fine-tuning (SFT), particularly in two aspects: out-of-domain (OOD) generalization and reasoning abilities, which significantly lags behind the contemporary Large language models (LLMs). To address these challenges, we propose Curriculum Reinforcement Finetuning (Curr-ReFT), a novel post-training paradigm specifically designed for small-scale VLMs. Inspired by the success of reinforcement learning in LLMs, Curr-ReFT comprises two sequential stages: (1) Curriculum Reinforcement Learning, which ensures steady progression of model capabilities through difficulty-aware reward design, transitioning from basic visual perception to complex reasoning tasks; and (2) Rejected Sampling-based Self-improvement, which maintains the fundamental capabilities of VLMs through selective learning from high-quality multimodal and language examples. Extensive experiments demonstrate that models trained with Curr-ReFT paradigm achieve state-of-the-art performance across various visual tasks in both in-domain and out-of-domain settings. Moreover, our Curr-ReFT enhanced 3B model matches the performance of 32B-parameter models, demonstrating that efficient training paradigms can effectively bridge the gap between small and large models.

[Arxiv](https://arxiv.org/abs/2503.07065)