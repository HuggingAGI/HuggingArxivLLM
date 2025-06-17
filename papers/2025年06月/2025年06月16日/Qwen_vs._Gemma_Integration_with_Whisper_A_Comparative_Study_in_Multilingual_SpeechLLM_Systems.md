# Qwen 与 Gemma 的对比研究：在多语言语音 LLM 系统中与 Whisper 的比较分析

发布时间：2025年06月16日

`LLM应用

理由：这篇论文主要讨论了将大型语言模型应用于多语言语音识别和语言建模的具体实现方法，属于LLM的应用层面。` `语音识别` `语音技术`

> Qwen vs. Gemma Integration with Whisper: A Comparative Study in Multilingual SpeechLLM Systems

# 摘要

> 本文介绍了我们参加 MLC-SLM Challenge 2025 的系统，专注于利用大型语言模型 (LLMs) 实现多语言语音识别和语言建模。我们的方案融合了微调的 Whisper-large-v3 编码器、高效投影器架构以及多样化解码器配置。通过三阶段训练策略，我们依次优化编码器、投影器和 LLM 组件。在测试中，使用 Gemma3-12B 和 Qwen2.5-7B 作为解码器仅语言模型时，系统分别达到了 16.63% 和 18.6% 的 WER/CER 平均成绩，展现出强劲的竞争力。

> This paper presents our system for the MLC-SLM Challenge 2025, focusing on multilingual speech recognition and language modeling with large language models (LLMs). Our approach combines a fine-tuned Whisper-large-v3 encoder with efficient projector architectures and various decoder configurations. We employ a three-stage training methodology that progressively optimizes the encoder, projector, and LLM components. Our system achieves competitive performance with a private test average WER/CER result of 16.63% using the Gemma3-12B and 18.6% using the Qwen2.5-7B as decoder-only language model.

[Arxiv](https://arxiv.org/abs/2506.13596)