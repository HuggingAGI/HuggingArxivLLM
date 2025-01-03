# # 分层视觉-语言对齐：基于扩散模型的文本到图像生成

发布时间：2025年01月01日

`LLM应用

**理由**：该论文主要讨论了如何通过视觉语言对齐扩散（VLAD）模型来改进文本到图像的生成，特别是针对复杂文本描述与高质量图像的生成问题。虽然涉及视觉语言模型（LVLMs），但其核心应用场景是文本到图像的生成，属于LLM在特定任务中的应用，因此归类为LLM应用。` `计算机视觉` `图像生成`

> Hierarchical Vision-Language Alignment for Text-to-Image Generation via Diffusion Models

# 摘要

> # 摘要
随着大型视觉语言模型（LVLMs）的整合，文本到图像生成取得了显著进展，但在复杂文本描述与高质量、视觉连贯图像的对齐上仍面临挑战。本文提出视觉语言对齐扩散（VLAD）模型，通过双流策略结合语义对齐和分层扩散，有效应对这些挑战。VLAD采用上下文组合模块（CCM）将文本提示分解为全局和局部表示，确保与视觉特征的精确对齐，并通过多阶段扩散过程和分层指导生成高保真图像。在MARIO-Eval和INNOVATOR-Eval基准上的实验表明，VLAD在图像质量、语义对齐和文本渲染准确性上显著优于现有方法。人类评估进一步验证了VLAD的卓越性能，使其成为复杂场景中文本到图像生成的有力工具。

> Text-to-image generation has witnessed significant advancements with the integration of Large Vision-Language Models (LVLMs), yet challenges remain in aligning complex textual descriptions with high-quality, visually coherent images. This paper introduces the Vision-Language Aligned Diffusion (VLAD) model, a generative framework that addresses these challenges through a dual-stream strategy combining semantic alignment and hierarchical diffusion. VLAD utilizes a Contextual Composition Module (CCM) to decompose textual prompts into global and local representations, ensuring precise alignment with visual features. Furthermore, it incorporates a multi-stage diffusion process with hierarchical guidance to generate high-fidelity images. Experiments conducted on MARIO-Eval and INNOVATOR-Eval benchmarks demonstrate that VLAD significantly outperforms state-of-the-art methods in terms of image quality, semantic alignment, and text rendering accuracy. Human evaluations further validate the superior performance of VLAD, making it a promising approach for text-to-image generation in complex scenarios.

[Arxiv](https://arxiv.org/abs/2501.00917)