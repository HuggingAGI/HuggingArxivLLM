# Scalene 中的开源 AI 驱动优化：利用 DeepSeek-R1 和 LLaMA 3.2 提升 Python 性能分析

发布时间：2025年02月14日

`LLM应用` `软件开发` `性能分析`

> Open-Source AI-Powered Optimization in Scalene: Advancing Python Performance Profiling with DeepSeek-R1 and LLaMA 3.2

# 摘要

> Python 的灵活性和易用性是以性能低效为代价的，开发者需要借助性能分析器进行优化。SCALENE 是一款高性能的 CPU、GPU 和内存性能分析器，它在运行时能够提供细致入微的洞察，速度远超传统分析器。最初，SCALENE 集成了 OpenAI 的 API 来生成 AI 驱动的优化建议，但对专有 API 的依赖限制了其可访问性。本研究探讨了在 SCALENE 中使用开源大型语言模型（如 DeepSeek-R1 和 Llama 3.2）生成优化建议的可行性。我们的评估表明，DeepSeek-R1 提供的代码优化与专有模型相当。我们将 DeepSeek-R1 集成到 SCALENE 中，使其能够自动分析性能瓶颈并提出改进建议，从而增强了 SCALENE 的实用性，同时保持了其开源特性。本研究证明，开源 LLM 可以成为 AI 驱动代码优化的可行替代方案，为更易获取且成本更低的性能分析工具铺平了道路。

> Python's flexibility and ease of use come at the cost of performance inefficiencies, requiring developers to rely on profilers to optimize execution. SCALENE, a high-performance CPU, GPU, and memory profiler, provides fine-grained insights into Python applications while running significantly faster than traditional profilers. Originally, SCALENE integrated OpenAI's API to generate AI-powered optimization suggestions, but its reliance on a proprietary API limited accessibility. This study explores the feasibility of using opensource large language models (LLMs), such as DeepSeek-R1 and Llama 3.2, to generate optimization recommendations within SCALENE. Our evaluation reveals that DeepSeek-R1 provides effective code optimizations comparable to proprietary models. We integrate DeepSeek-R1 into SCALENE to automatically analyze performance bottlenecks and suggest improvements, enhancing SCALENE's utility while maintaining its open-source nature. This study demonstrates that open-source LLMs can be viable alternatives for AI-driven code optimization, paving the way for more accessible and cost-effective performance analysis tools.

[Arxiv](https://arxiv.org/abs/2502.10299)