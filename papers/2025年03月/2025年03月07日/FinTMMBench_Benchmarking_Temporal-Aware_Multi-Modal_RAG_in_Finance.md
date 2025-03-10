# FinTMMBench：时间感知的多模态RAG金融领域基准评测

发布时间：2025年03月07日

`RAG` `金融分析`

> FinTMMBench: Benchmarking Temporal-Aware Multi-Modal RAG in Finance

# 摘要

> 金融决策离不开对多样化的数据源进行深入分析，例如财务报表、新闻资讯、股价动态等。本文首次推出FinTMMBench，这是一个专为评估金融领域时间感知型多模态检索增强生成（RAG）系统而设计的综合性基准测试。该基准构建于NASDAQ 100家企业的异源数据之上，具有三大突出优势：

1) 多模态语料库：整合了财务表格、新闻文章、每日股票价格以及技术图表等多种数据形式。

2) 时间感知型问题：每个问题都要求在特定时间段内检索并解析相关数据，时间尺度涵盖日、周、月、季和年。

3) 多样化的金融分析任务：问题类型多达10种，包括信息提取、趋势分析、情感分析和事件检测等。

我们还创新性地提出了一种TMMHybridRAG方法。该方法首先利用大语言模型将表格、视觉和时间序列等多模态数据转换为文本格式，然后在构建图和稠密索引的过程中，将时间信息融入每个节点。虽然该方法在实验中表现出色，但仍存在显著改进空间，这也凸显了我们提出的FinTMMBench所具有的研究挑战性。

> Finance decision-making often relies on in-depth data analysis across various data sources, including financial tables, news articles, stock prices, etc. In this work, we introduce FinTMMBench, the first comprehensive benchmark for evaluating temporal-aware multi-modal Retrieval-Augmented Generation (RAG) systems in finance. Built from heterologous data of NASDAQ 100 companies, FinTMMBench offers three significant advantages. 1) Multi-modal Corpus: It encompasses a hybrid of financial tables, news articles, daily stock prices, and visual technical charts as the corpus. 2) Temporal-aware Questions: Each question requires the retrieval and interpretation of its relevant data over a specific time period, including daily, weekly, monthly, quarterly, and annual periods. 3) Diverse Financial Analysis Tasks: The questions involve 10 different tasks, including information extraction, trend analysis, sentiment analysis and event detection, etc. We further propose a novel TMMHybridRAG method, which first leverages LLMs to convert data from other modalities (e.g., tabular, visual and time-series data) into textual format and then incorporates temporal information in each node when constructing graphs and dense indexes. Its effectiveness has been validated in extensive experiments, but notable gaps remain, highlighting the challenges presented by our FinTMMBench.

[Arxiv](https://arxiv.org/abs/2503.05185)