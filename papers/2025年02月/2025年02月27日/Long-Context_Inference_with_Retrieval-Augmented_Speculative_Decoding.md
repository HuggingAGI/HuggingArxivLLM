# 长上下文推理：增强型推测解码

发布时间：2025年02月27日

`RAG` `文本处理`

> Long-Context Inference with Retrieval-Augmented Speculative Decoding

# 摘要

> 长上下文大型语言模型（LLMs）的出现为处理长篇文档提供了一种有前景的替代方案，替代了传统的检索增强生成（RAG）。然而，长上下文推理的计算开销，特别是在管理键值（KV）缓存方面，带来了显著的效率挑战。虽然传统的Speculative Decoding（SD）方法通过使用较小的草稿模型加速推理，但其在长上下文场景下的有效性因内存受限的KV缓存操作而大幅降低。我们提出了一种名为检索增强推测解码（RAPID）的方法，该方法利用RAG技术在长上下文推理中同时加速生成并提升生成质量。RAPID引入了RAG草稿——一种基于缩短检索上下文运行的草稿LLM——来推测长上下文目标LLM的生成。我们的方法开启了一种新范式，使得同规模甚至更大的LLMs可以作为RAG草稿，同时保持计算效率。为了充分利用更强RAG草稿的潜在优势，我们开发了一种推理时的知识转移动态机制，通过RAG丰富目标分布。在LLaMA-3.1和Qwen2.5模型上的广泛实验表明，RAPID成功整合了两种方法的优势，实现了显著的性能提升（例如，LLaMA-3.1-8B在InfiniteBench上的得分从39.33提升到42.83），并且推理速度提升超过2倍。我们的分析表明，RAPID在超过32K上下文长度的情况下实现了稳健的加速，并在实际应用中展现了更优的生成质量。

> The emergence of long-context large language models (LLMs) offers a promising alternative to traditional retrieval-augmented generation (RAG) for processing extensive documents. However, the computational overhead of long-context inference, particularly in managing key-value (KV) caches, presents significant efficiency challenges. While Speculative Decoding (SD) traditionally accelerates inference using smaller draft models, its effectiveness diminishes substantially in long-context scenarios due to memory-bound KV cache operations. We present Retrieval-Augmented Speculative Decoding (RAPID), which leverages RAG for both accelerating and enhancing generation quality in long-context inference. RAPID introduces the RAG drafter-a draft LLM operating on shortened retrieval contexts-to speculate on the generation of long-context target LLMs. Our approach enables a new paradigm where same-scale or even larger LLMs can serve as RAG drafters while maintaining computational efficiency. To fully leverage the potentially superior capabilities from stronger RAG drafters, we develop an inference-time knowledge transfer dynamic that enriches the target distribution by RAG. Extensive experiments on the LLaMA-3.1 and Qwen2.5 backbones demonstrate that RAPID effectively integrates the strengths of both approaches, achieving significant performance improvements (e.g., from 39.33 to 42.83 on InfiniteBench for LLaMA-3.1-8B) with more than 2x speedups. Our analyses reveal that RAPID achieves robust acceleration beyond 32K context length and demonstrates superior generation quality in real-world applications.

[Arxiv](https://arxiv.org/abs/2502.20330)