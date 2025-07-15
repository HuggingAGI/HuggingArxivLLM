# 大型语言模型与时间序列变换器融合的时间序列预测

发布时间：2025年07月14日

`LLM应用` `时间序列预测`

> Fusing Large Language Models with Temporal Transformers for Time Series Forecasting

# 摘要

> 大型语言模型（LLMs）近期展现出的强大能力使其被应用于时间序列预测（TSF）任务，即基于历史时间序列数据预测未来数值。现有方法通过提示或微调策略，将文本知识迁移至时间序列预测，但LLMs擅长处理离散文本标记和语义模式，而非连续数值时间序列。这种差距导致LLMs的表现通常劣于直接训练的普通Transformer模型，而普通Transformer模型又难以捕捉高级语义模式。本文提出了一种创新的Transformer架构，结合LLMs和普通Transformer模型，将语义表示与时间信息融合，获得包含历史动态和语义变化的混合表示，从而实现更精准的预测。实验结果验证了该方法的有效性。

> Recently, large language models (LLMs) have demonstrated powerful capabilities in performing various tasks and thus are applied by recent studies to time series forecasting (TSF) tasks, which predict future values with the given historical time series. Existing LLM-based approaches transfer knowledge learned from text data to time series prediction using prompting or fine-tuning strategies. However, LLMs are proficient at reasoning over discrete tokens and semantic patterns but are not initially designed to model continuous numerical time series data. The gaps between text and time series data lead LLMs to achieve inferior performance to a vanilla Transformer model that is directly trained on TSF data. However, the vanilla Transformers often struggle to learn high-level semantic patterns. In this paper, we design a novel Transformer-based architecture that complementarily leverages LLMs and vanilla Transformers, so as to integrate the high-level semantic representations learned by LLMs into the temporal information encoded by time series Transformers, where a hybrid representation is obtained by fusing the representations from the LLM and the Transformer. The resulting fused representation contains both historical temporal dynamics and semantic variation patterns, allowing our model to predict more accurate future values. Experiments on benchmark datasets demonstrate the effectiveness of the proposed approach.

[Arxiv](https://arxiv.org/abs/2507.10098)