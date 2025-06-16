# 没有通用提示：通过自适应提示统一推理，专为时间表格推理设计

发布时间：2025年06月12日

`LLM应用` `数据处理` `人工智能`

> No Universal Prompt: Unifying Reasoning through Adaptive Prompting for Temporal Table Reasoning

# 摘要

> 时间表格推理是大型语言模型（LLMs）面临的关键挑战，需要有效的提示技术来提取相关见解。尽管存在多种提示方法，但它们对表格推理的影响仍然 largely 未被探索。此外，这些模型在不同表格和上下文结构下的表现差异巨大，使得难以确定最佳方法。本研究探讨了多种提示技术在不同表格类型中的应用，以确定不同场景下的最优方法。我们发现，性能因实体类型、表格结构、额外上下文需求以及问题复杂性而异，且没有单一方法能始终优于其他方法。为应对这些挑战，我们引入了SEAR，一种基于人类推理的自适应提示框架，能够根据上下文特征动态调整，并结合结构化推理。我们的结果显示，与其它基线提示技术相比，SEAR在所有表格类型中均表现出色。此外，我们还研究了表格结构重构的影响，发现统一表示能提升模型推理能力。

> Temporal Table Reasoning is a critical challenge for Large Language Models (LLMs), requiring effective prompting techniques to extract relevant insights. Despite existence of multiple prompting methods, their impact on table reasoning remains largely unexplored. Furthermore, the performance of these models varies drastically across different table and context structures, making it difficult to determine an optimal approach. This work investigates multiple prompting technique across diverse table types to determine optimal approaches for different scenarios. We find that performance varies based on entity type, table structure, requirement of additional context and question complexity, with NO single method consistently outperforming others. To mitigate these challenges, we introduce SEAR, an adaptive prompting framework inspired by human reasoning that dynamically adjusts based on context characteristics and integrates a structured reasoning. Our results demonstrate that SEAR achieves superior performance across all table types compared to other baseline prompting techniques. Additionally, we explore the impact of table structure refactoring, finding that a unified representation enhances model's reasoning.

[Arxiv](https://arxiv.org/abs/2506.11246)