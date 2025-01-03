# 分层卷积-LSTM与LLM融合模型：全面股票预测的新视角

发布时间：2024年09月30日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLM）与传统的神经网络模型（如Conv-LSTM）结合，用于金融领域的股票预测。LLM在这里被用来处理和分析外部文本数据（如金融新闻、社交媒体等），以增强预测的准确性。因此，这篇论文属于LLM在实际应用中的使用，即LLM应用。` `股市预测`

> A Hierarchical conv-LSTM and LLM Integrated Model for Holistic Stock Forecasting

# 摘要

> 金融领域的股市预测环境复杂多变，受多种数据源影响。传统模型通常使用CNN提取空间特征或LSTM捕捉时间依赖性，但对外部文本数据的整合有限。本文提出了一种新颖的两级Conv-LSTM神经网络，结合LLM，用于全面股票建议。该模型利用Conv-LSTM分析时间序列数据，LLM处理金融新闻、社交媒体和报告中的文本信息。第一级通过卷积层识别历史股票价格和技术指标的局部模式，LSTM层捕捉时间动态。第二级将输出与LLM结合，分析文本数据中的情感和上下文信息，提供市场状况的整体视图。这种组合方法旨在提高预测准确性并提供上下文丰富的股票建议。

> The financial domain presents a complex environment for stock market prediction, characterized by volatile patterns and the influence of multifaceted data sources. Traditional models have leveraged either Convolutional Neural Networks (CNN) for spatial feature extraction or Long Short-Term Memory (LSTM) networks for capturing temporal dependencies, with limited integration of external textual data. This paper proposes a novel Two-Level Conv-LSTM Neural Network integrated with a Large Language Model (LLM) for comprehensive stock advising. The model harnesses the strengths of Conv-LSTM for analyzing time-series data and LLM for processing and understanding textual information from financial news, social media, and reports. In the first level, convolutional layers are employed to identify local patterns in historical stock prices and technical indicators, followed by LSTM layers to capture the temporal dynamics. The second level integrates the output with an LLM that analyzes sentiment and contextual information from textual data, providing a holistic view of market conditions. The combined approach aims to improve prediction accuracy and provide contextually rich stock advising.

[Arxiv](https://arxiv.org/abs/2410.12807)