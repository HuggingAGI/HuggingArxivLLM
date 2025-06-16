# # NSW-EPNews: 一个用于用电量价格预测的新闻增强型基准数据集（结合大语言模型）

发布时间：2025年05月21日

`LLM应用` `能源管理` `能源预测`

> NSW-EPNews: A News-Augmented Benchmark for Electricity Price Forecasting with LLMs

# 摘要

> 电力价格预测是现代能源管理系统的基石，但现有方法往往忽视同期文本信号，过度依赖历史数据。我们推出NSW-EPNews，这是首个联合评估时间序列模型和大型语言模型（LLMs）在真实电力价格预测中表现的基准数据集。该数据集包含澳大利亚新南威尔士州（2015-2024年）的17.5万多条半小时现货价格、每日温度数据，以及精选市场新闻摘要。我们将其定义为48步预测任务，采用多模态输入：传统模型使用滞后价格、向量化新闻和天气特征，而LLMs则利用结构化上下文提示工程。我们的数据集生成了3,600个用于LLMs评估的多模态提示-输出对，采用特定模板。通过全面的基准测试，我们发现传统统计和机器学习模型从新闻特征中获益有限。对于GPT-4和Gemini 1.5 Pro等先进LLMs，虽然性能略有提升，但它们也频繁出现幻觉，如虚构和畸形的价格序列。NSW-EPNews为多模态环境下评估基于事实的数值推理提供了一个严格的测试平台，揭示了当前LLMs能力与高风险能源预测需求之间的显著差距。

> Electricity price forecasting is a critical component of modern energy-management systems, yet existing approaches heavily rely on numerical histories and ignore contemporaneous textual signals. We introduce NSW-EPNews, the first benchmark that jointly evaluates time-series models and large language models (LLMs) on real-world electricity-price prediction. The dataset includes over 175,000 half-hourly spot prices from New South Wales, Australia (2015-2024), daily temperature readings, and curated market-news summaries from WattClarity. We frame the task as 48-step-ahead forecasting, using multimodal input, including lagged prices, vectorized news and weather features for classical models, and prompt-engineered structured contexts for LLMs. Our datasets yields 3.6k multimodal prompt-output pairs for LLM evaluation using specific templates. Through compresive benchmark design, we identify that for traditional statistical and machine learning models, the benefits gain is marginal from news feature. For state-of-the-art LLMs, such as GPT-4o and Gemini 1.5 Pro, we observe modest performance increase while it also produce frequent hallucinations such as fabricated and malformed price sequences. NSW-EPNews provides a rigorous testbed for evaluating grounded numerical reasoning in multimodal settings, and highlights a critical gap between current LLM capabilities and the demands of high-stakes energy forecasting.

[Arxiv](https://arxiv.org/abs/2506.11050)