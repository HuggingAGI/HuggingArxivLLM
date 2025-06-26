# # 追踪错误，构建修复：基于类型状态引导的上下文检索实现仓库级内存错误修复

发布时间：2025年06月23日

`LLM应用` `软件开发` `内存管理`

> Tracing Errors, Constructing Fixes: Repository-Level Memory Error Repair via Typestate-Guided Context Retrieval

# 摘要

> C语言中的内存错误仍然是软件开发中的难题，其根源在于手动内存管理的复杂性。这些错误不仅是严重漏洞的温床，修复它们还需要深入理解程序逻辑和C语言的内存模型。自动化程序修复（APR）作为新兴研究领域，正在成为解决这些问题的关键。

传统APR方法依赖专家设计的策略和模板，这不仅耗时，还受限于人工规范的效果。深度学习技术提供了一种新思路，通过自动提取修复模式，但需要大量数据且通常缺乏可解释性。

本文提出LTFix，一种利用大型语言模型（LLMs）进行自动化内存修复的新方法，尤其擅长处理跨越多函数和文件的复杂仓库级错误。我们解决了基于LLM的内存修复中的两大难题：跨过程内存管理模式的理解不足以及仓库级分析的上下文限制。我们的方法通过有限类型状态自动机引导错误传播路径和上下文追踪，捕捉错误行为的空间（内存状态）和时间（执行历史）维度。这种类型状态引导的上下文检索策略为LLM提供了简洁而语义丰富的信息，有效解决了LLMs的令牌限制问题。

> Memory-related errors in C programming continue to pose significant challenges in software development, primarily due to the complexities of manual memory management inherent in the language. These errors frequently serve as vectors for severe vulnerabilities, while their repair requires extensive knowledge of program logic and C's memory model. Automated Program Repair (APR) has emerged as a critical research area to address these challenges. Traditional APR approaches rely on expert-designed strategies and predefined templates, which are labor-intensive and constrained by the effectiveness of manual specifications. Deep learning techniques offer a promising alternative by automatically extracting repair patterns, but they require substantial training datasets and often lack interpretability.
  This paper introduces LTFix, a novel approach that harnesses the potential of Large Language Models (LLMs) for automated memory error repair, especially for complex repository-level errors that span multiple functions and files. We address two fundamental challenges in LLM-based memory error repair: a limited understanding of interprocedural memory management patterns and context window limitations for repository-wide analysis. Our approach utilizes a finite typestate automaton to guide the tracking of error-propagation paths and context trace, capturing both spatial (memory states) and temporal (execution history) dimensions of error behavior. This typestate-guided context retrieval strategy provides the LLM with concise yet semantically rich information relevant to erroneous memory management, effectively addressing the token limitation of LLMs.

[Arxiv](https://arxiv.org/abs/2506.18394)