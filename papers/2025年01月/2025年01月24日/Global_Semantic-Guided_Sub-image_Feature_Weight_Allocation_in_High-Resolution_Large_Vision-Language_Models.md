# 高分辨率大视觉语言模型中的全局语义引导子图像特征权重分配

发布时间：2025年01月24日

`LLM应用

**解释**：这篇论文主要讨论了如何通过改进子图像分割方法来提高大型视觉语言模型（LVLMs）对高分辨率图像的处理能力。虽然论文涉及视觉语言模型，但其核心是优化模型在处理高分辨率图像时的性能，属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `计算机视觉` `多模态系统`

> Global Semantic-Guided Sub-image Feature Weight Allocation in High-Resolution Large Vision-Language Models

# 摘要

> 随着大型视觉语言模型（LVLMs）对高分辨率图像处理需求的增加，子图像分割成为缓解固定分辨率处理中视觉信息丢失的常用方法。然而，现有方法对子图像进行统一处理，导致图像理解效果不佳。我们发现，与整体图像语义相关性更高的子图像包含更丰富的视觉信息，有助于保留模型的视觉理解能力。为此，我们提出了全局语义引导权重分配器（GSWA）模块，它根据子图像的相对信息密度动态分配权重，模拟人类视觉注意力机制，使模型能够聚焦于信息更丰富的区域，突破统一处理的局限。我们将GSWA集成到InternVL2-2B框架中，构建了轻量级高性能模型SleighVL。实验表明，SleighVL在参数相当的情况下表现优异，且与更大模型相比仍具竞争力。这项工作为LVLMs中更高效、上下文感知的高分辨率图像处理提供了新思路，推动了多模态系统的发展。

> As the demand for high-resolution image processing in Large Vision-Language Models (LVLMs) grows, sub-image partitioning has become a popular approach for mitigating visual information loss associated with fixed-resolution processing. However, existing partitioning methods uniformly process sub-images, resulting in suboptimal image understanding. In this work, we reveal that the sub-images with higher semantic relevance to the entire image encapsulate richer visual information for preserving the model's visual understanding ability. Therefore, we propose the Global Semantic-guided Weight Allocator (GSWA) module, which dynamically allocates weights to sub-images based on their relative information density, emulating human visual attention mechanisms. This approach enables the model to focus on more informative regions, overcoming the limitations of uniform treatment. We integrate GSWA into the InternVL2-2B framework to create SleighVL, a lightweight yet high-performing model. Extensive experiments demonstrate that SleighVL outperforms models with comparable parameters and remains competitive with larger models. Our work provides a promising direction for more efficient and contextually aware high-resolution image processing in LVLMs, advancing multimodal system development.

[Arxiv](https://arxiv.org/abs/2501.14276)