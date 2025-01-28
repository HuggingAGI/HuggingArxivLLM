# Brain-Adapter: 利用适配器调优多模态大语言模型提升神经系统疾病分析能力

发布时间：2025年01月27日

`LLM应用` `脑部疾病`

> Brain-Adapter: Enhancing Neurological Disorder Analysis with Adapter-Tuning Multimodal Large Language Models

# 摘要

> 理解脑部疾病对临床诊断和治疗至关重要。多模态大型语言模型（MLLMs）的最新进展为在文本描述支持下解读医学图像提供了新思路。然而，以往研究多聚焦于2D医学图像，忽视了3D图像中更丰富的空间信息，且单一模态方法因忽略其他模态中的关键临床信息而受限。为此，本文提出Brain-Adapter，通过引入额外瓶颈层学习新知识并融入预训练模型。其核心在于使用轻量级瓶颈层减少参数训练，同时捕捉关键信息，并采用对比语言-图像预训练（CLIP）策略将多模态数据对齐到统一表示空间。大量实验表明，该方法在整合多模态数据、显著提升诊断准确性方面效果显著，且计算成本低，展现了其在优化现实诊断流程中的巨大潜力。

> Understanding brain disorders is crucial for accurate clinical diagnosis and treatment. Recent advances in Multimodal Large Language Models (MLLMs) offer a promising approach to interpreting medical images with the support of text descriptions. However, previous research has primarily focused on 2D medical images, leaving richer spatial information of 3D images under-explored, and single-modality-based methods are limited by overlooking the critical clinical information contained in other modalities. To address this issue, this paper proposes Brain-Adapter, a novel approach that incorporates an extra bottleneck layer to learn new knowledge and instill it into the original pre-trained knowledge. The major idea is to incorporate a lightweight bottleneck layer to train fewer parameters while capturing essential information and utilize a Contrastive Language-Image Pre-training (CLIP) strategy to align multimodal data within a unified representation space. Extensive experiments demonstrated the effectiveness of our approach in integrating multimodal data to significantly improve the diagnosis accuracy without high computational costs, highlighting the potential to enhance real-world diagnostic workflows.

[Arxiv](https://arxiv.org/abs/2501.16282)