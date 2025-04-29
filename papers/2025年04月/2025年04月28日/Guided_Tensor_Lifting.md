# # 引导式张量提升方法

发布时间：2025年04月28日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）来改进程序合成和代码提升过程，属于LLM在特定应用领域的实际应用。` `机器学习` `编程语言`

> Guided Tensor Lifting

# 摘要

> 机器学习领域的领域特定语言（DSLs）正在革新机器学习工作负载的速度和效率，因为它们使用户能够轻松访问高性能编译器优化和加速器。然而，要利用这些功能，用户必须首先将其遗留代码从当前使用的语言翻译成新的 DSL。将代码自动提升到这些 DSL 的过程已被 recent works 识别为关键问题，这些 works 提出程序合成作为解决方案。然而，程序合成虽能解决这一问题，但其成本高昂且难以在没有精心设计的启发式规则时扩展应用。本文提出了一种结合枚举式合成方法与大型语言模型的提升方法，该模型用于自动学习程序提升的领域特定启发式方法，以概率文法的形式呈现。尽管我们仅使用了学习到的启发式方法，但我们的方法在该领域超越了现有最先进的工具。

> Domain-specific languages (DSLs) for machine learning are revolutionizing the speed and efficiency of machine learning workloads as they enable users easy access to high-performance compiler optimizations and accelerators. However, to take advantage of these capabilities, a user must first translate their legacy code from the language it is currently written in, into the new DSL. The process of automatically lifting code into these DSLs has been identified by several recent works, which propose program synthesis as a solution. However, synthesis is expensive and struggles to scale without carefully designed and hard-wired heuristics. In this paper, we present an approach for lifting that combines an enumerative synthesis approach with a Large Language Model used to automatically learn the domain-specific heuristics for program lifting, in the form of a probabilistic grammar. Our approach outperforms the state-of-the-art tools in this area, despite only using learned heuristics.

[Arxiv](https://arxiv.org/abs/2504.19705)