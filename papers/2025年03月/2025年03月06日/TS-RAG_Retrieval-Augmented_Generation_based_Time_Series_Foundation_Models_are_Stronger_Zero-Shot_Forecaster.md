# # TS-RAG: 基于检索增强生成的时间序列基础模型是更强大的零样本预测器
TS-RAG: 基于检索增强生成的时间序列基础模型展现出更强大的零样本预测能力

发布时间：2025年03月06日

`RAG` `时间序列预测` `预测模型`

> TS-RAG: Retrieval-Augmented Generation based Time Series Foundation Models are Stronger Zero-Shot Forecaster

# 摘要

> 大型语言模型（LLMs）和基础模型（FMs）在时间序列预测任务中得到了广泛应用。然而，尽管通过微调大型语言模型（LLMs）进行预测能够适应特定领域，但在面对多样化的未见数据集时，其泛化能力往往不尽如人意。与此同时，现有的时间序列基础模型（TSFMs）缺乏内在的领域适应机制，且可解释性有限，因此在零样本预测方面表现不佳。针对这些问题，我们提出了TS-RAG，一种基于检索增强生成的时间序列预测框架，旨在提升TSFMs的泛化能力和可解释性。具体而言，TS-RAG利用预训练的时间序列编码器，从专用知识库中检索与给定时间序列查询语义相关的时间序列段，并将其上下文模式融入其中。随后，我们开发了一个基于可学习的专家混合（MoE）增强模块，该模块能够动态融合检索到的时间序列模式与TSFM对输入查询的表示，从而提升预测准确性，而无需进行特定任务的微调。通过在七个公共基准数据集上的全面实证研究，我们发现TS-RAG实现了零样本预测的最先进性能，相较于现有TSFMs在不同领域中提升了高达6.51%的预测精度，并展现出理想的可解释性。

> Recently, Large Language Models (LLMs) and Foundation Models (FMs) have become prevalent for time series forecasting tasks. However, fine-tuning large language models (LLMs) for forecasting enables the adaptation to specific domains but may not generalize well across diverse, unseen datasets. Meanwhile, existing time series foundation models (TSFMs) lack inherent mechanisms for domain adaptation and suffer from limited interpretability, making them suboptimal for zero-shot forecasting. To this end, we present TS-RAG, a retrieval-augmented generation based time series forecasting framework that enhances the generalization capability and interpretability of TSFMs. Specifically, TS-RAG leverages pre-trained time series encoders to retrieve semantically relevant time series segments from a dedicated knowledge database, incorporating contextual patterns for the given time series query. Next, we develop a learnable Mixture-of-Experts (MoE)-based augmentation module, which dynamically fuses retrieved time series patterns with the TSFM's representation of the input query, improving forecasting accuracy without requiring task-specific fine-tuning. Thorough empirical studies on seven public benchmark datasets demonstrate that TS-RAG achieves state-of-the-art zero-shot forecasting performance, outperforming TSFMs by up to 6.51% across diverse domains and showcasing desired interpretability.

[Arxiv](https://arxiv.org/abs/2503.07649)