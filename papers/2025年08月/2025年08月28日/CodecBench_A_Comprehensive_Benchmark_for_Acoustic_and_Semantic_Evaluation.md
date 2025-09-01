# CodecBench：针对声学和语义评估的全面基准测试

发布时间：2025年08月28日

`LLM应用` `媒体与娱乐`

> CodecBench: A Comprehensive Benchmark for Acoustic and Semantic Evaluation

# 摘要

> 随着多模态大型语言模型（LLMs）的崛起，音频编解码器在音频转离散令牌编码中愈发关键，成为实现音频与文本LLMs融合的核心技术。当前的音频编解码器主要捕获两类信息：声学特征与语义内容。然而，当音频编解码器被应用于语音语言模型的多样化场景时，其需处理的信息复杂度不断提升，还需适应多说话人、背景噪声及更丰富副语言信息等复杂语境。但现有编解码器的评估体系仍受限于简单指标与单一场景，且现有音频编解码器基准并未针对复杂应用场景设计，导致其在复杂数据集上对声学与语义能力的评估表现大打折扣。为此，我们提出综合评估数据集CodecBench，从声学与语义双重视角出发，在四个数据领域对音频编解码器性能进行全面测评。该基准旨在揭示现有技术瓶颈，明确未来研究方向，推动音频编解码器技术的进一步突破。代码开源地址：https://github.com/RayYuki/CodecBench。

> With the rise of multimodal large language models (LLMs), audio codec plays an increasingly vital role in encoding audio into discrete tokens, enabling integration of audio into text-based LLMs. Current audio codec captures two types of information: acoustic and semantic. As audio codec is applied to diverse scenarios in speech language model , it needs to model increasingly complex information and adapt to varied contexts, such as scenarios with multiple speakers, background noise, or richer paralinguistic information. However, existing codec's own evaluation has been limited by simplistic metrics and scenarios, and existing benchmarks for audio codec are not designed for complex application scenarios, which limits the assessment performance on complex datasets for acoustic and semantic capabilities. We introduce CodecBench, a comprehensive evaluation dataset to assess audio codec performance from both acoustic and semantic perspectives across four data domains. Through this benchmark, we aim to identify current limitations, highlight future research directions, and foster advances in the development of audio codec. The codes are available at https://github.com/RayYuki/CodecBench.

[Arxiv](https://arxiv.org/abs/2508.20660)