# DisCo: 实现视频多模态大型语言模型中显著且连贯的视觉封装

发布时间：2025年07月14日

`LLM应用` `视频处理` `多模态`

> DisCo: Towards Distinct and Coherent Visual Encapsulation in Video MLLMs

# 摘要

> 在视频多模态大型语言模型（video MLLMs）中，视觉封装过程是将视频内容转化为LLM输入的关键环节。尽管线性投影器被广泛用于封装，但它们在处理视频时会导致语义不区分和时间不连贯的问题。相比之下，重采样器的结构在解决这些问题方面展现出潜力，但目前尚未找到有效的解决方案。为此，我们受到重采样器结构的启发，提出了DisCo——一种全新的视觉封装方法，旨在为视频MLLMs生成语义清晰且时间连贯的视觉令牌。DisCo的核心由两个模块组成：（1）视觉概念判别器（VCD），通过将视觉令牌与视频中的判别性概念配对，赋予其独特的语义特征；（2）时间焦点校准器（TFC），确保视觉令牌在每帧视频中保持一致的时间焦点。通过在多个视频MLLM框架上的实验验证，DisCo在各类视频理解基准测试中表现卓越，显著超越现有最优方法，同时得益于语义区分度的提升，实现了更高的令牌效率。代码地址：https://github.com/ZJHTerry18/DisCo。


> In video Multimodal Large Language Models (video MLLMs), the visual encapsulation process plays a pivotal role in converting video contents into representative tokens for LLM input. While linear projectors are widely employed for encapsulation, they introduce semantic indistinctness and temporal incoherence when applied to videos. Conversely, the structure of resamplers shows promise in tackling these challenges, but an effective solution remains unexplored. Drawing inspiration from resampler structures, we introduce DisCo, a novel visual encapsulation method designed to yield semantically distinct and temporally coherent visual tokens for video MLLMs. DisCo integrates two key components: (1) A Visual Concept Discriminator (VCD) module, assigning unique semantics for visual tokens by associating them in pair with discriminative concepts in the video. (2) A Temporal Focus Calibrator (TFC) module, ensuring consistent temporal focus of visual tokens to video elements across every video frame. Through extensive experiments on multiple video MLLM frameworks, we demonstrate that DisCo remarkably outperforms previous state-of-the-art methods across a variety of video understanding benchmarks, while also achieving higher token efficiency thanks to the reduction of semantic indistinctness. The code: https://github.com/ZJHTerry18/DisCo.

[Arxiv](https://arxiv.org/abs/2507.10302)