# EAGLE：通过增强视觉基础，减少指令多模态模型中的幻觉

发布时间：2025年01月05日

`LLM应用

理由：这篇论文主要讨论了如何通过增强视觉组件的能力来减少多模态架构中的“幻觉”现象，即生成的响应偏离图像数据真实情况的问题。虽然论文提到了大型语言模型（LLM）和多模态架构，但其核心关注点是通过改进视觉编码器来提升模型的性能，而不是直接研究LLM的理论或Agent行为。因此，这篇论文更适合归类为“LLM应用”，因为它涉及如何在实际应用中改进和优化LLM的性能。` `计算机视觉`

> EAGLE: Enhanced Visual Grounding Minimizes Hallucinations in Instructional Multimodal Models

# 摘要

> 大型语言模型和视觉变换器展现了强大的零-shot能力，显著提升了下游任务的迁移性。这些模型的融合催生了具备更强指令能力的多模态架构。然而，尽管经过了海量的图像和语言预训练，这些架构生成的响应仍常常偏离图像数据的真实情况，这种现象被称为“幻觉”。目前，缓解幻觉的方法主要集中在语言组件的正则化、融合模块的优化，或通过集成多个视觉编码器来提升视觉表示。本文则另辟蹊径，通过直接增强视觉组件的能力来解决这一问题。我们提出的EAGLE方法完全独立于LLM或融合模块，作为一种后预训练策略，显著提升了视觉编码器的接地性和语言对齐能力。我们通过简单的对比预训练任务重新设计，得到了一个改进的视觉编码器，无需额外指令训练即可无缝融入多模态架构。实验表明，EAGLE在多个高难度基准和任务中大幅减少了幻觉现象。

> Large language models and vision transformers have demonstrated impressive zero-shot capabilities, enabling significant transferability in downstream tasks. The fusion of these models has resulted in multi-modal architectures with enhanced instructional capabilities. Despite incorporating vast image and language pre-training, these multi-modal architectures often generate responses that deviate from the ground truth in the image data. These failure cases are known as hallucinations. Current methods for mitigating hallucinations generally focus on regularizing the language component, improving the fusion module, or ensembling multiple visual encoders to improve visual representation. In this paper, we address the hallucination issue by directly enhancing the capabilities of the visual component. Our approach, named EAGLE, is fully agnostic to the LLM or fusion module and works as a post-pretraining approach that improves the grounding and language alignment of the visual encoder. We show that a straightforward reformulation of the original contrastive pre-training task results in an improved visual encoder that can be incorporated into the instructional multi-modal architecture without additional instructional training. As a result, EAGLE achieves a significant reduction in hallucinations across multiple challenging benchmarks and tasks.

[Arxiv](https://arxiv.org/abs/2501.02699)