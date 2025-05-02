# LLMs 与基于逻辑的框架结合，深入解析 MCTS

发布时间：2025年05月01日

`LLM应用` `人工智能` `决策支持系统`

> Combining LLMs with Logic-Based Framework to Explain MCTS

# 摘要

> 为了解决人工智能 (AI) 在序列规划中缺乏信任的问题，我们设计了一个基于计算树逻辑的大型语言模型 (LLM) 的自然语言解释框架，专门用于蒙特卡洛树搜索 (MCTS) 算法。尽管 MCTS 由于其复杂的搜索树结构而被认为难以解释，但我们的框架能够灵活应对围绕 MCTS 和应用领域马尔可夫决策过程 (MDP) 的各种自由形式事后查询和基于知识的询问。通过将用户查询转化为逻辑和变量声明，我们的框架确保了从搜索树中获得的证据在事实层面与底层环境动态以及实际随机控制过程中的任何约束保持一致。通过严格的定量评估，框架在准确性与事实一致性方面表现优异。

> In response to the lack of trust in Artificial Intelligence (AI) for sequential planning, we design a Computational Tree Logic-guided large language model (LLM)-based natural language explanation framework designed for the Monte Carlo Tree Search (MCTS) algorithm. MCTS is often considered challenging to interpret due to the complexity of its search trees, but our framework is flexible enough to handle a wide range of free-form post-hoc queries and knowledge-based inquiries centered around MCTS and the Markov Decision Process (MDP) of the application domain. By transforming user queries into logic and variable statements, our framework ensures that the evidence obtained from the search tree remains factually consistent with the underlying environmental dynamics and any constraints in the actual stochastic control process. We evaluate the framework rigorously through quantitative assessments, where it demonstrates strong performance in terms of accuracy and factual consistency.

[Arxiv](https://arxiv.org/abs/2505.00610)