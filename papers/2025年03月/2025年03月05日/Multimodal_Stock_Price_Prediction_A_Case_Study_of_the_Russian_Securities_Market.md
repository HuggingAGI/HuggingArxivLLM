# 多模态股票价格预测：以俄罗斯证券市场为例

发布时间：2025年03月05日

`LLM应用` `股票预测`

> Multimodal Stock Price Prediction: A Case Study of the Russian Securities Market

# 摘要

> 传统资产价格预测主要依赖价格时间序列、交易量、订单簿数据等数值信息，但新闻流在价格形成中扮演重要角色。本文提出结合蜡烛图时间序列和新闻文本的多模态预测方法。研究数据包括176只俄罗斯股票的价格走势和79,555篇俄文财经新闻。文本处理采用RuBERT和Vikhr-Qwen2.5-0.5b-Instruct模型，时间序列和文本特征则通过LSTM网络融合。实验结果显示，相比单一时间序列模型，引入文本模态使预测误差降低了55%。该多模态数据集为金融领域语言模型的优化提供了重要参考。未来研究将探索文本特征的时间窗口、情感分析和时序关系等优化方向。

> Classical asset price forecasting methods primarily rely on numerical data, such as price time series, trading volumes, limit order book data, and technical analysis indicators. However, the news flow plays a significant role in price formation, making the development of multimodal approaches that combine textual and numerical data for improved prediction accuracy highly relevant. This paper addresses the problem of forecasting financial asset prices using the multimodal approach that combines candlestick time series and textual news flow data. A unique dataset was collected for the study, which includes time series for 176 Russian stocks traded on the Moscow Exchange and 79,555 financial news articles in Russian. For processing textual data, pre-trained models RuBERT and Vikhr-Qwen2.5-0.5b-Instruct (a large language model) were used, while time series and vectorized text data were processed using an LSTM recurrent neural network. The experiments compared models based on a single modality (time series only) and two modalities, as well as various methods for aggregating text vector representations. Prediction quality was estimated using two key metrics: Accuracy (direction of price movement prediction: up or down) and Mean Absolute Percentage Error (MAPE), which measures the deviation of the predicted price from the true price. The experiments showed that incorporating textual modality reduced the MAPE value by 55%. The resulting multimodal dataset holds value for the further adaptation of language models in the financial sector. Future research directions include optimizing textual modality parameters, such as the time window, sentiment, and chronological order of news messages.

[Arxiv](https://arxiv.org/abs/2503.08696)