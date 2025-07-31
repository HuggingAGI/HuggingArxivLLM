# 基于大型语言模型的知识图谱修复系统化评估

发布时间：2025年07月30日

`LLM应用

理由：这篇论文探讨了大型语言模型在知识图谱修复中的应用，特别是通过评估框架和提示策略来优化修复效果，属于将LLM应用于具体任务的范畴。` `知识图谱`

> Systematic Evaluation of Knowledge Graph Repair with Large Language Models

# 摘要

> 我们提出了一种系统性方法，用于评估知识图谱修复在形状约束语言（SHACL）定义的约束违规方面的质量。现有评估方法依赖于特定的测试数据集，这限制了在更广泛场景下对修复系统的深入分析。我们的方法通过引入一种称为违规诱导操作（VIOs）的新机制，系统地生成违规行为，从而弥补了这一研究空白。我们采用提出的评估框架，对基于大型语言模型构建的多种修复系统进行了全面评估，并深入分析了不同提示策略对系统性能的影响。实验结果表明，同时包含相关违反的 SHACL 约束和知识图谱关键上下文信息的简洁提示策略，能够取得最佳的修复效果。

> We present a systematic approach for evaluating the quality of knowledge graph repairs with respect to constraint violations defined in shapes constraint language (SHACL). Current evaluation methods rely on \emph{ad hoc} datasets, which limits the rigorous analysis of repair systems in more general settings. Our method addresses this gap by systematically generating violations using a novel mechanism, termed violation-inducing operations (VIOs). We use the proposed evaluation framework to assess a range of repair systems which we build using large language models. We analyze the performance of these systems across different prompting strategies. Results indicate that concise prompts containing both the relevant violated SHACL constraints and key contextual information from the knowledge graph yield the best performance.

[Arxiv](https://arxiv.org/abs/2507.22419)