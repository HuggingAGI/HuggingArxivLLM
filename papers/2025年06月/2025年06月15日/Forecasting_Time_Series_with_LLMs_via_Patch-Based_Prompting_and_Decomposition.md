# 基于块提示与分解的LLMs时间序列预测方法

发布时间：2025年06月15日

`LLM应用` `数据科学` `时间序列分析`

> Forecasting Time Series with LLMs via Patch-Based Prompting and Decomposition

# 摘要

> 大型语言模型（LLMs）的最新进展为时间序列分析带来了新的可能性，但以往研究往往需要大量微调或忽视了时间序列间的关联。我们提出了一种简单灵活的基于提示的策略，使LLMs无需复杂架构或大量训练即可完成时间序列预测。通过时间序列分解、基于补丁的标记化和相似性邻域增强等方法，我们在保持简单性的同时显著提升了预测质量。为此，我们开发了PatchInstruct方法，使LLMs能够实现精准有效的预测。

> Recent advances in Large Language Models (LLMs) have demonstrated new possibilities for accurate and efficient time series analysis, but prior work often required heavy fine-tuning and/or ignored inter-series correlations. In this work, we explore simple and flexible prompt-based strategies that enable LLMs to perform time series forecasting without extensive retraining or the use of a complex external architecture. Through the exploration of specialized prompting methods that leverage time series decomposition, patch-based tokenization, and similarity-based neighbor augmentation, we find that it is possible to enhance LLM forecasting quality while maintaining simplicity and requiring minimal preprocessing of data. To this end, we propose our own method, PatchInstruct, which enables LLMs to make precise and effective predictions.

[Arxiv](https://arxiv.org/abs/2506.12953)