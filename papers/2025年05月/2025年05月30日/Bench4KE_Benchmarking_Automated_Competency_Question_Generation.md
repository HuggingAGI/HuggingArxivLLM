# Bench4KE：自动化能力问题生成基准测试

发布时间：2025年05月30日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在知识工程自动化中的应用，特别是自动生成能力问题（CQs）的工具。论文还提出了一个基准测试系统（Bench4KE）来评估这些工具的性能，属于LLM的具体应用和工具开发。` `知识工程` `基准测试系统`

> Bench4KE: Benchmarking Automated Competency Question Generation

# 摘要

> 大型语言模型（LLMs）的出现为知识工程（KE）自动化研究注入了新活力，这一趋势已在近期基于LLMs的工具开发中显现，这些工具能够自动生成能力问题（CQs）。然而，这些工具的评估缺乏统一标准，这不仅削弱了研究方法的严谨性，也阻碍了结果的复现和比较。为了解决这一问题，我们推出了Bench4KE——一个基于API的可扩展知识工程自动化基准测试系统。""其首个版本专注于评估自动生成能力问题（CQs）的工具。CQs是由知识工程师用来定义本体功能需求的自然语言问题。Bench4KE提供了一个精心策划的黄金标准，其中包括来自四个真实世界本体项目的能力问题数据集。它采用了一系列相似性指标来评估生成的能力问题的质量。我们对四个近期的能力问题生成系统进行了比较分析，这些系统基于LLMs，为未来研究奠定了基准。Bench4KE还设计成能够支持其他知识工程自动化任务，如SPARQL查询生成、本体测试和起草。代码和数据集在Apache 2.0许可下公开可用。

> The availability of Large Language Models (LLMs) presents a unique opportunity to reinvigorate research on Knowledge Engineering (KE) automation, a trend already evident in recent efforts developing LLM-based methods and tools for the automatic generation of Competency Questions (CQs). However, the evaluation of these tools lacks standardisation. This undermines the methodological rigour and hinders the replication and comparison of results. To address this gap, we introduce Bench4KE, an extensible API-based benchmarking system for KE automation. Its first release focuses on evaluating tools that generate CQs automatically. CQs are natural language questions used by ontology engineers to define the functional requirements of an ontology. Bench4KE provides a curated gold standard consisting of CQ datasets from four real-world ontology projects. It uses a suite of similarity metrics to assess the quality of the CQs generated. We present a comparative analysis of four recent CQ generation systems, which are based on LLMs, establishing a baseline for future research. Bench4KE is also designed to accommodate additional KE automation tasks, such as SPARQL query generation, ontology testing and drafting. Code and datasets are publicly available under the Apache 2.0 license.

[Arxiv](https://arxiv.org/abs/2505.24554)