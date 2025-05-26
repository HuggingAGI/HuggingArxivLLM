# 用语言锻造时间序列：大型语言模型驱动的合成数据生成新方法

发布时间：2025年05月21日

`LLM应用

摘要中提到SDForger是一个基于LLM生成多变量时间序列的框架，属于LLM的应用场景，因此归类为LLM应用。` `时间序列分析` `数据生成`

> Forging Time Series with Language: A Large Language Model Approach to Synthetic Data Generation

# 摘要

> SDForger 是一个灵活高效且基于 LLM 生成高质量多变量时间序列的框架。SDForger 基于紧凑的数据表示，能够从少量样本生成合成时间序列，并支持对任意自回归 LLM 进行低计算量的微调。具体来说，该框架通过将单变量和多变量信号转换为表格嵌入，再将其编码为文本并用于微调 LLM。在推理过程中，新的文本嵌入会被采样并解码为保留原始数据统计特性和时间动态的合成时间序列。在多样化的数据集上，SDForger 在多种场景下都优于现有的生成模型，无论是基于相似性的评估还是下游预测任务。通过在生成过程中启用文本条件控制，SDForger 为多模态建模和时间序列与文本信息的无缝集成铺平了道路。SDForger 的源代码即将开源。

> SDForger is a flexible and efficient framework for generating high-quality multivariate time series using LLMs. Leveraging a compact data representation, SDForger provides synthetic time series generation from a few samples and low-computation fine-tuning of any autoregressive LLM. Specifically, the framework transforms univariate and multivariate signals into tabular embeddings, which are then encoded into text and used to fine-tune the LLM. At inference, new textual embeddings are sampled and decoded into synthetic time series that retain the original data's statistical properties and temporal dynamics. Across a diverse range of datasets, SDForger outperforms existing generative models in many scenarios, both in similarity-based evaluations and downstream forecasting tasks. By enabling textual conditioning in the generation process, SDForger paves the way for multimodal modeling and the streamlined integration of time series with textual information. SDForger source code will be open-sourced soon.

[Arxiv](https://arxiv.org/abs/2505.17103)