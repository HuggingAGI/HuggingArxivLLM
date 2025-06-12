# 基于LLM的定性评估：自然语言生成中的自动化错误分析

发布时间：2025年06月10日

`LLM应用

这篇论文探讨了如何将大型语言模型（LLM）应用于评估自然语言生成（NLG）系统，属于LLM的应用层面。它展示了LLM在实际任务中的具体应用，而非理论研究或智能体相关的内容。`

> LLM-as-a-qualitative-judge: automating error analysis in natural language generation

# 摘要

> LLM-as-a-qualitative-judge是一种基于LLM的评估方法，专注于分析和报告自然语言生成（NLG）系统输出中的常见问题类型，从而为开发者提供有价值的改进建议。该方法包含两个主要步骤：开放式的逐实例问题分析，以及使用一种直观的累积算法对发现的问题进行聚类。我们还引入了一种评估策略，并结合了来自12个NLG数据集的约300个实例的问题标注。实验结果显示，该方法在2/3的情况下能够正确识别实例特定的问题，并且能够生成与人工标注者编写的报告相似的错误类型报告。我们的代码和数据已公开发布在https://github.com/tunde-ajayi/llm-as-a-qualitative-judge。

> Prompting large language models (LLMs) to evaluate generated text, known as LLM-as-a-judge, has become a standard evaluation approach in natural language generation (NLG), but is primarily used as a quantitative tool, i.e. with numerical scores as main outputs. In this work, we propose LLM-as-a-qualitative-judge, an LLM-based evaluation approach with the main output being a structured report of common issue types in the NLG system outputs. Our approach is targeted at providing developers with meaningful insights on what improvements can be done to a given NLG system and consists of two main steps, namely open-ended per-instance issue analysis and clustering of the discovered issues using an intuitive cumulative algorithm. We also introduce a strategy for evaluating the proposed approach, coupled with ~300 annotations of issues in instances from 12 NLG datasets. Our results show that LLM-as-a-qualitative-judge correctly recognizes instance-specific issues in 2/3 cases and is capable of producing error type reports resembling the reports composed by human annotators. Our code and data are publicly available at https://github.com/tunde-ajayi/llm-as-a-qualitative-judge.

[Arxiv](https://arxiv.org/abs/2506.09147)