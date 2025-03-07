# # 层级别熵加权量化的普遍性超越模型架构与规模
研究层级别熵加权量化方法在不同模型架构和规模上的普遍性表现。

发布时间：2025年03月06日

`LLM应用

摘要讨论了模型压缩和量化技术，特别是针对大型语言模型（LLMs）的优化和部署，属于应用层面的改进和优化。` `模型压缩`

> Universality of Layer-Level Entropy-Weighted Quantization Beyond Model Architecture and Size

# 摘要

> 我们提出了一种基于熵加权量化（EWQ）的新型选择性模型量化方法，突破了传统架构特定和尺寸依赖压缩方法在大型语言模型（LLMs）上的局限性。通过分析变压器块中的熵分布，EWQ能够智能识别哪些块可以安全量化而不影响性能，且完全独立于模型架构和尺寸。与均匀量化方法相比，我们的方法不仅将内存使用减少高达18%，还能保持与未量化模型相差不超过0.5%的多任务语言理解（MMLU）准确度。我们在从1.6B到70B参数的多个架构上展示了EWQ的卓越效果，证明了其在质量-压缩权衡方面的显著优势，无论模型规模或架构如何。令人惊喜的是，EWQ不仅降低了困惑度，还通过选择性精度降低实现了有益的正则化效果，这一发现跨越了不同模型家族，揭示了层级熵与最优精度要求之间的深层联系。此外，我们还推出了FastEWQ，一种无需加载模型权重的快速熵分布分析方法。该技术巧妙运用了在各种架构和规模中普遍存在的熵分布特性，能够在保持80%分类准确度的同时实现近乎即时的量化决策。我们的研究成果证明，有效的量化策略可以完全独立于特定的架构选择或模型尺寸开发，为高效部署大型语言模型开辟了全新可能。


> We present a novel approach to selective model quantization that transcends the limitations of architecture-specific and size-dependent compression methods for Large Language Models (LLMs) using Entropy-Weighted Quantization (EWQ). By analyzing the entropy distribution across transformer blocks, EWQ determines which blocks can be safely quantized without causing significant performance degradation, independent of model architecture or size. Our method outperforms uniform quantization approaches, maintaining Massive Multitask Language Understanding (MMLU) accuracy scores within 0.5% of unquantized models while reducing memory usage by up to 18%. We demonstrate the effectiveness of EWQ across multiple architectures-from 1.6B to 70B parameters-showcasing consistent improvements in the quality-compression trade-off regardless of model scale or architectural design. A surprising finding of EWQ is its ability to reduce perplexity compared to unquantized models, suggesting the presence of beneficial regularization through selective precision reduction. This improvement holds across different model families, indicating a fundamental relationship between layer-level entropy and optimal precision requirements. Additionally, we introduce FastEWQ, a rapid method for entropy distribution analysis that eliminates the need for loading model weights. This technique leverages universal characteristics of entropy distribution that persist across various architectures and scales, enabling near-instantaneous quantization decisions while maintaining 80% classification accuracy with full entropy analysis. Our results demonstrate that effective quantization strategies can be developed independently of specific architectural choices or model sizes, opening new possibilities for efficient LLM deployment.

[Arxiv](https://arxiv.org/abs/2503.04704)