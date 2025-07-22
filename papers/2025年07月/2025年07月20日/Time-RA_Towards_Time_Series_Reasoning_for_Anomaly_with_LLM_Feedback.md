# Time-RA：基于LLM反馈的时间序列异常推理方法

发布时间：2025年07月20日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于时间序列异常检测任务中，提出了一个新的任务框架，并引入了相关的数据集和基准测试。因此，它属于LLM应用的范畴。` `数据分析`

> Time-RA: Towards Time Series Reasoning for Anomaly with LLM Feedback

# 摘要

> 时间序列异常检测在各个领域都至关重要，但现有方法通常仅限于简单的二元异常分类，缺乏详细分类和解释性推理。针对这一问题，我们提出了一项全新任务——时间序列异常推理（Time-RA），它将传统的时间序列异常检测从判别式任务转变为基于大型语言模型（LLMs）的生成式、推理密集型任务。同时，我们引入了首个针对异常推理的现实世界多模态基准数据集RATs40K，该数据集包含约40,000个样本，覆盖10个现实领域。每个样本包含数值时间序列数据、上下文文本信息和视觉表示，每项均标注有细粒度类别（14种单变量异常和6种多变量异常）以及结构化的解释性推理。我们开发了一个先进的标注框架，利用集成生成标签并通过GPT-4驱动的反馈进行优化，确保准确性和可解释性。对LLMs和多模态LLMs的广泛基准测试展示了当前模型的能力和局限性，突显了监督微调的关键作用。我们的数据集和任务为可解释的时间序列异常检测和推理的显著进步铺平了道路。

> Time series anomaly detection is critical across various domains, yet current approaches often limit analysis to mere binary anomaly classification without detailed categorization or further explanatory reasoning. To address these limitations, we propose a novel task, Time-series Reasoning for Anomaly (Time-RA) that transforms classical time series anomaly detection from a discriminative into a generative, reasoning-intensive task leveraging Large Language Models (LLMs). Also, we introduce the first real-world multimodal benchmark dataset, RATs40K, explicitly annotated for anomaly reasoning, comprising approximately 40,000 samples across 10 real-world domains. Each sample includes numeric time series data, contextual text information, and visual representations, each annotated with fine-grained categories (14 types for univariate anomalies and 6 for multivariate anomalies) and structured explanatory reasoning. We develop a sophisticated annotation framework utilizing ensemble-generated labels refined through GPT-4-driven feedback, ensuring accuracy and interpretability. Extensive benchmarking of LLMs and multimodal LLMs demonstrates the capabilities and limitations of current models, highlighting the critical role of supervised fine-tuning. Our dataset and task pave the way for significant advancements in interpretable time series anomaly detection and reasoning.

[Arxiv](https://arxiv.org/abs/2507.15066)