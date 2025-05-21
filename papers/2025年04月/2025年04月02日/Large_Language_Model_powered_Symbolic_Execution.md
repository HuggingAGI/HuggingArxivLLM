# 大型语言模型驱动的符号执行：探索AI与形式化方法的完美结合

发布时间：2025年04月02日

`LLM应用

摘要讨论了大型语言模型在程序分析中的应用，特别是符号执行方法，属于LLM的应用层面。论文提出了一种新的方法，优化了LLM在特定任务中的性能，因此属于LLM应用类别。

LLM应用` `程序分析`

> Large Language Model powered Symbolic Execution

# 摘要

> 大型语言模型 (LLMs) 为传统静态程序分析方法（如符号执行）提供了一种有前途的替代方案，能够直接对代码进行推理，无需依赖定理证明器或 SMT 求解器。然而，LLMs 本质上是概率性的，在实际应用中面临着分析准确性和规模方面的挑战。这些问题通常需要更大规模的 LLMs 和企业级硬件（GPU），从而限制了其普及。
    本文提出了一种基于 LLM 的符号执行方法，通过将程序分析任务分解为更小、更易于处理的子任务来增强 LLM 推理。核心思想是利用一种通用的基于代码的表示形式来推广路径约束，直接由 LLM 进行推理，无需转换为其他表达能力较弱的正式语言。我们通过 AutoExe 实现了这一方法，这是一种轻量级且与语言无关的基于 LLM 的符号执行引擎，成为分析传统方法难以处理的代码的实用工具。实验表明，AutoExe 能够显著提高基于 LLM 的程序分析的准确性和规模，特别是对于能够运行在消费级硬件上的较小规模的 LLMs。
    

> Large Language Models (LLMs) have emerged as a promising alternative to traditional static program analysis methods, such as symbolic execution, offering the ability to reason over code directly without relying on theorem provers or SMT solvers. However, LLMs are also inherently probabilistic by nature, and therefore face significant challenges in relation to the accuracy and scale of the analysis in real-world application. Such issues often necessitate the use of larger LLMs with higher token limits, but this requires enterprise-grade hardware (GPUs) and thus limits accessibility for many users.
  In this paper, we propose LLM-based symbolic execution -- a novel approach that enhances LLM inference via a path-based decomposition of the program analysis tasks into smaller (more tractable) sub-tasks. The core idea is to generalize path constraints using a generic code-based representation that the LLM can directly reason over, and without translation into another (less-expressive) formal language. We implement our approach in the form of AutoExe, an LLM-based symbolic execution engine that is lightweight and language-agnostic, making it a practical tool for analyzing code that is challenging for traditional approaches. We show that AutoExe can improve both the accuracy and scale of LLM-based program analysis, especially for smaller LLMs that can run on consumer grade hardware.

[Arxiv](https://arxiv.org/abs/2505.13452)