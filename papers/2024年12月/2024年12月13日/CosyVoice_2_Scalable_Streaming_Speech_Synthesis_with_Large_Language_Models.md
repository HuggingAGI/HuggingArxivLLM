# CosyVoice 2：借助大型语言模型实现可扩展的流式语音合成

发布时间：2024年12月13日

`LLM应用` `语音合成` `多语言处理`

> CosyVoice 2: Scalable Streaming Speech Synthesis with Large Language Models

# 摘要

> 在我们先前的工作里，我们推出了 CosyVoice，这是一个基于有监督离散语音令牌的多语言语音合成模型。借助使用两种热门的生成模型（语言模型（LMs）和流匹配）进行渐进式语义解码，CosyVoice 在语音上下文学习中展现出高韵律自然度、内容一致性以及说话者相似度。近来，多模态大型语言模型（LLMs）取得重大突破，其中语音合成的响应延迟和实时因子在交互体验中至关重要。所以，在本报告中，我们呈现了一种改进的流式语音合成模型 CosyVoice 2，它涵盖了全面且系统的优化。具体而言，我们引入有限标量量化来提升语音令牌的码本利用率。对于文本-语音语言模型，我们精简了模型架构，能够直接将预先训练好的 LLM 用作骨干。另外，我们开发了一个块感知因果流匹配模型，以支持各类合成场景，在单个模型中实现流式和非流式合成。通过在大规模多语言数据集上训练，CosyVoice 2 在流式模式下达成了与人类相当的自然度、极小的响应延迟以及近乎无损的合成质量。诚邀读者前往 https://funaudiollm.github.io/cosyvoice2 收听演示。

> In our previous work, we introduced CosyVoice, a multilingual speech synthesis model based on supervised discrete speech tokens. By employing progressive semantic decoding with two popular generative models, language models (LMs) and Flow Matching, CosyVoice demonstrated high prosody naturalness, content consistency, and speaker similarity in speech in-context learning. Recently, significant progress has been made in multi-modal large language models (LLMs), where the response latency and real-time factor of speech synthesis play a crucial role in the interactive experience. Therefore, in this report, we present an improved streaming speech synthesis model, CosyVoice 2, which incorporates comprehensive and systematic optimizations. Specifically, we introduce finite-scalar quantization to improve the codebook utilization of speech tokens. For the text-speech LM, we streamline the model architecture to allow direct use of a pre-trained LLM as the backbone. In addition, we develop a chunk-aware causal flow matching model to support various synthesis scenarios, enabling both streaming and non-streaming synthesis within a single model. By training on a large-scale multilingual dataset, CosyVoice 2 achieves human-parity naturalness, minimal response latency, and virtually lossless synthesis quality in the streaming mode. We invite readers to listen to the demos at https://funaudiollm.github.io/cosyvoice2.

[Arxiv](https://arxiv.org/abs/2412.10117)