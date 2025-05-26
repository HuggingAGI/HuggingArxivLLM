# # 对比蒸馏：从大型语言模型中提取情感知识用于零样本情感识别

发布时间：2025年05月23日

`LLM应用` `情感识别`

> Contrastive Distillation of Emotion Knowledge from LLMs for Zero-Shot Emotion Recognition

# 摘要

> 无需专门训练即可处理多种情感标签的能力对构建灵活的情感识别 (ER) 系统至关重要。传统 ER 模型依赖固定标签集训练，难以泛化到新场景。而大型语言模型 (LLMs) 虽在多样化标签空间中展现出强大的零样本 ER 能力，但其规模限制了在边缘设备上的应用。

本研究提出了一种对比蒸馏框架，无需人工标注即可将 LLMs 的丰富情感知识迁移到轻量化模型中。我们借助 GPT-4 生成描述性情感标注，提供超越固定标签集的丰富监督信号。通过在共享嵌入空间中对齐文本样本与情感描述，我们的方法实现了对不同情感类别、粒度及标签模式的零样本预测。

实验表明，蒸馏后的模型在多个数据集和标签空间中表现出色，超越了同类规模的强基线模型，性能接近 GPT-4 的零样本水平，同时模型体积仅为 GPT-4 的万分之一。

> The ability to handle various emotion labels without dedicated training is crucial for building adaptable Emotion Recognition (ER) systems. Conventional ER models rely on training using fixed label sets and struggle to generalize beyond them. On the other hand, Large Language Models (LLMs) have shown strong zero-shot ER performance across diverse label spaces, but their scale limits their use on edge devices. In this work, we propose a contrastive distillation framework that transfers rich emotional knowledge from LLMs into a compact model without the use of human annotations. We use GPT-4 to generate descriptive emotion annotations, offering rich supervision beyond fixed label sets. By aligning text samples with emotion descriptors in a shared embedding space, our method enables zero-shot prediction on different emotion classes, granularity, and label schema. The distilled model is effective across multiple datasets and label spaces, outperforming strong baselines of similar size and approaching GPT-4's zero-shot performance, while being over 10,000 times smaller.

[Arxiv](https://arxiv.org/abs/2505.18040)