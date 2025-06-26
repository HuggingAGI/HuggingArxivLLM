# 追踪错误，构建修复：基于类型状态引导的上下文检索实现仓库级内存错误修复

发布时间：2025年06月23日

`LLM应用` `软件开发` `软件工程`

> Tracing Errors, Constructing Fixes: Repository-Level Memory Error Repair via Typestate-Guided Context Retrieval

# 摘要

> # 摘要  
C编程中的内存相关错误始终是软件开发中的重大挑战，这主要归因于该语言固有的复杂手动内存管理。这些错误常常成为严重漏洞的温床，而修复它们则需要深入理解程序逻辑和C语言的内存模型。自动程序修复（APR）作为一种新兴的研究领域，旨在应对这些挑战。传统的APR方法依赖于专家设计的策略和预先定义的模板，这些方法不仅耗时耗力，还受限于人工规范的有效性。深度学习技术提供了一个有前景的替代方案，能够自动提取修复模式，但它们需要大量的训练数据集，并且常常缺乏可解释性。

本文介绍了LTFix，这是一种全新的方法，利用大型语言模型（LLMs）的潜力来实现自动化的内存错误修复，特别是在涉及多个函数和文件的复杂仓库级错误方面。我们针对基于LLM的内存错误修复中的两个基本挑战：对跨过程内存管理模式的有限理解以及对仓库级分析的上下文窗口限制。我们的方法采用有限类型状态自动机来指导错误传播路径和上下文跟踪，捕捉错误行为的空间（内存状态）和时间（执行历史）维度。这种类型状态引导的上下文检索策略为LLM提供了简洁且语义丰富的信息，与错误内存管理相关，有效解决了LLMs的令牌限制。

> Memory-related errors in C programming continue to pose significant challenges in software development, primarily due to the complexities of manual memory management inherent in the language. These errors frequently serve as vectors for severe vulnerabilities, while their repair requires extensive knowledge of program logic and C's memory model. Automated Program Repair (APR) has emerged as a critical research area to address these challenges. Traditional APR approaches rely on expert-designed strategies and predefined templates, which are labor-intensive and constrained by the effectiveness of manual specifications. Deep learning techniques offer a promising alternative by automatically extracting repair patterns, but they require substantial training datasets and often lack interpretability.
  This paper introduces LTFix, a novel approach that harnesses the potential of Large Language Models (LLMs) for automated memory error repair, especially for complex repository-level errors that span multiple functions and files. We address two fundamental challenges in LLM-based memory error repair: a limited understanding of interprocedural memory management patterns and context window limitations for repository-wide analysis. Our approach utilizes a finite typestate automaton to guide the tracking of error-propagation paths and context trace, capturing both spatial (memory states) and temporal (execution history) dimensions of error behavior. This typestate-guided context retrieval strategy provides the LLM with concise yet semantically rich information relevant to erroneous memory management, effectively addressing the token limitation of LLMs.

[Arxiv](https://arxiv.org/abs/2506.18394)