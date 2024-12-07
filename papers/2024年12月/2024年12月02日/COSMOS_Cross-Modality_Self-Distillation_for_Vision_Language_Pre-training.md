# COSMOS：用于视觉语言预训练的跨模态自提炼

发布时间：2024年12月02日

`LLM应用` `视觉语言` `自监督学习`

> COSMOS: Cross-Modality Self-Distillation for Vision Language Pre-training

# 摘要

> 视觉语言模型（VLMs）经对比损失训练后，在各类视觉和语言任务中取得了重大进展。但对比损失的全局性致使 VLMs 主要聚焦于前景对象，而忽略了图像中的其他关键信息，这限制了其在下游任务中的表现。为应对这些挑战，我们提出了 COSMOS：用于视觉语言预训练的跨模态自蒸馏，它将新颖的文本裁剪策略和交叉注意力模块融入自监督学习框架。我们创建了图像和文本的全局及局部视图（即多模态增强），这对 VLMs 的自蒸馏至关重要。我们还引入了交叉注意力模块，使 COSMOS 能够学习通过跨模态自蒸馏损失优化的全面跨模态表示。COSMOS 在包括检索、分类和语义分割等各种零样本下游任务中，始终优于以往的强大基线。此外，在视觉感知和上下文理解任务中，它也超越了在更大数据集上训练的基于 CLIP 的模型。

> Vision-Language Models (VLMs) trained with contrastive loss have achieved significant advancements in various vision and language tasks. However, the global nature of contrastive loss makes VLMs focus predominantly on foreground objects, neglecting other crucial information in the image, which limits their effectiveness in downstream tasks. To address these challenges, we propose COSMOS: CrOSs-MOdality Self-distillation for vision-language pre-training that integrates a novel text-cropping strategy and cross-attention module into a self-supervised learning framework. We create global and local views of images and texts (i.e., multi-modal augmentations), which are essential for self-distillation in VLMs. We further introduce a cross-attention module, enabling COSMOS to learn comprehensive cross-modal representations optimized via a cross-modality self-distillation loss. COSMOS consistently outperforms previous strong baselines on various zero-shot downstream tasks, including retrieval, classification, and semantic segmentation. Additionally, it surpasses CLIP-based models trained on larger datasets in visual perception and contextual understanding tasks.

[Arxiv](https://arxiv.org/abs/2412.01814)