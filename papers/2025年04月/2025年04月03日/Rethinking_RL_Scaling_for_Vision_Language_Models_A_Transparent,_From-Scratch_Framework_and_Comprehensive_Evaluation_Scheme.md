# 重新思考RL缩放策略：针对视觉语言模型，构建一个透明且从零开始的框架，并制定全面的评估方案

发布时间：2025年04月03日

`LLM应用` `计算机视觉` `视觉语言模型`

> Rethinking RL Scaling for Vision Language Models: A Transparent, From-Scratch Framework and Comprehensive Evaluation Scheme

# 摘要

> 强化学习（RL）在提升大型语言模型推理能力方面展现出强大潜力，并正在被积极扩展到视觉语言模型（VLMs）领域。然而，现有VLMs中的RL应用往往依赖于复杂框架，导致研究难以复现和普及，同时缺乏统一的评估标准，使得结果比较和训练动态解释困难。本研究提出了一种透明的、从零开始的VLMs中RL框架，提供了一个经过多模型和多数据集验证的简约而实用的四步流程。此外，还提出了一种标准化的评估方案，用于评估训练动态和反思行为。在视觉推理任务上的广泛实验揭示了关键经验发现：响应长度对随机种子敏感，反思与输出长度相关，且RL在泛化能力上始终优于监督微调（SFT），即使使用高质量数据也是如此。这些发现，结合提出的框架，旨在建立一个可重复的基准，并支持更广泛的基于RL的VLM研究参与。

> Reinforcement learning (RL) has recently shown strong potential in improving the reasoning capabilities of large language models and is now being actively extended to vision-language models (VLMs). However, existing RL applications in VLMs often rely on heavily engineered frameworks that hinder reproducibility and accessibility, while lacking standardized evaluation protocols, making it difficult to compare results or interpret training dynamics. This work introduces a transparent, from-scratch framework for RL in VLMs, offering a minimal yet functional four-step pipeline validated across multiple models and datasets. In addition, a standardized evaluation scheme is proposed to assess training dynamics and reflective behaviors. Extensive experiments on visual reasoning tasks uncover key empirical findings: response length is sensitive to random seeds, reflection correlates with output length, and RL consistently outperforms supervised fine-tuning (SFT) in generalization, even with high-quality data. These findings, together with the proposed framework, aim to establish a reproducible baseline and support broader engagement in RL-based VLM research.

[Arxiv](https://arxiv.org/abs/2504.02587)