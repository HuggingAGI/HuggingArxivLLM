# 一种基于零样本面向排名自动评估，在所有查询和语料库中表现卓越的分布式协作检索框架

发布时间：2024年12月16日

`LLM应用` `分布式系统`

> A Distributed Collaborative Retrieval Framework Excelling in All Queries and Corpora based on Zero-shot Rank-Oriented Automatic Evaluation

# 摘要

> 众多检索模型，像稀疏、密集以及基于 llm 的那些方法，在预测查询和语料库的相关性上表现不凡。然而，初步的有效性分析实验显示，这些模型在多数查询和语料库上都难以达到理想的性能，表明它们的有效性局限于特定场景。所以，为应对此问题，我们提出了新颖的分布式协同检索框架（DCRF），其在所有查询和语料库上的表现都超越了单个模型。具体来说，此框架将各类检索模型整合进统一系统，为每个用户的查询动态选出最优结果。它能够轻松聚合任何检索模型，并拓展到任何应用场景，彰显出其灵活性和可扩展性。另外，为降低维护和训练成本，我们借助大型语言模型（LLMs）设计了四种有效的提示策略，在不依赖标注数据的情况下评估排名质量。大量实验表明，所提出的框架结合 8 个高效检索模型，能够实现与 RankGPT 和 ListT5 等有效列表方法相媲美的性能，同时具备出色的效率。而且，DCRF 在大多数数据集上都优于所有选定的检索模型，这表明我们的提示策略在面向排名的自动评估中是有效的。

> Numerous retrieval models, including sparse, dense and llm-based methods, have demonstrated remarkable performance in predicting the relevance between queries and corpora. However, the preliminary effectiveness analysis experiments indicate that these models fail to achieve satisfactory performance on the majority of queries and corpora, revealing their effectiveness restricted to specific scenarios. Thus, to tackle this problem, we propose a novel Distributed Collaborative Retrieval Framework (DCRF), outperforming each single model across all queries and corpora. Specifically, the framework integrates various retrieval models into a unified system and dynamically selects the optimal results for each user's query. It can easily aggregate any retrieval model and expand to any application scenarios, illustrating its flexibility and scalability.Moreover, to reduce maintenance and training costs, we design four effective prompting strategies with large language models (LLMs) to evaluate the quality of ranks without reliance of labeled data. Extensive experiments demonstrate that proposed framework, combined with 8 efficient retrieval models, can achieve performance comparable to effective listwise methods like RankGPT and ListT5, while offering superior efficiency. Besides, DCRF surpasses all selected retrieval models on the most datasets, indicating the effectiveness of our prompting strategies on rank-oriented automatic evaluation.

[Arxiv](https://arxiv.org/abs/2412.11832)