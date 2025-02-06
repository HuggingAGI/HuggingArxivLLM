# 检测LLMs与知识图谱间元语言分歧的基准

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要探讨了LLMs（大型语言模型）在知识图谱构建中的事实提取任务中的应用，特别是LLMs和KGs（知识图谱）之间的元语言分歧问题。论文提出了一个基准来评估这种分歧，并讨论了其对知识图谱工程实践的影响。因此，这篇论文属于LLM应用的范畴。` `知识图谱`

> A Benchmark for the Detection of Metalinguistic Disagreements between LLMs and Knowledge Graphs

# 摘要

> 在评估LLMs用于支持知识图谱构建的事实提取等任务时，通常使用基于KG的基准来计算准确性指标。这些评估假设错误代表事实分歧。然而，人类对话中常出现元语言分歧，即代理人在事实本身无分歧，但在表达这些事实的语言意义上存在差异。鉴于LLMs在自然语言处理和生成中的复杂性，我们提出疑问：LLMs和KGs之间是否存在元语言分歧？基于T-REx知识对齐数据集的调查，我们假设LLMs和KGs之间确实存在元语言分歧，这可能对知识图谱工程实践具有潜在意义。我们提出了一个基准，用于评估LLMs和KGs之间事实和元语言分歧的检测，其初步概念验证已在Github上提供。

> Evaluating large language models (LLMs) for tasks like fact extraction in support of knowledge graph construction frequently involves computing accuracy metrics using a ground truth benchmark based on a knowledge graph (KG). These evaluations assume that errors represent factual disagreements. However, human discourse frequently features metalinguistic disagreement, where agents differ not on facts but on the meaning of the language used to express them. Given the complexity of natural language processing and generation using LLMs, we ask: do metalinguistic disagreements occur between LLMs and KGs? Based on an investigation using the T-REx knowledge alignment dataset, we hypothesize that metalinguistic disagreement does in fact occur between LLMs and KGs, with potential relevance for the practice of knowledge graph engineering. We propose a benchmark for evaluating the detection of factual and metalinguistic disagreements between LLMs and KGs. An initial proof of concept of such a benchmark is available on Github.

[Arxiv](https://arxiv.org/abs/2502.02896)