# Llasa+: 加速与流式Llama语音合成的免费午餐

发布时间：2025年08月08日

`LLM应用` `语音合成` `实时处理`

> Llasa+: Free Lunch for Accelerated and Streaming Llama-Based Speech Synthesis

# 摘要

> # 摘要  
文本到语音（TTS）领域近期取得了令人瞩目的进展，尤其是在大型语言模型（LLM）方法的推动下，展现了极高的自然度和灵活性。然而，现有的自回归（AR）结构和大规模模型，如Llasa，在推理延迟和流式合成方面仍面临诸多挑战。为突破这些限制，我们推出了Llasa+——一款基于Llasa的加速流式TTS模型。  
具体而言，我们通过在冻结的主干后加入两个即插即用的多令牌预测（MTP）模块，实现了生成过程的加速。这些模块使模型能够一次性预测多个令牌。同时，为缓解MTP不准确引发的潜在错误传播问题，我们设计了一种创新的验证算法，利用冻结的主干对生成的令牌进行验证，从而确保Llasa+在加速过程中生成质量不受影响。此外，我们还开发了一种因果解码器，支持从令牌中进行流式语音重构。  
实验结果表明，Llasa+实现了1.48倍的速度提升，且生成质量保持不变，尽管其仅基于LibriTTS进行训练。更值得一提的是，MTP和验证框架具有广泛的适用性，可应用于加速任何基于LLM的模型。所有代码和模型均已开源，访问地址为https://github.com/ASLP-lab/LLaSA_Plus。

> Recent progress in text-to-speech (TTS) has achieved impressive naturalness and flexibility, especially with the development of large language model (LLM)-based approaches. However, existing autoregressive (AR) structures and large-scale models, such as Llasa, still face significant challenges in inference latency and streaming synthesis. To deal with the limitations, we introduce Llasa+, an accelerated and streaming TTS model built on Llasa. Specifically, to accelerate the generation process, we introduce two plug-and-play Multi-Token Prediction (MTP) modules following the frozen backbone. These modules allow the model to predict multiple tokens in one AR step. Additionally, to mitigate potential error propagation caused by inaccurate MTP, we design a novel verification algorithm that leverages the frozen backbone to validate the generated tokens, thus allowing Llasa+ to achieve speedup without sacrificing generation quality. Furthermore, we design a causal decoder that enables streaming speech reconstruction from tokens. Extensive experiments show that Llasa+ achieves a 1.48X speedup without sacrificing generation quality, despite being trained only on LibriTTS. Moreover, the MTP-and-verification framework can be applied to accelerate any LLM-based model. All codes and models are publicly available at https://github.com/ASLP-lab/LLaSA_Plus.

[Arxiv](https://arxiv.org/abs/2508.06262)