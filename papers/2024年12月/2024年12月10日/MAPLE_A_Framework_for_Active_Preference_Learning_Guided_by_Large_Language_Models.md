# MAPLE：大型语言模型引导下的主动偏好学习框架

发布时间：2024年12月10日

`LLM应用` `偏好学习`

> MAPLE: A Framework for Active Preference Learning Guided by Large Language Models

# 摘要

> 大型语言模型（LLMs）的问世，激起了人们用自然语言进行偏好学习的浓厚兴趣。然而，现有的方法常存在计算负担重、人力监督成本高以及缺乏可解释性等问题。为应对这些难题，我们推出了 MAPLE，这是一个由大型语言模型引导的贝叶斯主动偏好学习框架。MAPLE 借助 LLMs 对偏好函数的分布进行建模，以自然语言反馈和诸如成对轨迹排名之类的传统偏好学习反馈为条件。MAPLE 还运用主动学习来有系统地降低此分布中的不确定性，并融入语言条件下的主动查询选择机制，以找出有价值且易回答的查询，进而减轻人力负担。我们在两个基准上对 MAPLE 的样本效率和偏好推断质量进行了评估，其中包括使用 OpenStreetMap 数据的真实世界车辆路线规划基准。结果显示，MAPLE 加快了学习进程，有效提升了人类回答查询的能力。

> The advent of large language models (LLMs) has sparked significant interest in using natural language for preference learning. However, existing methods often suffer from high computational burdens, taxing human supervision, and lack of interpretability. To address these issues, we introduce MAPLE, a framework for large language model-guided Bayesian active preference learning. MAPLE leverages LLMs to model the distribution over preference functions, conditioning it on both natural language feedback and conventional preference learning feedback, such as pairwise trajectory rankings. MAPLE also employs active learning to systematically reduce uncertainty in this distribution and incorporates a language-conditioned active query selection mechanism to identify informative and easy-to-answer queries, thus reducing human burden. We evaluate MAPLE's sample efficiency and preference inference quality across two benchmarks, including a real-world vehicle route planning benchmark using OpenStreetMap data. Our results demonstrate that MAPLE accelerates the learning process and effectively improves humans' ability to answer queries.

[Arxiv](https://arxiv.org/abs/2412.07207)