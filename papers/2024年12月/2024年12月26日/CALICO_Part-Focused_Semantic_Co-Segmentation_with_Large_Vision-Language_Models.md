# CALICO: 利用大型视觉-语言模型实现部分聚焦的语义共分割

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了大规模视觉-语言模型（LVLMs）在视觉任务中的应用，特别是通过视觉指令调优来实现跨图像的分割和推理。论文提出了一个新的任务和模型（CALICO），并展示了其在部分聚焦的语义共分割任务中的卓越性能。虽然涉及视觉和语言的多模态处理，但其核心仍然是基于大规模语言模型的应用，因此归类为LLM应用。` `计算机视觉` `图像处理`

> CALICO: Part-Focused Semantic Co-Segmentation with Large Vision-Language Models

# 摘要

> # 摘要
近期大规模视觉-语言模型（LVLMs）的进展通过视觉指令调优在通用视觉任务中取得了显著突破。尽管已有研究展示了LVLMs生成与自然语言描述对齐的分割掩码的能力，但在跨多图像的分割基础比较上仍显不足，尤其是在对象部分的细粒度层面。本文提出了一种新的任务——部分聚焦的语义共分割，旨在识别并分割图像中的共同和独特对象及其部分。为此，我们推出了CALICO，这是首个能够跨图像分割和推理多个掩码的LVLM，使其能够基于对象的组成部分进行比较。CALICO包含两个创新组件：一个新颖的对应提取模块，用于捕捉语义丰富的信息以识别对象间的部分级对应关系；以及一个对应适应模块，将这些信息嵌入LVLM，以参数高效的方式促进多图像理解。为支持训练和评估，我们构建了MixedParts数据集，包含$\sim$2.4M个样本，覆盖$\sim$44K张图像，涵盖多样化的对象和部分类别。实验表明，CALICO仅在其架构的0.3%上进行微调，便在部分聚焦的语义共分割任务中展现出卓越性能。

> Recent advances in Large Vision-Language Models (LVLMs) have sparked significant progress in general-purpose vision tasks through visual instruction tuning. While some works have demonstrated the capability of LVLMs to generate segmentation masks that align phrases with natural language descriptions in a single image, they struggle with segmentation-grounded comparisons across multiple images, particularly at finer granularities such as object parts. In this paper, we introduce the new task of part-focused semantic co-segmentation, which seeks to identify and segment common and unique objects and parts across images. To address this task, we present CALICO, the first LVLM that can segment and reason over multiple masks across images, enabling object comparison based on their constituent parts. CALICO features two proposed components, a novel Correspondence Extraction Module, which captures semantic-rich information to identify part-level correspondences between objects, and a Correspondence Adaptation Module, which embeds this information into the LVLM to facilitate multi-image understanding in a parameter-efficient manner. To support training and evaluation, we curate MixedParts, a comprehensive multi-image segmentation dataset containing $\sim$2.4M samples across $\sim$44K images with diverse object and part categories. Experimental results show CALICO, finetuned on only 0.3% of its architecture, achieves robust performance in part-focused semantic co-segmentation.

[Arxiv](https://arxiv.org/abs/2412.19331)