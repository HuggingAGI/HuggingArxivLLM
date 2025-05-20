# # 神经符号查询编译器

发布时间：2025年05月17日

`RAG` `信息检索` `问答系统`

> Neuro-Symbolic Query Compiler

# 摘要

> 在检索增强生成（RAG）系统中，精准识别搜索意图始终是一个充满挑战的目标，尤其是在资源受限和面对具有嵌套结构与依赖关系的复杂查询时。本文提出了一种名为QCompiler的神经符号框架，该框架灵感源自语言语法规则与编译器设计，旨在解决这一难题。通过理论设计，我们构建了一个简洁而充分的巴科斯-诺尔范式（BNF）语法$G[q]$，用于形式化复杂查询。与传统方法不同，该语法在保持完整性的基础上大幅减少了冗余。基于此语法，QCompiler集成了查询表达式翻译器、词法语法解析器和递归下降处理器，将查询编译为抽象语法树（AST）以实现高效执行。得益于叶子节点中子查询的原子性，QCompiler显著提升了文档检索和响应生成的精准度，从而大幅增强了RAG系统处理复杂查询的能力。

> Precise recognition of search intent in Retrieval-Augmented Generation (RAG) systems remains a challenging goal, especially under resource constraints and for complex queries with nested structures and dependencies. This paper presents QCompiler, a neuro-symbolic framework inspired by linguistic grammar rules and compiler design, to bridge this gap. It theoretically designs a minimal yet sufficient Backus-Naur Form (BNF) grammar $G[q]$ to formalize complex queries. Unlike previous methods, this grammar maintains completeness while minimizing redundancy. Based on this, QCompiler includes a Query Expression Translator, a Lexical Syntax Parser, and a Recursive Descent Processor to compile queries into Abstract Syntax Trees (ASTs) for execution. The atomicity of the sub-queries in the leaf nodes ensures more precise document retrieval and response generation, significantly improving the RAG system's ability to address complex queries.

[Arxiv](https://arxiv.org/abs/2505.11932)