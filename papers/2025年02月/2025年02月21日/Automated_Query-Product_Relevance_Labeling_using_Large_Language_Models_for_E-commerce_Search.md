# 基于大规模语言模型的电商搜索自动化查询-商品匹配标注

发布时间：2025年02月21日

`LLM应用` `电子商务` `信息检索`

> Automated Query-Product Relevance Labeling using Large Language Models for E-commerce Search

# 摘要

> 在电子商务搜索中，准确标注查询与产品相关性是生成真实标注数据集不可或缺的。传统基于人工的标注服务不仅昂贵、耗时，还容易出错。本研究探索了将大型语言模型（LLMs）应用于大规模电子商务搜索中的自动标注任务。我们使用了多个公开可用和专有的LLMs，并在两个开源数据集和一个内部电子商务搜索数据集上进行了实验。通过运用链式思维提示（CoT）、上下文学习（ICL）以及结合最大边际相关性（MMR）的检索增强生成（RAG）等提示工程技巧，我们证明LLMs在这一任务上的性能不仅在时间和成本上远低于人工标注，还能达到接近人类级别的准确性。我们已利用LLMs大规模生成了查询-产品相关性标签，并将其用于评估搜索算法的改进。本研究展示了LLMs在提升查询-产品相关性、从而增强电子商务搜索用户体验方面的潜力。更重要的是，这一可扩展的人工标注替代方案对信息检索领域（包括搜索和推荐系统）具有重要意义，因为相关性评分对于优化产品和内容的排名以提高客户参与度和其他转化指标至关重要。

> Accurate query-product relevance labeling is indispensable to generate ground truth dataset for search ranking in e-commerce. Traditional approaches for annotating query-product pairs rely on human-based labeling services, which is expensive, time-consuming and prone to errors. In this work, we explore the application of Large Language Models (LLMs) to automate query-product relevance labeling for large-scale e-commerce search. We use several publicly available and proprietary LLMs for this task, and conducted experiments on two open-source datasets and an in-house e-commerce search dataset. Using prompt engineering techniques such as Chain-of-Thought (CoT) prompting, In-context Learning (ICL), and Retrieval Augmented Generation (RAG) with Maximum Marginal Relevance (MMR), we show that LLM's performance has the potential to approach human-level accuracy on this task in a fraction of the time and cost required by human-labelers, thereby suggesting that our approach is more efficient than the conventional methods. We have generated query-product relevance labels using LLMs at scale, and are using them for evaluating improvements to our search algorithms. Our work demonstrates the potential of LLMs to improve query-product relevance thus enhancing e-commerce search user experience. More importantly, this scalable alternative to human-annotation has significant implications for information retrieval domains including search and recommendation systems, where relevance scoring is crucial for optimizing the ranking of products and content to improve customer engagement and other conversion metrics.

[Arxiv](https://arxiv.org/abs/2502.15990)