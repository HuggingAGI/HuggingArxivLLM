# LLM驱动的数据生成与用于评估航空MRO文本到SQL任务的新型软指标

发布时间：2025年06月11日

`LLM应用` `航空维修` `数据库管理`

> LLM-Driven Data Generation and a Novel Soft Metric for Evaluating Text-to-SQL in Aviation MRO

# 摘要

> 大型语言模型（LLMs）在文本到SQL任务中的应用为数据民主化带来了巨大潜力，尤其是在航空维修、修理与运营（MRO）等关键行业。然而，该领域的发展受到两大挑战的制约：传统评估指标如执行准确性过于 rigid，仅能提供粗略的二元反馈，以及领域特定评估数据集的稀缺性。本文针对这些挑战展开研究。我们提出了一种基于F1分数的“soft”新指标，能够量化生成SQL与真实SQL结果之间的信息重叠，从而实现更细致的评估。为解决数据稀缺性问题，我们开发了一种基于LLM的流水线，能够从数据库架构中合成现实的问答-SQL配对。通过在真实MRO数据库上的实证评估，我们展示了这些创新的成效。实验结果表明，相较于严格的准确性评估，我们的soft指标能提供更具洞察力的性能分析，而数据生成技术在创建领域特定基准方面也表现出色。这些贡献共同为在专业环境中评估和推进文本到SQL系统提供了一个强大的框架。

> The application of Large Language Models (LLMs) to text-to-SQL tasks promises to democratize data access, particularly in critical industries like aviation Maintenance, Repair, and Operation (MRO). However, progress is hindered by two key challenges: the rigidity of conventional evaluation metrics such as execution accuracy, which offer coarse, binary feedback, and the scarcity of domain-specific evaluation datasets. This paper addresses these gaps. To enable more nuanced assessment, we introduce a novel F1-score-based 'soft' metric that quantifies the informational overlap between generated and ground-truth SQL results. To address data scarcity, we propose an LLM-driven pipeline that synthesizes realistic question-SQL pairs from database schemas. We demonstrate our contributions through an empirical evaluation on an authentic MRO database. Our experiments show that the proposed soft metric provides more insightful performance analysis than strict accuracy, and our data generation technique is effective in creating a domain-specific benchmark. Together, these contributions offer a robust framework for evaluating and advancing text-to-SQL systems in specialized environments.

[Arxiv](https://arxiv.org/abs/2506.13785)