# LLMs在推荐中忽视的关键点：利用检索增强协作信号跨越鸿沟

发布时间：2025年05月27日

`LLM应用` `推荐系统` `信息检索`

> What LLMs Miss in Recommendations: Bridging the Gap with Retrieval-Augmented Collaborative Signals

# 摘要

> 用户-项目交互中的协同信号是众多成功推荐系统的核心。尽管近期研究探索了将大型语言模型（LLMs）应用于推荐系统，但LLMs能否有效利用这种协同信息仍不明确。本文通过系统性比较，评估LLMs与经典矩阵分解（MF）模型在利用用户-项目交互数据方面的表现。我们还引入了一种简单的检索增强生成（RAG）方法，通过将LLMs的预测基于结构化交互数据，提升其性能。实验结果显示，当前LLMs在捕捉MF模型固有的协同模式方面表现不足，但我们的RAG方法显著提升了推荐质量，为未来基于LLMs的推荐系统指明了方向。


> User-item interactions contain rich collaborative signals that form the backbone of many successful recommender systems. While recent work has explored the use of large language models (LLMs) for recommendation, it remains unclear whether LLMs can effectively reason over this type of collaborative information. In this paper, we conduct a systematic comparison between LLMs and classical matrix factorization (MF) models to assess LLMs' ability to leverage user-item interaction data. We further introduce a simple retrieval-augmented generation (RAG) method that enhances LLMs by grounding their predictions in structured interaction data. Our experiments reveal that current LLMs often fall short in capturing collaborative patterns inherent to MF models, but that our RAG-based approach substantially improves recommendation quality-highlighting a promising direction for future LLM-based recommenders.

[Arxiv](https://arxiv.org/abs/2505.20730)