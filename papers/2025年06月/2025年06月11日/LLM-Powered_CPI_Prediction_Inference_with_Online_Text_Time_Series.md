# # 基于大型语言模型的 CPI 预测推理与在线文本时间序列
探索如何利用大型语言模型的强大能力，通过在线文本时间序列实现精准的 CPI 预测推理。

发布时间：2025年06月11日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于消费者价格指数（CPI）的预测，通过整合在线文本数据和时间序列模型，展示了LLMs在经济学中的实际应用。因此，它属于LLM应用类别。` `经济学`

> LLM-Powered CPI Prediction Inference with Online Text Time Series

# 摘要

> # 摘要
消费者价格指数（CPI）预测是经济学中的重要课题，但现有方法多依赖低频调查数据。大型语言模型（LLMs）的突破为利用高频在线文本提升CPI预测提供了新思路。本文提出LLM-CPI方法，整合在线文本时间序列数据。我们从中文社交平台收集高频文本，使用ChatGPT和BERT模型为通胀相关帖子构建标签。通过LDA和BERT提取文本嵌入。开发的联合时间序列框架结合月度CPI与LLM生成的日度代理变量。月度模型采用ARX结构，结合CPI数据、文本嵌入和宏观经济变量；日度模型则基于VARX结构。我们验证了方法的渐近性质并提供两种预测区间构造。仿真与实际数据均验证了LLM-CPI的有效性与优势。

> Forecasting the Consumer Price Index (CPI) is an important yet challenging task in economics, where most existing approaches rely on low-frequency, survey-based data. With the recent advances of large language models (LLMs), there is growing potential to leverage high-frequency online text data for improved CPI prediction, an area still largely unexplored. This paper proposes LLM-CPI, an LLM-based approach for CPI prediction inference incorporating online text time series. We collect a large set of high-frequency online texts from a popularly used Chinese social network site and employ LLMs such as ChatGPT and the trained BERT models to construct continuous inflation labels for posts that are related to inflation. Online text embeddings are extracted via LDA and BERT. We develop a joint time series framework that combines monthly CPI data with LLM-generated daily CPI surrogates. The monthly model employs an ARX structure combining observed CPI data with text embeddings and macroeconomic variables, while the daily model uses a VARX structure built on LLM-generated CPI surrogates and text embeddings. We establish the asymptotic properties of the method and provide two forms of constructed prediction intervals. The finite-sample performance and practical advantages of LLM-CPI are demonstrated through both simulation and real data examples.

[Arxiv](https://arxiv.org/abs/2506.09516)