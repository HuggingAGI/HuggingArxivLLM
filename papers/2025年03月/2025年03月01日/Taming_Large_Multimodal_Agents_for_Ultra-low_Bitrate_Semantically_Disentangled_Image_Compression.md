# 驾驭大型多模态智能体实现超低比特率语义解耦图像压缩

发布时间：2025年03月01日

`LLM应用` `图像处理` `计算机视觉`

> Taming Large Multimodal Agents for Ultra-low Bitrate Semantically Disentangled Image Compression

# 摘要

> 在超低比特率（≤0.05 bpp）下实现图像的语义一致性和高质量感知压缩仍是一个重大挑战。本文提出了一种名为语义解耦图像压缩（SEDIC）的新颖框架。SEDIC利用大型多模态模型（LMMs）将图像分解为多个关键语义信息，包括极度压缩的参考图像、整体与对象级别的文本描述以及语义掩码。我们设计了多阶段语义解码器，逐步按对象恢复传输的参考图像，最终生成高质量且感知一致的重建图像。在每个解码阶段，SEDIC采用预训练的可控扩散模型，根据文本描述和语义掩码在参考图像上恢复对象细节。实验结果表明，SEDIC显著优于现有方法，实现了卓越的感知质量和语义一致性。我们的代码可在https://github.com/yang-xidian/SEDIC获取。

> It remains a significant challenge to compress images at ultra-low bitrate while achieving both semantic consistency and high perceptual quality. We propose a novel image compression framework, Semantically Disentangled Image Compression (SEDIC) in this paper. Our proposed SEDIC leverages large multimodal models (LMMs) to disentangle the image into several essential semantic information, including an extremely compressed reference image, overall and object-level text descriptions, and the semantic masks. A multi-stage semantic decoder is designed to progressively restore the transmitted reference image object-by-object, ultimately producing high-quality and perceptually consistent reconstructions. In each decoding stage, a pre-trained controllable diffusion model is utilized to restore the object details on the reference image conditioned by the text descriptions and semantic masks. Experimental results demonstrate that SEDIC significantly outperforms state-of-the-art approaches, achieving superior perceptual quality and semantic consistency at ultra-low bitrates ($\le$ 0.05 bpp). Our code is available at https://github.com/yang-xidian/SEDIC.

[Arxiv](https://arxiv.org/abs/2503.00399)