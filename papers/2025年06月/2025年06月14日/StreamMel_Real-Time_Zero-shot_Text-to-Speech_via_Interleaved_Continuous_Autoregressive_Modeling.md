# # StreamMel：通过交错连续自回归建模实现实时零样本文本到语音转换

发布时间：2025年06月14日

`LLM应用` `语音处理` `实时语音生成`

> StreamMel: Real-Time Zero-shot Text-to-Speech via Interleaved Continuous Autoregressive Modeling

# 摘要

> 零样本语音合成的最新进展已能为未见过的说话人生成高质量语音，但现有系统多因离线设计而不适用于实时场景。当前流式TTS方法通常依赖多阶段处理和离散表征，导致计算开销大、性能欠佳。本研究提出StreamMel——首个专注于连续梅尔频谱建模的单阶段流式TTS框架。通过将文本与声学特征交错处理，StreamMel实现了低延迟自回归合成，同时保持高说话人相似度和自然度。LibriSpeech实验表明，StreamMel在音质与延迟方面均超越现有流式TTS基线。其性能甚至可比肩离线系统，同时支持高效实时生成，为实时语音大语言模型的集成提供了广阔前景。更多音频示例请访问：https://aka.ms/StreamMel。

> Recent advances in zero-shot text-to-speech (TTS) synthesis have achieved high-quality speech generation for unseen speakers, but most systems remain unsuitable for real-time applications because of their offline design. Current streaming TTS paradigms often rely on multi-stage pipelines and discrete representations, leading to increased computational cost and suboptimal system performance. In this work, we propose StreamMel, a pioneering single-stage streaming TTS framework that models continuous mel-spectrograms. By interleaving text tokens with acoustic frames, StreamMel enables low-latency, autoregressive synthesis while preserving high speaker similarity and naturalness. Experiments on LibriSpeech demonstrate that StreamMel outperforms existing streaming TTS baselines in both quality and latency. It even achieves performance comparable to offline systems while supporting efficient real-time generation, showcasing broad prospects for integration with real-time speech large language models. Audio samples are available at: https://aka.ms/StreamMel.

[Arxiv](https://arxiv.org/abs/2506.12570)