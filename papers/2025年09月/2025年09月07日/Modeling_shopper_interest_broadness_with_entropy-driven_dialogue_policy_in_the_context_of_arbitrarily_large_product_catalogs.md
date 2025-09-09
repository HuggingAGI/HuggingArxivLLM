# 超大型产品目录场景下基于熵驱动对话策略的购物者兴趣广度建模

发布时间：2025年09月07日

`Agent` `零售与电商`

> Modeling shopper interest broadness with entropy-driven dialogue policy in the context of arbitrarily large product catalogs

# 摘要

> 对话推荐系统有望为电子商务带来丰富的交互体验，但在平衡探索（澄清用户需求）与利用（给出推荐）方面仍面临挑战，尤其是在部署搭载庞大产品目录的大型语言模型（LLMs）时。为解决这一挑战，我们通过检索分数分布的熵来建模用户兴趣的广度：利用神经检索器获取用户查询的相关商品，计算重排序分数的熵，以此动态规划对话策略——低熵（明确）的查询会触发直接推荐，而高熵（模糊）的查询则会引发探索性问题。这种简单却高效的策略，能让LLM驱动的智能体实时掌握任意庞大的商品目录，同时不会增加其上下文窗口负担。

> Conversational recommender systems promise rich interactions for e-commerce, but balancing exploration (clarifying user needs) and exploitation (making recommendations) remains challenging, especially when deploying large language models (LLMs) with vast product catalogs. We address this challenge by modeling the breadth of user interest via the entropy of retrieval score distributions. Our method uses a neural retriever to fetch relevant items for a user query and computes the entropy of the re-ranked scores to dynamically route the dialogue policy: low-entropy (specific) queries trigger direct recommendations, whereas high-entropy (ambiguous) queries prompt exploratory questions. This simple yet effective strategy allows an LLM-driven agent to remain aware of an arbitrarily large catalog in real-time without bloating its context window.

[Arxiv](https://arxiv.org/abs/2509.06185)