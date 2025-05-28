# RelationalFactQA：评估大型语言模型表格事实检索能力的基准

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了大型语言模型在生成结构化多记录表格输出方面的应用能力，提出了一个新的基准测试RelationalFactQA，并分析了模型在不同查询复杂度和输出规模下的表现。这属于对大型语言模型实际应用能力的评估和研究，因此归类为LLM应用。` `大型语言模型` `结构化知识`

> RelationalFactQA: A Benchmark for Evaluating Tabular Fact Retrieval from Large Language Models

# 摘要

> 大型语言模型（LLMs）在事实性方面面临持续挑战。现有基准主要评估简短事实答案，却忽视了生成结构化多记录表格输出的能力，这些输出基于参数化知识。我们发现，关系事实检索远比孤立点式查询困难，即使模型已知单个事实，仍会因输出维度（如属性或记录数）而暴露出独特失败模式。为系统评估这一未充分探索的能力，我们推出RelationalFactQA——全新基准，包含多样化自然语言问题（配对SQL）及黄金标准表格答案，专为评估结构化知识检索而设计。RelationalFactQA支持跨不同查询复杂度、输出规模及数据特性进行分析。实验显示，即使是最先进的LLMs在生成关系输出时也面临重大挑战，事实准确性不超过25%，且输出维度增加时性能显著下降。这些发现凸显了当前LLMs在合成结构化事实知识方面的局限性，并确立了RelationalFactQA作为衡量LLM事实性未来进展的关键资源。

> Factuality in Large Language Models (LLMs) is a persistent challenge. Current benchmarks often assess short factual answers, overlooking the critical ability to generate structured, multi-record tabular outputs from parametric knowledge. We demonstrate that this relational fact retrieval is substantially more difficult than isolated point-wise queries, even when individual facts are known to the model, exposing distinct failure modes sensitive to output dimensionality (e.g., number of attributes or records). To systematically evaluate this under-explored capability, we introduce RelationalFactQA, a new benchmark featuring diverse natural language questions (paired with SQL) and gold-standard tabular answers, specifically designed to assess knowledge retrieval in a structured format. RelationalFactQA enables analysis across varying query complexities, output sizes, and data characteristics. Our experiments reveal that even state-of-the-art LLMs struggle significantly, not exceeding 25% factual accuracy in generating relational outputs, with performance notably degrading as output dimensionality increases. These findings underscore critical limitations in current LLMs' ability to synthesize structured factual knowledge and establish RelationalFactQA as a crucial resource for measuring future progress in LLM factuality.

[Arxiv](https://arxiv.org/abs/2505.21409)