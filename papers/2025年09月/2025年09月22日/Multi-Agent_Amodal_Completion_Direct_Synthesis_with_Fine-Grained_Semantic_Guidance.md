# 多智能体非模态补全：细粒度语义引导下的直接合成

发布时间：2025年09月22日

`Agent` `媒体与娱乐`

> Multi-Agent Amodal Completion: Direct Synthesis with Fine-Grained Semantic Guidance

# 摘要

> 隐式补全——即生成被遮挡物体的不可见部分——在图像编辑、增强现实（AR）等应用中至关重要。现有方法却受限于数据需求量大、泛化能力弱或渐进式流水线存在误差累积等问题。为此，我们提出一种基于前期协作推理的协作多智能体推理框架以突破这些局限。该框架通过多个智能体协作分析遮挡关系、确定必要的边界扩展，进而生成用于图像修复的精确掩码。同时，单个智能体生成细粒度文本描述，提供细粒度语义引导。这既能保证物体合成的准确性，又能避免遮挡物或其他无关元素的再生——这在大型图像修复区域中尤为关键。此外，我们的方法在可见掩码和扩散Transformer注意力图的引导下，直接生成分层RGBA输出，省去了额外的分割步骤。大量实验评估证实，我们的框架实现了当前最先进的视觉质量。

> Amodal completion, generating invisible parts of occluded objects, is vital for applications like image editing and AR. Prior methods face challenges with data needs, generalization, or error accumulation in progressive pipelines. We propose a Collaborative Multi-Agent Reasoning Framework based on upfront collaborative reasoning to overcome these issues. Our framework uses multiple agents to collaboratively analyze occlusion relationships and determine necessary boundary expansion, yielding a precise mask for inpainting. Concurrently, an agent generates fine-grained textual descriptions, enabling Fine-Grained Semantic Guidance. This ensures accurate object synthesis and prevents the regeneration of occluders or other unwanted elements, especially within large inpainting areas. Furthermore, our method directly produces layered RGBA outputs guided by visible masks and attention maps from a Diffusion Transformer, eliminating extra segmentation. Extensive evaluations demonstrate our framework achieves state-of-the-art visual quality.

[Arxiv](https://arxiv.org/abs/2509.17757)