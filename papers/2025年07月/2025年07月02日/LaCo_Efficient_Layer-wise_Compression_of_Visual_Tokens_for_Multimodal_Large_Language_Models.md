# LaCo：多模态大语言模型的高效分层视觉令牌压缩

发布时间：2025年07月02日

`LLM应用

理由：这篇论文讨论了多模态大型语言模型 (MLLMs) 中的视觉令牌压缩方法，并提出了一种新的框架 LaCo，用于在视觉编码器的中间层实现有效的令牌压缩。这属于对大型语言模型的应用优化，特别是提升模型的效率和性能。因此，它属于LLM应用类别。` `计算机视觉`

> LaCo: Efficient Layer-wise Compression of Visual Tokens for Multimodal Large Language Models

# 摘要

> 目前针对多模态大型语言模型 (MLLMs) 的视觉令牌压缩方法主要作为后编码器模块运行，这限制了它们在效率提升方面的潜力。为了解决这一限制，我们提出了一种名为 LaCo (Layer-wise Visual Token Compression) 的新框架，该框架能够在视觉编码器的中间层实现有效的令牌压缩。LaCo引入了两个核心组件：1) 一种分层像素混洗机制，通过空间到通道的变换系统地合并相邻令牌；2) 一种带有非参数快捷方式的残差学习架构，在压缩过程中保留关键视觉信息。大量实验表明，与现有方法相比，我们在视觉编码器的中间层压缩令牌时，LaCo表现更优，效果显著。此外，与外部压缩相比，我们的方法在保持强劲性能的同时，将训练效率提升了超过 20%，推理吞吐量提升了 15%以上。

> Existing visual token compression methods for Multimodal Large Language Models (MLLMs) predominantly operate as post-encoder modules, limiting their potential for efficiency gains. To address this limitation, we propose LaCo (Layer-wise Visual Token Compression), a novel framework that enables effective token compression within the intermediate layers of the vision encoder. LaCo introduces two core components: 1) a layer-wise pixel-shuffle mechanism that systematically merges adjacent tokens through space-to-channel transformations, and 2) a residual learning architecture with non-parametric shortcuts that preserves critical visual information during compression. Extensive experiments indicate that our LaCo outperforms all existing methods when compressing tokens in the intermediate layers of the vision encoder, demonstrating superior effectiveness. In addition, compared to external compression, our method improves training efficiency beyond 20% and inference throughput over 15% while maintaining strong performance.

[Arxiv](https://arxiv.org/abs/2507.02279)