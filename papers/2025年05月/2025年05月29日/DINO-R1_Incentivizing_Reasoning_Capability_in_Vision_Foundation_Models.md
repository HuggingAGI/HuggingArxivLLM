# DINO-R1：激发视觉基础模型的推理潜能

发布时间：2025年05月29日

`其他` `计算机视觉` `视觉推理`

> DINO-R1: Incentivizing Reasoning Capability in Vision Foundation Models

# 摘要

> 大型语言模型（如DeepSeek-R1）近期在推理能力方面引发了广泛关注，基于强化学习的微调框架（如组相对策略优化（GRPO））在其中发挥了关键作用。然而，这种推理能力在视觉基础模型中尚未得到充分挖掘，特别是在DINO系列等表示模型中更是鲜见应用。为此，我们提出了	extbf{DINO-R1}，这是首个尝试利用强化学习提升视觉基础模型视觉上下文推理能力的研究。具体而言，DINO-R1引入了	extbf{组相对查询优化（GRQO）}，这是一种专为基于查询的表示模型设计的新型强化学习训练策略，通过计算基于组归一化对齐质量的查询级别奖励。同时，我们采用了KL正则化方法以稳定目标分布，从而减少训练过程中的不稳定因素。这种联合优化方法不仅能够提供密集且富有表现力的监督信号，还能有效缓解过拟合和分布漂移问题。基于Grounding-DINO，我们训练了一系列整合视觉提示编码器和视觉引导查询选择机制的DINO-R1家族模型。在COCO、LVIS和ODinW等数据集上的广泛实验表明，DINO-R1显著超越了监督微调基线模型，并在开放词汇和封闭集视觉提示场景中均展现了强大的泛化能力。

> The recent explosive interest in the reasoning capabilities of large language models, such as DeepSeek-R1, has demonstrated remarkable success through reinforcement learning-based fine-tuning frameworks, exemplified by methods like Group Relative Policy Optimization (GRPO). However, such reasoning abilities remain underexplored and notably absent in vision foundation models, including representation models like the DINO series. In this work, we propose \textbf{DINO-R1}, the first such attempt to incentivize visual in-context reasoning capabilities of vision foundation models using reinforcement learning. Specifically, DINO-R1 introduces \textbf{Group Relative Query Optimization (GRQO)}, a novel reinforcement-style training strategy explicitly designed for query-based representation models, which computes query-level rewards based on group-normalized alignment quality. We also apply KL-regularization to stabilize the objectness distribution to reduce the training instability. This joint optimization enables dense and expressive supervision across queries while mitigating overfitting and distributional drift. Building upon Grounding-DINO, we train a series of DINO-R1 family models that integrate a visual prompt encoder and a visual-guided query selection mechanism. Extensive experiments on COCO, LVIS, and ODinW demonstrate that DINO-R1 significantly outperforms supervised fine-tuning baselines, achieving strong generalization in both open-vocabulary and closed-set visual prompting scenarios.

[Arxiv](https://arxiv.org/abs/2505.24025)