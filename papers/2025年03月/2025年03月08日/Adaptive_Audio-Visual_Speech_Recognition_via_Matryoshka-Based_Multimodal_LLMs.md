# 基于套娃结构的多模态大语言模型实现自适应视听语音识别

发布时间：2025年03月08日

`LLM应用` `语音识别` `多模态`

> Adaptive Audio-Visual Speech Recognition via Matryoshka-Based Multimodal LLMs

# 摘要

> 音频-视觉语音识别（AVSR）结合音频和视觉模态，显著提升了语音识别的鲁棒性，尤其在噪声环境中表现优异。大型语言模型（LLMs）近期在语音识别领域，特别是AVSR方面，展现了强大的能力。然而，由于语音表示的长度问题，直接与LLMs结合会导致巨大的计算负担。以往方法通过压缩语音表示后再输入LLMs来解决这一问题，但更高的压缩率通常会带来性能下降，这就需要在计算效率和识别准确率之间做出权衡。

为解决这一难题，我们提出了Llama-MTSK——首个专为AVSR设计的基于Matryoshka的多模态大型语言模型。该模型能够在保持高性能的同时，根据具体的计算约束灵活调整音频-视觉令牌的分配。受套娃式表示学习的启发，我们的方法在同一模型中对音频-视觉表示进行多粒度编码，避免了为不同压缩级别训练独立模型的需要。

此外，为了高效微调大型语言模型，我们引入了三种基于LoRA的套娃策略，利用全局和特定尺度的LoRA模块。在两个最大AVSR数据集上的广泛评估表明，Llama-MTSK达到了最优性能，与固定压缩级别的独立训练模型相比，其表现持平或更优。

> Audio-Visual Speech Recognition (AVSR) leverages both audio and visual modalities to enhance speech recognition robustness, particularly in noisy environments. Recent advancements in Large Language Models (LLMs) have demonstrated their effectiveness in speech recognition, including AVSR. However, due to the significant length of speech representations, direct integration with LLMs imposes substantial computational costs. Prior approaches address this by compressing speech representations before feeding them into LLMs. However, higher compression ratios often lead to performance degradation, necessitating a trade-off between computational efficiency and recognition accuracy. To address this challenge, we propose Llama-MTSK, the first Matryoshka-based Multimodal LLM for AVSR, which enables flexible adaptation of the audio-visual token allocation based on specific computational constraints while preserving high performance. Our approach, inspired by Matryoshka Representation Learning, encodes audio-visual representations at multiple granularities within a single model, eliminating the need to train separate models for different compression levels. Moreover, to efficiently fine-tune the LLM, we introduce three LoRA-based Matryoshka strategies using global and scale-specific LoRA modules. Extensive evaluations on the two largest AVSR datasets demonstrate that Llama-MTSK achieves state-of-the-art results, matching or surpassing models trained independently at fixed compression levels.

[Arxiv](https://arxiv.org/abs/2503.06362)