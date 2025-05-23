# 大型语言模型：卓越的流处理器——利用组位置编码连接流与批处理差异

发布时间：2025年05月22日

`LLM理论` `流处理`

> LLM as Effective Streaming Processor: Bridging Streaming-Batch Mismatches with Group Position Encoding

# 摘要

> 大型语言模型（LLMs）主要面向批处理设计。现有适配流处理的方法，或是依赖昂贵的重新编码，或是采用扩展性有限的专用架构。本研究发现，将批处理导向的LLMs适配流处理存在三大关键不匹配：输入注意力、输出注意力和位置ID不匹配。尽管人们普遍认为后两者需要频繁重新编码，但我们的分析揭示，唯有输入注意力不匹配显著影响性能，表明重新编码输出大多可省。为深入理解这一与常见认知的差异，我们首次全面解析了位置编码在流处理中对LLMs的影响，发现相较于维持绝对顺序，在源目标上下文中保持相对位置更为关键。基于此分析，我们提出了一种基于批处理架构的分组位置编码范式，以增强流处理与批处理模式的一致性。在跨语言和跨模态任务上的广泛实验表明，我们的方法超越现有方案。我们的方法无需架构改动，在流处理和批处理模式下均展现出强大的泛化能力。代码可在仓库 https://github.com/EIT-NLP/StreamingLLM 获取。

> Large Language Models (LLMs) are primarily designed for batch processing. Existing methods for adapting LLMs to streaming rely either on expensive re-encoding or specialized architectures with limited scalability. This work identifies three key mismatches in adapting batch-oriented LLMs to streaming: (1) input-attention, (2) output-attention, and (3) position-ID mismatches. While it is commonly assumed that the latter two mismatches require frequent re-encoding, our analysis reveals that only the input-attention mismatch significantly impacts performance, indicating re-encoding outputs is largely unnecessary. To better understand this discrepancy with the common assumption, we provide the first comprehensive analysis of the impact of position encoding on LLMs in streaming, showing that preserving relative positions within source and target contexts is more critical than maintaining absolute order. Motivated by the above analysis, we introduce a group position encoding paradigm built on batch architectures to enhance consistency between streaming and batch modes. Extensive experiments on cross-lingual and cross-modal tasks demonstrate that our method outperforms existing approaches. Our method requires no architectural modifications, exhibits strong generalization in both streaming and batch modes. The code is available at repository https://github.com/EIT-NLP/StreamingLLM.

[Arxiv](https://arxiv.org/abs/2505.16983)