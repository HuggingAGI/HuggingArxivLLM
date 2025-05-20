# 神经符号查询编译器

发布时间：2025年05月17日

`RAG` `信息检索` `编译器设计`

> Neuro-Symbolic Query Compiler

# 摘要

> 在检索增强生成（RAG）系统中，精准识别搜索意图仍是一项具有挑战性的目标，尤其是在资源受限和处理具有嵌套结构及依赖关系的复杂查询时。本文提出了一种名为 QCompiler 的神经符号框架，该框架灵感来源于语言语法规则和编译器设计，旨在填补这一研究空白。它从理论上设计了一种简洁而充分的巴科斯-瑙尔范式（BNF）文法【数学公式】，用于形式化表达复杂查询。与以往方法不同，该文法在保持完整性的前提下最大限度地减少了冗余。基于此，QCompiler 包含了一个查询表达式翻译器、一个词法语法解析器和一个递归下降处理器，能够将查询编译为抽象语法树（AST）以供执行。位于叶子节点的子查询的原子性确保了更精确的文档检索和响应生成，从而显著提升了 RAG 系统处理复杂查询的能力。

> Precise recognition of search intent in Retrieval-Augmented Generation (RAG) systems remains a challenging goal, especially under resource constraints and for complex queries with nested structures and dependencies. This paper presents QCompiler, a neuro-symbolic framework inspired by linguistic grammar rules and compiler design, to bridge this gap. It theoretically designs a minimal yet sufficient Backus-Naur Form (BNF) grammar $G[q]$ to formalize complex queries. Unlike previous methods, this grammar maintains completeness while minimizing redundancy. Based on this, QCompiler includes a Query Expression Translator, a Lexical Syntax Parser, and a Recursive Descent Processor to compile queries into Abstract Syntax Trees (ASTs) for execution. The atomicity of the sub-queries in the leaf nodes ensures more precise document retrieval and response generation, significantly improving the RAG system's ability to address complex queries.

[Arxiv](https://arxiv.org/abs/2505.11932)