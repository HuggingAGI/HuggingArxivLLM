# 渐进式提示提升图像生成保真度

发布时间：2025年01月13日

`LLM应用

**解释**：这篇论文主要讨论了如何利用大型语言模型（LLM）生成图像的高级和低级描述，并将其应用于扩散变换器（DiT）架构中，以提升图像生成的可控性。虽然论文涉及图像生成技术，但其核心在于LLM的应用，因此应归类为LLM应用。` `图像生成` `计算机视觉`

> Enhancing Image Generation Fidelity via Progressive Prompts

# 摘要

> 扩散变换器（DiT）架构在图像生成领域备受瞩目，显著提升了保真度、性能和多样性。然而，现有基于DiT的方法多聚焦于全局感知合成，区域提示控制的研究相对较少。本文提出了一种从粗到细的区域提示跟随生成管道。具体而言，我们首先利用强大的大型语言模型（LLM）生成图像的高级描述（如内容、主题和对象）和低级描述（如细节和风格）。随后，我们探究了不同深度交叉注意力层的影响，发现深层负责高级内容控制，而浅层则处理低级内容控制。我们将多种提示注入到区域交叉注意力控制中，实现从粗到细的生成。通过这一管道，我们显著提升了基于DiT的图像生成的可控性。大量定量和定性实验表明，该管道能有效提升生成图像的性能。

> The diffusion transformer (DiT) architecture has attracted significant attention in image generation, achieving better fidelity, performance, and diversity. However, most existing DiT - based image generation methods focus on global - aware synthesis, and regional prompt control has been less explored. In this paper, we propose a coarse - to - fine generation pipeline for regional prompt - following generation. Specifically, we first utilize the powerful large language model (LLM) to generate both high - level descriptions of the image (such as content, topic, and objects) and low - level descriptions (such as details and style). Then, we explore the influence of cross - attention layers at different depths. We find that deeper layers are always responsible for high - level content control, while shallow layers handle low - level content control. Various prompts are injected into the proposed regional cross - attention control for coarse - to - fine generation. By using the proposed pipeline, we enhance the controllability of DiT - based image generation. Extensive quantitative and qualitative results show that our pipeline can improve the performance of the generated images.

[Arxiv](https://arxiv.org/abs/2501.07070)