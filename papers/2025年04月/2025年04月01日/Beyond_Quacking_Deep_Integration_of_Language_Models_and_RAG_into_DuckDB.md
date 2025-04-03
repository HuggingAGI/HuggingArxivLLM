# 不止于鸭声：语言模型与RAG的深度融入DuckDB

发布时间：2025年04月01日

`LLM应用` `数据库管理系统` `知识密集型分析应用`

> Beyond Quacking: Deep Integration of Language Models and RAG into DuckDB

# 摘要

> 知识密集型分析应用通过从结构化表格数据和非结构化、无文本的文档中检索上下文信息，支持更有效的决策制定。大型语言模型（LLMs）的出现使构建这些检索与推理数据管道变得更加容易。然而，高效实现这些管道仍然面临诸多挑战，包括协调异构数据系统、管理数据移动以及处理LLM上下文管理等低级细节。

    为了解决这些挑战，我们推出了FlockMTL：一个深度集成LLM功能和增强检索生成（RAG）的DBMS扩展。FlockMTL支持基于模型的标量和聚合函数，通过元组级映射和约简实现链式预测。受关系模型启发，FlockMTL具有两大核心特性：(i) 基于成本的优化，能够无缝应用批处理和缓存等技术；(ii) 通过创新的SQL DDL抽象（PROMPT和MODEL）实现的资源独立性，这些抽象与TABLE一起作为核心架构对象。FlockMTL不仅简化了知识密集型分析应用的开发，其优化功能还显著降低了实现难度。

> Knowledge-intensive analytical applications retrieve context from both structured tabular data and unstructured, text-free documents for effective decision-making. Large language models (LLMs) have made it significantly easier to prototype such retrieval and reasoning data pipelines. However, implementing these pipelines efficiently still demands significant effort and has several challenges. This often involves orchestrating heterogeneous data systems, managing data movement, and handling low-level implementation details, e.g., LLM context management.
  To address these challenges, we introduce FlockMTL: an extension for DBMSs that deeply integrates LLM capabilities and retrieval-augmented generation (RAG). FlockMTL includes model-driven scalar and aggregate functions, enabling chained predictions through tuple-level mappings and reductions. Drawing inspiration from the relational model, FlockMTL incorporates: (i) cost-based optimizations, which seamlessly apply techniques such as batching and caching; and (ii) resource independence, enabled through novel SQL DDL abstractions: PROMPT and MODEL, introduced as first-class schema objects alongside TABLE. FlockMTL streamlines the development of knowledge-intensive analytical applications, and its optimizations ease the implementation burden.

[Arxiv](https://arxiv.org/abs/2504.01157)