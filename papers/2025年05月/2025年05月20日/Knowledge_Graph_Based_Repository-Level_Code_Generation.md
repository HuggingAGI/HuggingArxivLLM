# 基于知识图谱的代码仓库级代码生成

发布时间：2025年05月20日

`LLM应用

理由：这篇论文探讨了大型语言模型在代码生成中的应用，并提出了一种基于知识图谱的方法来优化代码搜索和检索，以提升生成质量。这属于LLM在具体任务中的应用，因此归类为LLM应用。` `软件工程` `知识图谱`

> Knowledge Graph Based Repository-Level Code Generation

# 摘要

> 大型语言模型 (LLMs) 的突破性进展彻底改变了代码生成领域，从自然语言查询到代码输出的转变尤为显著。尽管 LLMs 能够生成高质量代码，但它们在上下文准确性方面的表现仍有待提升，特别是在处理动态变化的代码库时。现有代码搜索和检索方法在结果质量和上下文相关性方面往往不够稳健，导致代码生成效果受限。本文提出了一种基于知识图谱的创新方法，旨在优化代码搜索和检索，从而在仓库级别任务中显著提升代码生成质量。该方法通过将代码仓库表示为图结构，有效捕捉结构化和关系信息，从而增强上下文感知的代码生成能力。我们的框架采用混合方法进行代码检索，以提升上下文相关性，跟踪文件间的模块依赖关系，生成更稳健的代码，并确保与现有代码库的无缝衔接。我们在 Evolutionary Code Benchmark (EvoCodeBench) 数据集上对所提方法进行了基准测试，这是一个仓库级别的代码生成基准测试。实验结果表明，我们的方法显著优于传统基线方法。这些发现表明，基于知识图谱的代码生成技术有望推动开发出更加稳健且上下文敏感的编码辅助工具。

> Recent advancements in Large Language Models (LLMs) have transformed code generation from natural language queries. However, despite their extensive knowledge and ability to produce high-quality code, LLMs often struggle with contextual accuracy, particularly in evolving codebases. Current code search and retrieval methods frequently lack robustness in both the quality and contextual relevance of retrieved results, leading to suboptimal code generation. This paper introduces a novel knowledge graph-based approach to improve code search and retrieval leading to better quality of code generation in the context of repository-level tasks. The proposed approach represents code repositories as graphs, capturing structural and relational information for enhanced context-aware code generation. Our framework employs a hybrid approach for code retrieval to improve contextual relevance, track inter-file modular dependencies, generate more robust code and ensure consistency with the existing codebase. We benchmark the proposed approach on the Evolutionary Code Benchmark (EvoCodeBench) dataset, a repository-level code generation benchmark, and demonstrate that our method significantly outperforms the baseline approach. These findings suggest that knowledge graph based code generation could advance robust, context-sensitive coding assistance tools.

[Arxiv](https://arxiv.org/abs/2505.14394)