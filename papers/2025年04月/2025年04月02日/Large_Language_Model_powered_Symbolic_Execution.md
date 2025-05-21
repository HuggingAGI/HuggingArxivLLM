# 基于大型语言模型的符号执行

发布时间：2025年04月02日

`LLM应用` `软件工程` `程序分析`

> Large Language Model powered Symbolic Execution

# 摘要

> 大型语言模型（LLMs）正在逐步取代传统的静态程序分析方法，如符号执行。LLMs无需依赖定理证明器或SMT求解器，可以直接对代码进行推理。然而，LLMs本质上是概率性的，在实际应用中面临着分析准确性和规模方面的重大挑战。为了解决这些问题，通常需要更大规模的LLMs以及更高的令牌限制，而这又要求企业级硬件（如GPU），从而限制了许多用户的使用门槛。

在本文中，我们提出了基于LLM的符号执行方法。该方法通过将程序分析任务分解为更小（更易于处理）的子任务来增强LLM推理能力。其核心思想是利用一种通用的基于代码的表示方式来对路径约束进行泛化，这种方式可以直接被LLM进行推理，而无需转换为另一种表达能力较弱的形式化语言。我们通过实现AutoExe这一基于LLM的符号执行引擎，展示了该方法的可行性。AutoExe具有轻量化和语言无关性的特点，使其成为分析传统方法难以处理的代码的实用工具。实验表明，AutoExe能够显著提升基于LLM的程序分析的准确性和规模，特别是对于可以在消费级硬件上运行的小型LLMs，效果尤为显著。

> Large Language Models (LLMs) have emerged as a promising alternative to traditional static program analysis methods, such as symbolic execution, offering the ability to reason over code directly without relying on theorem provers or SMT solvers. However, LLMs are also inherently probabilistic by nature, and therefore face significant challenges in relation to the accuracy and scale of the analysis in real-world application. Such issues often necessitate the use of larger LLMs with higher token limits, but this requires enterprise-grade hardware (GPUs) and thus limits accessibility for many users.
  In this paper, we propose LLM-based symbolic execution -- a novel approach that enhances LLM inference via a path-based decomposition of the program analysis tasks into smaller (more tractable) sub-tasks. The core idea is to generalize path constraints using a generic code-based representation that the LLM can directly reason over, and without translation into another (less-expressive) formal language. We implement our approach in the form of AutoExe, an LLM-based symbolic execution engine that is lightweight and language-agnostic, making it a practical tool for analyzing code that is challenging for traditional approaches. We show that AutoExe can improve both the accuracy and scale of LLM-based program analysis, especially for smaller LLMs that can run on consumer grade hardware.

[Arxiv](https://arxiv.org/abs/2505.13452)