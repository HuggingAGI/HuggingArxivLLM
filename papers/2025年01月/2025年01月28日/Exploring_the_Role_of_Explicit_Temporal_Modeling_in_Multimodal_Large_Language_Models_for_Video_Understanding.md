# 探索显式时间建模在多模态大语言模型中的角色，助力视频理解

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要探讨了如何将多模态大型语言模型（MLLMs）应用于视频理解，特别是通过引入可堆叠时间编码器（STE）来改进时间建模。这属于将大型语言模型应用于特定任务（视频理解）的研究，因此归类为LLM应用。` `视频理解` `多模态学习`

> Exploring the Role of Explicit Temporal Modeling in Multimodal Large Language Models for Video Understanding

# 摘要

> 将多模态大型语言模型（MLLMs）应用于视频理解面临巨大挑战，因为需要建模跨帧的时间关系。现有方法要么依赖LLM解码器进行隐式时间建模，要么使用辅助时间编码器进行显式时间建模。为了探讨这两种范式的优劣，我们提出了可堆叠时间编码器（STE）。STE通过可调的时间感受野和令牌压缩比，实现了灵活的显式时间建模。利用STE，我们系统比较了隐式和显式时间建模在整体性能、令牌压缩效果和时间特定理解等方面的表现。此外，我们还探讨了STE作为插件模块和在图像模态中的设计考量及其广泛影响。研究结果凸显了显式时间建模的关键作用，为视频MLLMs的发展提供了实用见解。

> Applying Multimodal Large Language Models (MLLMs) to video understanding presents significant challenges due to the need to model temporal relations across frames. Existing approaches adopt either implicit temporal modeling, relying solely on the LLM decoder, or explicit temporal modeling, employing auxiliary temporal encoders. To investigate this debate between the two paradigms, we propose the Stackable Temporal Encoder (STE). STE enables flexible explicit temporal modeling with adjustable temporal receptive fields and token compression ratios. Using STE, we systematically compare implicit and explicit temporal modeling across dimensions such as overall performance, token compression effectiveness, and temporal-specific understanding. We also explore STE's design considerations and broader impacts as a plug-in module and in image modalities. Our findings emphasize the critical role of explicit temporal modeling, providing actionable insights to advance video MLLMs.

[Arxiv](https://arxiv.org/abs/2501.16786)