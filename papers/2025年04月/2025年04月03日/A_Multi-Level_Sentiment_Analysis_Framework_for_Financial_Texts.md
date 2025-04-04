# 金融文本多层级情感分析框架

发布时间：2025年04月03日

`LLM应用`

> A Multi-Level Sentiment Analysis Framework for Financial Texts

# 摘要

> 现有金融情绪分析方法往往由于单一层面的分析方法以及忽视时间动态，难以捕捉债券市场风险的多面性。为此，我们提出了一种基于预训练语言模型（PLMs）和大型语言模型（LLMs）的多层级情绪分析框架。该框架系统整合了企业特定的微观情绪、行业特定的中观情绪以及考虑时间跨度的情绪平滑，以建模文本影响的延迟性和持续性。我们将其应用于构建的全面中文债券市场语料库（2013-2023，139万条文本），提取了每日综合情绪指数。实证结果显示，纳入情绪分析后，信用利差预测的改进在统计上显著（平均绝对误差MAE降低3.25%，平均绝对百分比误差MAPE降低10.96%），且情绪变化与重大社会风险事件和企业特定危机密切相关。此框架不仅能够更细致地理解不同市场层面的情绪，同时考虑了情绪效应的时间演变。

> Existing financial sentiment analysis methods often fail to capture the multi-faceted nature of risk in bond markets due to their single-level approach and neglect of temporal dynamics. We propose Multi-Level Sentiment Analysis based on pre-trained language models (PLMs) and large language models (LLMs), a novel framework that systematically integrates firm-specific micro-level sentiment, industry-specific meso-level sentiment, and duration-aware smoothing to model the latency and persistence of textual impact. Applying our framework to the comprehensive Chinese bond market corpus constructed by us (2013-2023, 1.39M texts), we extracted a daily composite sentiment index. Empirical results show statistically measurable improvements in credit spread forecasting when incorporating sentiment (3.25% MAE and 10.96% MAPE reduction), with sentiment shifts closely correlating with major social risk events and firm-specific crises. This framework provides a more nuanced understanding of sentiment across different market levels while accounting for the temporal evolution of sentiment effects.

[Arxiv](https://arxiv.org/abs/2504.02429)