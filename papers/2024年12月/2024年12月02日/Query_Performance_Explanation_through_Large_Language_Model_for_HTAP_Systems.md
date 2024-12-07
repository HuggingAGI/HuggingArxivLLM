# 通过大型语言模型为 HTAP 系统解释查询性能

发布时间：2024年12月02日

`LLM应用` `数据库` `混合引擎系统`

> Query Performance Explanation through Large Language Model for HTAP Systems

# 摘要

> 在 HTAP 系统中，用户常困惑于为何来自某一引擎（OLAP 或 OLTP）的查询计划执行速度远慢于另一引擎。虽然优化器借由 EXPLAIN 函数提供计划细节，但这些解释对非专业人士而言往往过于技术化，且对跨引擎性能差异的见解有限。为此，我们提出一个创新框架，借助大型语言模型（LLMs）来阐释 HTAP 系统中的查询性能。基于检索增强生成（RAG），我们的框架构建了一个知识库，用于存储历史查询执行情况及专家精心策划的解释。为实现相关知识的高效检索，采用轻量级树-CNN 分类器对查询计划进行嵌入。这种增强使得 LLM 能够生成清晰且具有上下文感知的关于引擎间性能差异的解释。我们的方法展现了 LLMs 在混合引擎系统中的潜力，为数据库优化和用户支持的进一步发展铺平了道路。

> In hybrid transactional and analytical processing (HTAP) systems, users often struggle to understand why query plans from one engine (OLAP or OLTP) perform significantly slower than those from another. Although optimizers provide plan details via the EXPLAIN function, these explanations are frequently too technical for non-experts and offer limited insights into performance differences across engines. To address this, we propose a novel framework that leverages large language models (LLMs) to explain query performance in HTAP systems. Built on Retrieval-Augmented Generation (RAG), our framework constructs a knowledge base that stores historical query executions and expert-curated explanations. To enable efficient retrieval of relevant knowledge, query plans are embedded using a lightweight tree-CNN classifier. This augmentation allows the LLM to generate clear, context-aware explanations of performance differences between engines. Our approach demonstrates the potential of LLMs in hybrid engine systems, paving the way for further advancements in database optimization and user support.

[Arxiv](https://arxiv.org/abs/2412.01709)