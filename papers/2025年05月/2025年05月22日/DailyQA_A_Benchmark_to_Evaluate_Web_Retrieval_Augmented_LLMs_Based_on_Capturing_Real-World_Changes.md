# DailyQA：通过捕捉真实世界变化评估网络检索增强型LLM的基准测试

发布时间：2025年05月22日

`RAG` `人工智能` `信息检索`

> DailyQA: A Benchmark to Evaluate Web Retrieval Augmented LLMs Based on Capturing Real-World Changes

# 摘要

> 我们提出了DailyQA，一个自动更新的动态数据集，每周更新问题并包含针对任意日期的问题答案。DailyQA利用Wikipedia修订日志的每日更新，构建了一个完整的自动化处理流程，涵盖数据筛选、查询生成、质量检查、答案提取和分类。该基准要求大型语言模型（LLMs）处理涉及快速变化事实数据并跨多领域的问题。我们使用不同带有网络搜索增强的RAG管道，评估了多个开源和闭源的LLMs。我们发现，不同模型在处理时效性网络信息方面的能力存在差异，其中对网络检索结果进行重排序至关重要。我们的结果显示，LLMs在处理频繁更新的信息方面仍然面临显著挑战，DailyQA基准测试为LLMs和RAG系统的发展方向提供了有价值的见解。

> We propose DailyQA, an automatically updated dynamic dataset that updates questions weekly and contains answers to questions on any given date. DailyQA utilizes daily updates from Wikipedia revision logs to implement a fully automated pipeline of data filtering, query generation synthesis, quality checking, answer extraction, and query classification. The benchmark requires large language models (LLMs) to process and answer questions involving fast-changing factual data and covering multiple domains. We evaluate several open-source and closed-source LLMs using different RAG pipelines with web search augmentation. We compare the ability of different models to process time-sensitive web information and find that rerank of web retrieval results is critical. Our results indicate that LLMs still face significant challenges in handling frequently updated information, suggesting that DailyQA benchmarking provides valuable insights into the direction of progress for LLMs and RAG systems.

[Arxiv](https://arxiv.org/abs/2505.17162)