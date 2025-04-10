# NeedleInATable: 探索大型语言模型处理长结构化表格的长上下文能力

发布时间：2025年04月08日

`LLM应用` `数据科学` `数据分析`

> NeedleInATable: Exploring Long-Context Capability of Large Language Models towards Long-Structured Tables

# 摘要

> 处理结构化表格数据，尤其是长表格，对大型语言模型（LLMs）来说是一项基础但具挑战性的任务。然而，现有的长上下文基准主要关注无结构文本，忽视了长而复杂的结构化表格的挑战。为了解决这一问题，我们提出了一个新的任务——NeedleInATable（NIAT），将每个表格单元格视为“针”，要求模型在不同查询下提取目标单元格。评估结果显示，主流 LLMs 在处理复杂表格时表现不佳，常常依赖表面相关性或捷径，显示出其在处理复杂表格数据方面的局限性。为此，我们提出了一种数据合成方法，以提升模型对长表格的理解能力。实验结果表明，我们的合成训练数据显著提升了 LLMs 在 NIAT 任务上的性能，超越了现有的长上下文 LLMs 和长表格代理方法。这项研究不仅推动了对 LLMs 真实长结构化表格理解能力的评估，还为长上下文和表格理解应用的进步铺平了道路。

> Processing structured tabular data, particularly lengthy tables, constitutes a fundamental yet challenging task for large language models (LLMs). However, existing long-context benchmarks primarily focus on unstructured text, neglecting the challenges of long and complex structured tables. To address this gap, we introduce NeedleInATable (NIAT), a novel task that treats each table cell as a "needle" and requires the model to extract the target cell under different queries. Evaluation results of mainstream LLMs on this benchmark show they lack robust long-table comprehension, often relying on superficial correlations or shortcuts for complex table understanding tasks, revealing significant limitations in processing intricate tabular data. To this end, we propose a data synthesis method to enhance models' long-table comprehension capabilities. Experimental results show that our synthesized training data significantly enhances LLMs' performance on the NIAT task, outperforming both long-context LLMs and long-table agent methods. This work advances the evaluation of LLMs' genuine long-structured table comprehension capabilities and paves the way for progress in long-context and table understanding applications.

[Arxiv](https://arxiv.org/abs/2504.06560)