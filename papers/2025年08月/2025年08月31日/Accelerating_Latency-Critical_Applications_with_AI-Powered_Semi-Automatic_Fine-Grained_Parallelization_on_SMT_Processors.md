# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Accelerating Latency-Critical Applications with AI-Powered Semi-Automatic Fine-Grained Parallelization on SMT Processors

# 摘要

> <翻译失败>

> Latency-critical applications tend to show low utilization of functional units due to frequent cache misses and mispredictions during speculative execution in high-performance superscalar processors. However, due to significant impact on single-thread performance, Simultaneous Multithreading (SMT) technology is rarely used with heavy threads of latency-critical applications. In this paper, we explore utilization of SMT technology to support fine-grained parallelization of latency-critical applications. Following the advancements in the development of Large Language Models (LLMs), we introduce Aira, an AI-powered Parallelization Adviser. To implement Aira, we extend AI Coding Agent in Cursor IDE with additional tools connected through Model Context Protocol, enabling end-to-end AI Agent for parallelization. Additional connected tools enable LLM-guided hotspot detection, collection of dynamic dependencies with Dynamic Binary Instrumentation, SMT-aware performance simulation to estimate performance gains. We apply Aira with Relic parallel framework for fine-grained task parallelism on SMT cores to parallelize latency-critical benchmarks representing real-world applications used in industry. We show 17% geomean performance gain from parallelization of latency-critical benchmarks using Aira with Relic framework.

[Arxiv](https://arxiv.org/abs/2509.00883)