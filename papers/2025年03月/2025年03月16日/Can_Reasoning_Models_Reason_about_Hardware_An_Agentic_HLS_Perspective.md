# 推理模型能否真正理解硬件？从智能体HLS视角探索

发布时间：2025年03月16日

`LLM应用

摘要中讨论了大型语言模型在硬件设计中的应用，特别是如何通过LLM来优化HLS过程，提升设计效率和质量。这属于将LLM应用于特定领域的范畴，因此归类为LLM应用。` `硬件设计`

> Can Reasoning Models Reason about Hardware? An Agentic HLS Perspective

# 摘要

> 最近，OpenAI 的 o3-mini 和 DeepSeek-R1 等大型语言模型通过链式思维（CoT）实现了推理能力的提升。然而，它们在硬件设计领域的潜力尚未得到充分挖掘，因为硬件设计通常依赖于专家驱动的迭代优化。本文旨在研究推理型 LLM 是否能够应对高级综合（HLS）设计空间探索与优化中的挑战。在 HLS 过程中，工程师需要手动定义 pragma/directive 来平衡性能与资源约束。为此，我们提出了一种基于 LLM 的优化代理框架，该框架能够自动重构代码、插入 pragma，并通过 HLS 工具的反馈以及对整数线性规划（ILP）求解器的访问，识别出最优的设计点。实验部分通过成功率、效率和设计质量（面积/时延）等指标，比较了推理模型与传统 LLM 在基准测试中的表现，并首次揭示了像 DeepSeek-R1 这样强大的开源推理模型生成的 CoT。

> Recent Large Language Models (LLMs) such as OpenAI o3-mini and DeepSeek-R1 use enhanced reasoning through Chain-of-Thought (CoT). Their potential in hardware design, which relies on expert-driven iterative optimization, remains unexplored. This paper investigates whether reasoning LLMs can address challenges in High-Level Synthesis (HLS) design space exploration and optimization. During HLS, engineers manually define pragmas/directives to balance performance and resource constraints. We propose an LLM-based optimization agentic framework that automatically restructures code, inserts pragmas, and identifies optimal design points via feedback from HLs tools and access to integer-linear programming (ILP) solvers. Experiments compare reasoning models against conventional LLMs on benchmarks using success rate, efficiency, and design quality (area/latency) metrics, and provide the first-ever glimpse into the CoTs produced by a powerful open-source reasoning model like DeepSeek-R1.

[Arxiv](https://arxiv.org/abs/2503.12721)