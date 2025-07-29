# 基于区域的聚类判别方法在视觉表示学习中的应用

发布时间：2025年07月26日

`其他` `计算机视觉` `OCR`

> Region-based Cluster Discrimination for Visual Representation Learning

# 摘要

> 视觉表示学习是众多下游任务的重要基础。尽管近期的视觉-语言对比模型（如CLIP和SigLIP）通过大规模视觉-语言对齐实现了令人印象深刻的零样本性能，但它们对全局表示的依赖限制了在密集预测任务（如定位、OCR和分割）中的有效性。为了解决这一问题，我们提出了一种名为Region-Aware Cluster Discrimination（RICE）的新方法，专注于提升区域级视觉和OCR能力。我们首先构建了一个十亿规模的候选区域数据集，并提出了一种区域变换器层来提取丰富的区域语义。我们进一步设计了一种统一的区域聚类判别损失，能够在单一分类框架内同时支持目标和OCR学习，从而实现大规模数据上的高效且可扩展的分布式训练。大量实验表明，RICE在包括分割、密集检测以及多模态大语言模型（MLLMs）的视觉感知等任务中始终优于先前方法。预训练模型已发布在https://github.com/deepglint/MVT。


> Learning visual representations is foundational for a broad spectrum of downstream tasks. Although recent vision-language contrastive models, such as CLIP and SigLIP, have achieved impressive zero-shot performance via large-scale vision-language alignment, their reliance on global representations constrains their effectiveness for dense prediction tasks, such as grounding, OCR, and segmentation. To address this gap, we introduce Region-Aware Cluster Discrimination (RICE), a novel method that enhances region-level visual and OCR capabilities. We first construct a billion-scale candidate region dataset and propose a Region Transformer layer to extract rich regional semantics. We further design a unified region cluster discrimination loss that jointly supports object and OCR learning within a single classification framework, enabling efficient and scalable distributed training on large-scale data. Extensive experiments show that RICE consistently outperforms previous methods on tasks, including segmentation, dense detection, and visual perception for Multimodal Large Language Models (MLLMs). The pre-trained models have been released at https://github.com/deepglint/MVT.

[Arxiv](https://arxiv.org/abs/2507.20025)