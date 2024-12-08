# 对 Transformer 进行缩放以用于低比特率高质量语音编码

发布时间：2024年11月29日

`其他` `AI 管道`

> Scaling Transformers for Low-Bitrate High-Quality Speech Coding

# 摘要

> 语音通过神经音频编解码模型进行标记化，这在现代 AI 管道中，无论是单独还是在多模态情境下生成或理解语音，都是至关重要的一部分。传统上，这类标记化模型侧重于低参数数量的架构，仅采用具有强归纳偏差的组件。在本研究中，我们展示，将具有大量参数的 Transformer 架构应用于此问题，并采用基于灵活有限标量量化（FSQ）的瓶颈，能够在每秒 400 或 700 比特这样极低的比特率下达到顶尖的语音质量。训练出的模型在客观和主观测试中，都显著优于现有的基线。

> The tokenization of speech with neural audio codec models is a vital part of modern AI pipelines for the generation or understanding of speech, alone or in a multimodal context. Traditionally such tokenization models have concentrated on low parameter-count architectures using only components with strong inductive biases. In this work we show that by scaling a transformer architecture with large parameter count to this problem, and applying a flexible Finite Scalar Quantization (FSQ) based bottleneck, it is possible to reach state-of-the-art speech quality at extremely low bit-rates of $400$ or $700$ bits-per-second. The trained models strongly out-perform existing baselines in both objective and subjective tests.

[Arxiv](https://arxiv.org/abs/2411.19842)