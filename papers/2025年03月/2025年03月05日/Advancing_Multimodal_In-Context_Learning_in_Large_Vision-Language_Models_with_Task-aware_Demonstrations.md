# 提升大型视觉语言模型的多模态上下文学习能力，通过任务感知的演示

发布时间：2025年03月05日

`LLM应用

论文摘要讨论了多模态上下文学习（ICL）在大型视觉语言模型中的应用，提出了新的模型架构SabER，专注于上下文学习的优化和应用，因此归类为LLM应用。` `计算机视觉` `跨模态`

> Advancing Multimodal In-Context Learning in Large Vision-Language Models with Task-aware Demonstrations

# 摘要

> 多模态上下文学习（ICL）作为大型视觉语言模型（LVLMs）的核心能力，其发展得益于模型规模与应用范围的不断扩展。然而，尽管潜力巨大，多模态环境下的有效ICL仍面临挑战，主要源于图像-文本输入的复杂性和ICL性能对输入配置的高度敏感性。本研究深入探讨了多模态ICL的核心机制，发现任务映射是配置健壮上下文演示（ICD）序列的关键。基于此，我们提出了SabER——一个轻量级且功能强大的仅解码器式变压器，配备任务感知注意力机制，能够智能选择和排列ICD序列，并以自回归方式生成。这种设计不仅实现了细粒度特征提取与跨模态推理，还通过迭代优化任务映射生成高质量ICD序列。通过涵盖五种LVLM和九个基准数据集的全面实验，SabER不仅展现了卓越的实证性能，还揭示了任务语义与多模态ICD之间的深层关联。我们的研究结果强调了基于原则配置ICD序列的重要性，并为提升多模态ICL在现实场景中的应用开辟了新方向。

> Multimodal in-context learning (ICL) has emerged as a key capability of Large Vision-Language Models (LVLMs), driven by their increasing scale and applicability. Despite its promise, effective ICL in the multimodal setting remains challenging due to the inherent complexity of image-text inputs and the high sensitivity of ICL performance to input configurations. In this work, we shed light on the core mechanism underlying multimodal ICL, identifying task mapping as a crucial factor in configuring robust in-context demonstration (ICD) sequences. Building on these insights, we propose \textit{SabER}, a lightweight yet powerful decoder-only transformer equipped with task-aware attention, which intelligently selects and arranges ICDs from a demonstration library in an autoregressive fashion. This design enables fine-grained feature extraction and cross-modal reasoning, iteratively refining task mapping to generate high-quality ICD sequences. Through extensive experiments covering five LVLMs and nine benchmark datasets, SabER not only demonstrates strong empirical performance, but also provides deeper understanding of how task semantics interact with multimodal ICDs. Our findings highlight the importance of principled ICD sequence configuration and open new avenues to enhance multimodal ICL in a wide range of real-world scenarios.

[Arxiv](https://arxiv.org/abs/2503.04839)