# UNIC-Adapter: 基于多模态Transformer的统一图像-指令适配器，助力图像生成

发布时间：2024年12月25日

`其他

理由：这篇论文主要讨论的是文本到图像生成模型的改进，特别是通过引入多模态扩散Transformer架构和统一图像指令适配器（UNIC-Adapter）来实现可控生成。虽然涉及到了多模态和生成模型，但其核心内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等概念。因此，将其分类为“其他”更为合适。` `计算机视觉` `图像生成`

> UNIC-Adapter: Unified Image-instruction Adapter with Multi-modal Transformer for Image Generation

# 摘要

> # 摘要
近期，文本到图像生成模型取得了显著进展，尤其是扩散模型在从文本生成高质量图像方面表现出色。然而，仅凭文本提示，这些模型往往难以精确控制像素级布局、物体外观和全局风格。为解决这一问题，先前研究引入了条件图像作为辅助输入，增强了控制能力，但通常需要为不同参考输入定制专门模型。本文提出了一种新方法，将可控生成统一在一个框架内。我们基于多模态扩散Transformer架构，设计了统一图像指令适配器（UNIC-Adapter），实现了跨多种条件的灵活可控生成，无需多个专门模型。UNIC-Adapter通过结合条件图像和任务指令，有效提取多模态指令信息，并通过增强的旋转位置嵌入交叉注意力机制，将这些信息注入图像生成过程。实验结果表明，UNIC-Adapter在像素级空间控制、主题驱动图像生成和基于风格图像的图像合成等任务中，展现了统一可控图像生成的有效性。

> Recently, text-to-image generation models have achieved remarkable advancements, particularly with diffusion models facilitating high-quality image synthesis from textual descriptions. However, these models often struggle with achieving precise control over pixel-level layouts, object appearances, and global styles when using text prompts alone. To mitigate this issue, previous works introduce conditional images as auxiliary inputs for image generation, enhancing control but typically necessitating specialized models tailored to different types of reference inputs. In this paper, we explore a new approach to unify controllable generation within a single framework. Specifically, we propose the unified image-instruction adapter (UNIC-Adapter) built on the Multi-Modal-Diffusion Transformer architecture, to enable flexible and controllable generation across diverse conditions without the need for multiple specialized models. Our UNIC-Adapter effectively extracts multi-modal instruction information by incorporating both conditional images and task instructions, injecting this information into the image generation process through a cross-attention mechanism enhanced by Rotary Position Embedding. Experimental results across a variety of tasks, including pixel-level spatial control, subject-driven image generation, and style-image-based image synthesis, demonstrate the effectiveness of our UNIC-Adapter in unified controllable image generation.

[Arxiv](https://arxiv.org/abs/2412.18928)