# # 潘多拉：代码驱动的大型语言模型智能体，实现多样化结构化知识的统一推理

发布时间：2025年04月17日

`LLM应用` `知识图谱`

> Pandora: A Code-Driven Large Language Model Agent for Unified Reasoning Across Diverse Structured Knowledge

# 摘要

> 统一结构化知识推理（USKR）的目标是通过统一的方式，利用结构化数据（如表格、数据库和知识图谱）来回答自然语言问题。现有的USKR方法通常依赖于任务特定的策略或自定义表示，这些方法在跨任务知识迁移和与LLMs预训练先验的对齐方面表现不足，从而限制了其性能。本文提出了一种名为	extsc{Pandora}的新框架，该框架基于	extsc{Python}的	extsc{Pandas} API构建统一的知识表示，使其与LLM预训练相匹配。它利用LLM为每个问题生成推理步骤和可执行代码。通过从涵盖多种SKR任务的训练样例库中提取示例，	extsc{Pandora}实现了有效的知识迁移。在四个基准测试中，涉及三种SKR任务的大量实验表明，	extsc{Pandora}超越了现有的统一框架，并且在与任务特定方法的竞争中表现优异。

> Unified Structured Knowledge Reasoning (USKR) aims to answer natural language questions (NLQs) by using structured sources such as tables, databases, and knowledge graphs in a unified way. Existing USKR methods either rely on employing task-specific strategies or custom-defined representations, which struggle to leverage the knowledge transfer between different SKR tasks or align with the prior of LLMs, thereby limiting their performance. This paper proposes a novel USKR framework named \textsc{Pandora}, which takes advantage of \textsc{Python}'s \textsc{Pandas} API to construct a unified knowledge representation for alignment with LLM pre-training. It employs an LLM to generate textual reasoning steps and executable Python code for each question. Demonstrations are drawn from a memory of training examples that cover various SKR tasks, facilitating knowledge transfer. Extensive experiments on four benchmarks involving three SKR tasks demonstrate that \textsc{Pandora} outperforms existing unified frameworks and competes effectively with task-specific methods.

[Arxiv](https://arxiv.org/abs/2504.12734)