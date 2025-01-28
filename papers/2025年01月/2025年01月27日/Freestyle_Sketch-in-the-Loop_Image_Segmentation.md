# 自由风格草图循环图像分割

发布时间：2025年01月27日

`其他

理由：这篇论文主要讨论的是图像分割领域的一个新方法，即通过手绘草图作为查询方式进行图像分割。虽然提到了大规模预训练模型（如CLIP或DINOv2），但核心内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `计算机视觉` `图像处理`

> Freestyle Sketch-in-the-Loop Image Segmentation

# 摘要

> 本文首次将草图研究引入图像分割领域，旨在将手绘草图作为主观图像分割的查询方式。我们创新性地提出了“草图在环”图像分割框架，无需专门数据集即可实现部分、完整或分组的视觉概念分割，真正实现了“自由风格”分割。该框架巧妙结合了基于草图的图像检索（SBIR）模型和大规模预训练模型（CLIP或DINOv2）的优势：前者提供训练信号，后者执行主观分割。我们还设计了专门的增强策略，使草图引导的掩码生成更具灵活性，支持多粒度分割。在多个基准数据集上的广泛实验表明，我们的方法在各种评估场景中均显著优于现有方法。

> In this paper, we expand the domain of sketch research into the field of image segmentation, aiming to establish freehand sketches as a query modality for subjective image segmentation. Our innovative approach introduces a "sketch-in-the-loop" image segmentation framework, enabling the segmentation of visual concepts partially, completely, or in groupings - a truly "freestyle" approach - without the need for a purpose-made dataset (i.e., mask-free). This framework capitalises on the synergy between sketch-based image retrieval (SBIR) models and large-scale pre-trained models (CLIP or DINOv2). The former provides an effective training signal, while fine-tuned versions of the latter execute the subjective segmentation. Additionally, our purpose-made augmentation strategy enhances the versatility of our sketch-guided mask generation, allowing segmentation at multiple granularity levels. Extensive evaluations across diverse benchmark datasets underscore the superior performance of our method in comparison to existing approaches across various evaluation scenarios.

[Arxiv](https://arxiv.org/abs/2501.16022)