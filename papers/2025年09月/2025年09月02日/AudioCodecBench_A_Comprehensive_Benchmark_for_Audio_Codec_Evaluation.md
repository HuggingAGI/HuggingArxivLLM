# AudioCodecBench：音频编解码器评估的全面基准

发布时间：2025年09月02日

`LLM理论` `媒体与娱乐`

> AudioCodecBench: A Comprehensive Benchmark for Audio Codec Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）已在语音和音乐领域广泛应用，这一趋势推动了对大型模型（LMs）音频 tokenization 的关注。与仅含语义的文本令牌不同，音频令牌需同时捕捉全局语义内容并保留细粒度声学细节，还能为语音和音乐提供离散表示方法，从而有效集成到 MLLMs 中。然而，现有研究对语义令牌与声学令牌的定义不够恰当；此外，编解码器评估常局限于特定领域或任务（如音频重建、自动语音识别（ASR）），难以实现公平全面的对比。针对这些问题，本文明确了语义令牌与声学令牌的合理定义，并提出一套系统评估框架。该框架从四个维度全面衡量编解码器性能：音频重建质量、码本索引（ID）稳定性、仅解码器Transformer困惑度及下游探测任务表现。研究结果验证了所提定义的合理性，并揭示了重建指标、码本ID稳定性、下游任务性能与困惑度之间的关联性。

> Multimodal Large Language Models (MLLMs) have been widely applied in speech and music. This tendency has led to a focus on audio tokenization for Large Models (LMs). Unlike semantic-only text tokens, audio tokens must both capture global semantic content and preserve fine-grained acoustic details. Moreover, they provide a discrete method for speech and music that can be effectively integrated into MLLMs. However, existing research is unsuitable in the definitions of semantic tokens and acoustic tokens. In addition, the evaluation of different codecs typically concentrates on specific domains or tasks, such as reconstruction or Automatic Speech Recognition (ASR) task, which prevents fair and comprehensive comparisons. To address these problems, this paper provides suitable definitions for semantic and acoustic tokens and introduces a systematic evaluation framework. This framework allows for a comprehensive assessment of codecs' capabilities which evaluate across four dimensions: audio reconstruction metric, codebook index (ID) stability, decoder-only transformer perplexity, and performance on downstream probe tasks. Our results show the correctness of the provided suitable definitions and the correlation among reconstruction metrics, codebook ID stability, downstream probe tasks and perplexity.

[Arxiv](https://arxiv.org/abs/2509.02349)