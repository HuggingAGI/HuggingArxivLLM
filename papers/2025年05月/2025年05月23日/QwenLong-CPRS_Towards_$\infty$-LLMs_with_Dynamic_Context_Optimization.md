# QwenLong-CPRS：探索动态上下文优化，迈向无限大语言模型

发布时间：2025年05月23日

`LLM应用

理由：这篇论文主要探讨了如何优化大型语言模型在处理长上下文时的性能，通过引入上下文压缩框架来解决计算开销和性能下降的问题。这属于LLM的应用层面，因为它专注于实际问题的优化和性能提升，而不是理论上的探讨或与其他技术的结合。` `生成式AI`

> QwenLong-CPRS: Towards $\infty$-LLMs with Dynamic Context Optimization

# 摘要

> 本技术报告介绍了 QwenLong-CPRS，一个专为长上下文优化设计的上下文压缩框架，旨在解决大型语言模型 (LLMs) 在预填阶段的高昂计算开销以及长序列处理中的“迷失在中间”性能下降问题。通过创新的动态上下文优化机制，QwenLong-CPRS 实现了基于自然语言指令的多粒度上下文压缩，显著提升了效率和性能。

QwenLong-CPRS 在 Qwen 架构基础上实现了四项关键创新：(1) 自然语言引导的动态优化，(2) 增强边界感知的双向推理层，(3) 配备语言建模头的令牌评价机制，(4) 窗口并行推理。

在涵盖4K至2M单词上下文的五个基准测试中，QwenLong-CPRS 展现了其三重优势：(1) 在准确性和效率上超越 RAG 和稀疏注意力等方法；(2) 与包括 GPT-4o、Gemini2.0-pro 等在内的旗舰 LLM 实现了架构无关的集成，带来 21.59 倍上下文压缩和 19.15 分的平均性能提升；(3) 配套 Qwen2.5-32B-Instruct 使用时，在 Ruler-128K 和 InfiniteBench 测试中分别超出领先专有 LLM 4.85 分和 10.88 分，树立了新的 SOTA 性能标杆。


> This technical report presents QwenLong-CPRS, a context compression framework designed for explicit long-context optimization, addressing prohibitive computation overhead during the prefill stage and the "lost in the middle" performance degradation of large language models (LLMs) during long sequence processing. Implemented through a novel dynamic context optimization mechanism, QwenLong-CPRS enables multi-granularity context compression guided by natural language instructions, achieving both efficiency gains and improved performance.
  Evolved from the Qwen architecture series, QwenLong-CPRS introduces four key innovations: (1) Natural language-guided dynamic optimization, (2) Bidirectional reasoning layers for enhanced boundary awareness, (3) Token critic mechanisms with language modeling heads, and (4) Window-parallel inference.
  Comprehensive evaluations across five benchmarks (4K-2M word contexts) demonstrate QwenLong-CPRS's threefold effectiveness: (1) Consistent superiority over other context management methods like RAG and sparse attention in both accuracy and efficiency. (2) Architecture-agnostic integration with all flagship LLMs, including GPT-4o, Gemini2.0-pro, Claude3.7-sonnet, DeepSeek-v3, and Qwen2.5-max, achieves 21.59$\times$ context compression alongside 19.15-point average performance gains; (3) Deployed with Qwen2.5-32B-Instruct, QwenLong-CPRS surpasses leading proprietary LLMs by 4.85 and 10.88 points on Ruler-128K and InfiniteBench, establishing new SOTA performance.

[Arxiv](https://arxiv.org/abs/2505.18092)