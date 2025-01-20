# PIXELS: 渐进式图像范例编辑与潜在手术

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论的是如何利用现有的扩散模型（如大型文本到图像模型）进行图像编辑，特别是通过示例驱动的编辑方法。虽然论文中提到了多模态提示和参考图像的使用，但其核心是应用现有的生成模型（如扩散模型）来实现高质量的图像编辑。因此，这篇论文属于LLM应用领域，因为它涉及如何将现有的生成模型应用于具体的任务（图像编辑）中，而不是讨论模型的理论基础或新的模型架构。` `图像编辑` `计算机视觉`

> PIXELS: Progressive Image Xemplar-based Editing with Latent Surgery

# 摘要

> # 摘要
近期语言引导的图像编辑扩散模型进展常受限于繁琐的提示工程，难以精确表达所需更改。一个直观的替代方案是利用野外图像示例，帮助用户将想象中的编辑变为现实。然而，现有基于示例的编辑方法往往回避利用大型文本到图像（TTI）模型的丰富潜在空间，转而依赖精心设计的训练目标。虽然有效，但这种方法计算资源消耗大，且难以兼容多种基础模型和任意数量的示例。进一步研究发现，这些技术还限制了用户控制，仅允许在整个编辑区域上应用统一的全局更改。本文提出了一种名为PIXELS的新框架，利用现成的扩散模型进行渐进式示例驱动编辑，提供像素或区域级别的细粒度控制，实现高度定制化。PIXELS仅在推理阶段运行，支持从动态数量的参考图像或多模态提示中汲取灵感，逐步整合所有更改，无需重新训练或微调现有TTI模型。这种细粒度控制能力带来了新的可能性，如选择性修改单个对象或指定渐进的空间变化。实验表明，PIXELS能够高效生成高质量编辑，在定量指标和人类评估中均表现优异。通过降低高质量图像编辑的门槛，PIXELS有望让更多用户轻松使用开源图像生成模型进行专业级编辑。

> Recent advancements in language-guided diffusion models for image editing are often bottle-necked by cumbersome prompt engineering to precisely articulate desired changes. An intuitive alternative calls on guidance from in-the-wild image exemplars to help users bring their imagined edits to life. Contemporary exemplar-based editing methods shy away from leveraging the rich latent space learnt by pre-existing large text-to-image (TTI) models and fall back on training with curated objective functions to achieve the task. Though somewhat effective, this demands significant computational resources and lacks compatibility with diverse base models and arbitrary exemplar count. On further investigation, we also find that these techniques restrict user control to only applying uniform global changes over the entire edited region. In this paper, we introduce a novel framework for progressive exemplar-driven editing with off-the-shelf diffusion models, dubbed PIXELS, to enable customization by providing granular control over edits, allowing adjustments at the pixel or region level. Our method operates solely during inference to facilitate imitative editing, enabling users to draw inspiration from a dynamic number of reference images, or multimodal prompts, and progressively incorporate all the desired changes without retraining or fine-tuning existing TTI models. This capability of fine-grained control opens up a range of new possibilities, including selective modification of individual objects and specifying gradual spatial changes. We demonstrate that PIXELS delivers high-quality edits efficiently, leading to a notable improvement in quantitative metrics as well as human evaluation. By making high-quality image editing more accessible, PIXELS has the potential to enable professional-grade edits to a wider audience with the ease of using any open-source image generation model.

[Arxiv](https://arxiv.org/abs/2501.09826)