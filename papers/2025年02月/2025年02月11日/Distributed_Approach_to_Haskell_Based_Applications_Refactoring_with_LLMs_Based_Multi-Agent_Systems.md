# 基于大语言模型的多智能体系统驱动的 Haskell 应用程序分布式重构方法

发布时间：2025年02月11日

`Agent` `软件工程`

> Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems

# 摘要

> 我们提出了一种基于大型语言模型（LLMs）的多智能体系统，用于自动重构Haskell代码库。该系统由多个专用智能体组成，分别负责上下文分析、重构、验证和测试等任务。通过循环复杂度、运行时间和内存分配等指标评估重构效果。实验结果表明，该系统显著提升了代码质量：循环复杂度分别降低了13.64%和47.06%，内存分配效率提高了4.17%和41.73%，运行效率更是提升了高达50%。这些数据充分证明了该系统在优化Haskell函数范式的同时，能够保持代码的正确性和可扩展性。该方法通过分布式和模块化的多智能体系统，实现了精确的任务执行和智能体间的高效协作，成功解决了功能编程语言重构中的诸多挑战。

> We present a large language models (LLMs) based multi-agent system to automate the refactoring of Haskell codebases. The multi-agent system consists of specialized agents performing tasks such as context analysis, refactoring, validation, and testing. Refactoring improvements are using metrics such as cyclomatic complexity, run-time, and memory allocation. Experimental evaluations conducted on Haskell codebases demonstrate improvements in code quality. Cyclomatic complexity was reduced by 13.64% and 47.06% in the respective codebases. Memory allocation improved by 4.17% and 41.73%, while runtime efficiency increased by up to 50%. These metrics highlight the systems ability to optimize Haskells functional paradigms while maintaining correctness and scalability. Results show reductions in complexity and performance enhancements across codebases. The integration of LLMs based multi-agent system enables precise task execution and inter-agent collaboration, addressing the challenges of refactoring in functional programming. This approach aims to address the challenges of refactoring functional programming languages through distributed and modular systems.

[Arxiv](https://arxiv.org/abs/2502.07928)