# # 摘要  
LLM：高效流处理器，组位置编码解决流批不匹配

发布时间：2025年05月22日

`LLM理论` `流处理`

> LLM as Effective Streaming Processor: Bridging Streaming-Batch Mismatches with Group Position Encoding

# 摘要

> 大型语言模型（LLMs）主要用于批量处理。现有将LLMs适配为流处理的方法，要么依赖昂贵的重新编码，要么采用有限可扩展性的专用架构。本研究识别出将面向批量的LLMs适配为流处理的三个关键不匹配问题：输入注意力机制不匹配、输出注意力机制不匹配以及位置ID不匹配。尽管通常认为后两种不匹配需要频繁重新编码，但我们的分析表明，只有输入注意力机制不匹配显著影响性能，重新编码输出在很大程度上是不必要的。为了更好地理解这一与常见假设的差异，我们首次对流处理中位置编码对LLMs的影响进行了全面分析，发现保持源和目标上下文中的相对位置比维持绝对顺序更为关键。基于此，我们引入了一种基于批量架构的分组位置编码范式，以增强流处理和批量模式之间的一致性。在跨语言和跨模态任务上的大量实验表明，我们的方法优于现有方法。我们的方法无需架构修改，且在流处理和批量模式下均表现出强大的泛化能力。代码可在仓库https://github.com/EIT-NLP/StreamingLLM获取。

> Large Language Models (LLMs) are primarily designed for batch processing. Existing methods for adapting LLMs to streaming rely either on expensive re-encoding or specialized architectures with limited scalability. This work identifies three key mismatches in adapting batch-oriented LLMs to streaming: (1) input-attention, (2) output-attention, and (3) position-ID mismatches. While it is commonly assumed that the latter two mismatches require frequent re-encoding, our analysis reveals that only the input-attention mismatch significantly impacts performance, indicating re-encoding outputs is largely unnecessary. To better understand this discrepancy with the common assumption, we provide the first comprehensive analysis of the impact of position encoding on LLMs in streaming, showing that preserving relative positions within source and target contexts is more critical than maintaining absolute order. Motivated by the above analysis, we introduce a group position encoding paradigm built on batch architectures to enhance consistency between streaming and batch modes. Extensive experiments on cross-lingual and cross-modal tasks demonstrate that our method outperforms existing approaches. Our method requires no architectural modifications, exhibits strong generalization in both streaming and batch modes. The code is available at repository https://github.com/EIT-NLP/StreamingLLM.

[Arxiv](https://arxiv.org/abs/2505.16983)