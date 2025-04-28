# Token序列压缩：提升多模态计算效率的新方法

发布时间：2025年04月24日

`其他` `视觉语言模型` `多模态数据`

> Token Sequence Compression for Efficient Multimodal Computing

# 摘要

> 大规模多模态模型（LMMs）的快速发展推动了跨模态推理能力的提升，但同时也带来了高昂的计算代价。本研究聚焦于视觉语言模型领域，揭示了现有视觉编码器的冗余与低效问题，并致力于构建一种适用于多模态数据的自适应压缩方法。通过基准测试和定性分析，我们系统地探讨了多种视觉令牌选择与合并策略。值得注意的是，简单的集群级令牌聚合方法在性能上优于现有最优方法，包括视觉编码器级别合并和注意力机制方法。我们还指出了现有视觉编码器中的冗余现象，并通过跨模态注意力可视化，揭示了视觉令牌选择原则中几个令人费解的趋势。这项研究为更高效地编码和处理高维数据迈出了重要一步，为构建更可扩展、更可持续的多模态系统奠定了基础。

> The exponential growth of Large Multimodal Models (LMMs) has driven advancements in cross-modal reasoning but at significant computational costs. In this work, we focus on visual language models. We highlight the redundancy and inefficiency in current vision encoders, and seek to construct an adaptive compression method for multimodal data. In this work, we characterize a panoply of visual token selection and merging approaches through both benchmarking and qualitative analysis. In particular, we demonstrate that simple cluster-level token aggregation outperforms prior state-of-the-art works in token selection and merging, including merging at the vision encoder level and attention-based approaches. We underline the redundancy in current vision encoders, and shed light on several puzzling trends regarding principles of visual token selection through cross-modal attention visualizations. This work is a first effort towards more effective encoding and processing of high-dimensional data, and paves the way for more scalable and sustainable multimodal systems.

[Arxiv](https://arxiv.org/abs/2504.17892)