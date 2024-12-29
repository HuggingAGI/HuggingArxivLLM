# TimeRAG：借助检索增强生成提高 LLM 时间序列预测能力

发布时间：2024年12月21日

`RAG` `时间序列预测` `数据处理`

> TimeRAG: BOOSTING LLM Time Series Forecasting via Retrieval-Augmented Generation

# 摘要

> 虽然大型语言模型（LLMs）的兴起给时间序列预测带来了新契机，然而现有的基于LLM的方案训练量过大，可迁移性也有限。鉴于这些难题，我们推出了TimeRAG，这是一个把检索增强生成（RAG）融入时间序列预测LLM的框架，它从历史序列构建时间序列知识库，从知识库中检索出与通过动态时间规整（DTW）测量的查询序列模式相似的参考序列，并将这些参考序列和预测查询组合成时间序列预测LLM的文本提示。在不同领域的数据集上开展的实验表明，RAG的融入平均让原始模型的预测准确率提高了2.97％。

> Although the rise of large language models (LLMs) has introduced new opportunities for time series forecasting, existing LLM-based solutions require excessive training and exhibit limited transferability. In view of these challenges, we propose TimeRAG, a framework that incorporates Retrieval-Augmented Generation (RAG) into time series forecasting LLMs, which constructs a time series knowledge base from historical sequences, retrieves reference sequences from the knowledge base that exhibit similar patterns to the query sequence measured by Dynamic Time Warping (DTW), and combines these reference sequences and the prediction query as a textual prompt to the time series forecasting LLM. Experiments on datasets from various domains show that the integration of RAG improved the prediction accuracy of the original model by 2.97% on average.

[Arxiv](https://arxiv.org/abs/2412.16643)