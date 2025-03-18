# # 摘要
基于LLM的数据分析洞察生成方法

发布时间：2025年02月20日

`LLM应用` `数据分析` `数据库`

> An LLM-Based Approach for Insight Generation in Data Analysis

# 摘要

> 从数据库中提取具有洞察力和可操作性的信息是数据分析的关键所在。本文提出了一种基于大型语言模型（LLMs）的自动文本见解生成新方法。给定多表数据库作为输入，我们的方法通过LLMs生成简洁且基于文本的见解，能够反映表格中的有趣模式。我们的框架包含三个核心组件：假设生成器（用于提出与领域相关的疑问）、查询代理（通过生成SQL查询回答问题）和总结模块（将见解转化为文字）。我们采用人工判断与自动化指标相结合的方式，从准确性和主观洞察力两个维度对见解进行评估。实验结果表明，与其它方法相比，我们的方法不仅保持了准确性，还能够生成更具洞察力的见解，这一优势在公共数据库和企业数据库中均得到了验证。

> Generating insightful and actionable information from databases is critical in data analysis. This paper introduces a novel approach using Large Language Models (LLMs) to automatically generate textual insights. Given a multi-table database as input, our method leverages LLMs to produce concise, text-based insights that reflect interesting patterns in the tables. Our framework includes a Hypothesis Generator to formulate domain-relevant questions, a Query Agent to answer such questions by generating SQL queries against a database, and a Summarization module to verbalize the insights. The insights are evaluated for both correctness and subjective insightfulness using a hybrid model of human judgment and automated metrics. Experimental results on public and enterprise databases demonstrate that our approach generates more insightful insights than other approaches while maintaining correctness.

[Arxiv](https://arxiv.org/abs/2503.11664)