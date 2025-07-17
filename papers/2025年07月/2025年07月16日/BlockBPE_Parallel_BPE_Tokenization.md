# BlockBPE：并行 BPE 分词

发布时间：2025年07月16日

`LLM应用` `计算机体系结构`

> BlockBPE: Parallel BPE Tokenization

# 摘要

> 分词是大型语言模型流水线中的关键预处理步骤，但目前广泛使用的实现仍受CPU性能限制，且在GPU上的批量推理工作流中表现欠佳。我们提出了BlockBPE，这是一种基于字节对编码（BPE）的并行GPU实现，能够在合理假设下实现接近线性时间复杂度，并针对高吞吐量批量推理进行了优化。与现有的基于Rust的分词器（如HuggingFace Tokenizers或OpenAI的tiktoken）不同，这些分词器的运行时间主要由Regex预分词决定，且表现出【数学公式】的运行时间。BlockBPE通过消除Regex预分词步骤，虽然导致生成质量略有下降，但能够在线程块内实现高度并行的token合并，将整体复杂度降低至【数学公式】，其中$d \ll n$。在高批量推理工作负载下，BlockBPE的吞吐量比tiktoken高出2倍，比HuggingFace Tokenizers高出2.5倍。

> Tokenization is a critical preprocessing step in large language model pipelines, yet widely-used implementations remain CPU-bound and suboptimal for batch inference workflows on GPU. We present BlockBPE, a parallel GPU implementation of byte-pair encoding (BPE) that achieves near linear-time complexity under realistic assumptions and is optimized for high-throughput, batch inference. Unlike existing Rust-based tokenizers such as HuggingFace Tokenizers or OpenAI's tiktoken-whose runtimes are dominated by Regex pre-tokenization and exhibit $O(n \log n)$ runtime-BlockBPE eliminates the Regex pre-tokenization which leads to small loss in generation quality, but enables highly parallelized token merges within thread blocks, reducing overall complexity to $O(nd)$ where $d \ll n$. On high-batch inference workloads, BlockBPE achieves up to 2x higher throughput than tiktoken and 2.5x over HuggingFace Tokenizers.

[Arxiv](https://arxiv.org/abs/2507.11941)