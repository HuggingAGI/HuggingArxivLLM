# BlockDialect: 面向高效能 LLM 推理的块级细粒度混合格式

发布时间：2025年01月02日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型（LLMs）的量化技术，特别是细粒度块级量化方法，以解决内存和计算成本的问题。论文提出了新的量化格式和技术（如BlockDialect和DialectFP4），并展示了其在LLM推理中的性能提升。这些内容属于对LLM底层技术的改进和优化，因此应归类为LLM理论。` `人工智能` `硬件优化`

> BlockDialect: Block-wise Fine-grained Mixed Format for Energy-Efficient LLM Inference

# 摘要

> 大型语言模型（LLMs）虽取得了显著成就，但其规模膨胀带来了内存和计算成本的巨大挑战。量化权重和激活是解决之道，而细粒度块级量化作为一种硬件支持的方案，能有效应对异常值问题。然而，现有方法难以捕捉块数据的细微分布。为此，我们提出了BlockDialect，一种块级细粒度混合格式技术，它从格式库中为每个块分配最优数字格式，以提升数据表示效果。我们还引入了DialectFP4，这是一个FP4变体（类似方言）的格式库，能灵活适应多样化的数据分布。DialectFP4通过选择可表示为低精度整数算术的缩放整数，确保了硬件效率。此外，我们提出了一种两阶段方法，用于在线DialectFP4激活量化。与MXFP4格式相比，BlockDialect在LLaMA3-8B（LLaMA2-7B）模型上实现了11.40%（6.90%）的准确率提升，同时在使用相同比特数的情况下，仅比全精度低5.89%（3.31%），即使在全路径矩阵乘法量化时也是如此。我们的工作专注于如何表示而非如何缩放，为高效能的LLM推理开辟了一条新路径。

> Large Language Models (LLMs) have achieved remarkable success, but their increasing size poses significant challenges in memory usage and computational costs. Quantizing both weights and activations can address these issues, with fine-grained block-wise quantization emerging as a promising hardware-supported solution to mitigate outliers. However, existing methods struggle to capture nuanced block data distributions. To address this, we propose BlockDialect, a block-wise fine-grained mixed format technique that assigns a per-block optimal number format from formatbook for better data representation. Additionally, we introduce DialectFP4, a formatbook of FP4 variants (akin to dialects) that adapt to diverse data distributions. Importantly, DialectFP4 ensures hardware efficiency by selecting representable values as scaled integers compatible with low-precision integer arithmetic. Furthermore, we propose a two-stage approach for online DialectFP4 activation quantization. BlockDialect achieves 11.40% (6.90%) accuracy gain on the LLaMA3-8B (LLaMA2-7B) model compared to MXFP4 format with a comparable bit usage per data, while being only 5.89% (3.31%) below full precision even when quantizing full-path matrix multiplication. Focusing on how to represent over how to scale, our work presents a promising path for energy-efficient LLM inference.

[Arxiv](https://arxiv.org/abs/2501.01144)