# FastKV: 基于令牌选择性传播的KV缓存压缩，助力快速长上下文处理

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何通过改进键值（KV）缓存压缩方法来提升大型语言模型（LLMs）在处理长上下文序列时的计算效率和内存使用。具体来说，论文提出了FastKV方法，通过创新的Token-Selective Propagation（TSP）策略和分组查询注意力（GQA）感知的KV缓存压缩，显著降低了延迟并提升了吞吐量。这些改进直接应用于LLMs的实际运行中，属于LLM应用的范畴。` `计算优化`

> FastKV: KV Cache Compression for Fast Long-Context Processing with Token-Selective Propagation

# 摘要

> 尽管大型语言模型（LLMs）在处理长上下文序列时表现出色，但其所需的键值（KV）缓存会显著拖累计算效率和内存使用。以往的KV缓存压缩方法主要聚焦于减少内存占用，但在降低延迟方面效果有限。为此，我们提出了FastKV，一种专为提升长上下文序列延迟而设计的KV缓存压缩方法。FastKV采用了一种创新的Token-Selective Propagation（TSP）策略，在LLMs的初始层保留完整上下文信息，并在更深层中仅选择性地传播部分信息，即使在预填充阶段也是如此。此外，FastKV还结合了分组查询注意力（GQA）感知的KV缓存压缩，充分利用GQA在内存和计算效率上的优势。实验结果显示，与当前最先进的KV缓存压缩方法HeadKV相比，FastKV在首词时间（TTFT）和吞吐量上分别提升了2.00倍和1.40倍。同时，FastKV在长上下文基准测试中保持了与基线相当的准确性。代码已开源，地址为https://github.com/dongwonjo/FastKV。

> While large language models (LLMs) excel at handling long-context sequences, they require substantial key-value (KV) caches to store contextual information, which can heavily burden computational efficiency and memory usage. Previous efforts to compress these KV caches primarily focused on reducing memory demands but were limited in enhancing latency. To address this issue, we introduce FastKV, a KV cache compression method designed to enhance latency for long-context sequences. To enhance processing speeds while maintaining accuracy, FastKV adopts a novel Token-Selective Propagation (TSP) approach that retains the full context information in the initial layers of LLMs and selectively propagates only a portion of this information in deeper layers even in the prefill stage. Additionally, FastKV incorporates grouped-query attention (GQA)-aware KV cache compression to exploit the advantages of GQA in both memory and computational efficiency. Our experimental results show that FastKV achieves 2.00$\times$ and 1.40$\times$ improvements in time-to-first-token (TTFT) and throughput, respectively, compared to HeadKV, the state-of-the-art KV cache compression method. Moreover, FastKV successfully maintains accuracy on long-context benchmarks at levels comparable to the baselines. Our code is available at https://github.com/dongwonjo/FastKV.

[Arxiv](https://arxiv.org/abs/2502.01068)