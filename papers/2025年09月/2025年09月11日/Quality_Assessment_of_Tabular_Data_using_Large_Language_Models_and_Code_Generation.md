# 基于大型语言模型与代码生成的表格数据质量评估

发布时间：2025年09月11日

`RAG` `基础理论`

> Quality Assessment of Tabular Data using Large Language Models and Code Generation

# 摘要

> 可靠的数据质量是表格数据集下游分析的关键，但基于规则的验证常因效率低、依赖人工干预及计算成本高而受限。为此，我们提出一种三阶段框架，融合统计内联检测与LLM驱动的规则及代码生成能力。在通过传统聚类过滤数据样本后，我们迭代提示LLMs生成语义有效的质量规则，并借助代码生成LLMs合成可执行验证器。为生成可靠的质量规则，我们利用外部知识源与特定领域少样本示例，通过检索增强生成（RAG）技术增强LLMs能力。同时，稳健的防护机制保障规则与代码片段的准确性和一致性。在基准数据集上的大量实验验证了该方法的有效性。

> Reliable data quality is crucial for downstream analysis of tabular datasets, yet rule-based validation often struggles with inefficiency, human intervention, and high computational costs. We present a three-stage framework that combines statistical inliner detection with LLM-driven rule and code generation. After filtering data samples through traditional clustering, we iteratively prompt LLMs to produce semantically valid quality rules and synthesize their executable validators through code-generating LLMs. To generate reliable quality rules, we aid LLMs with retrieval-augmented generation (RAG) by leveraging external knowledge sources and domain-specific few-shot examples. Robust guardrails ensure the accuracy and consistency of both rules and code snippets. Extensive evaluations on benchmark datasets confirm the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.10572)