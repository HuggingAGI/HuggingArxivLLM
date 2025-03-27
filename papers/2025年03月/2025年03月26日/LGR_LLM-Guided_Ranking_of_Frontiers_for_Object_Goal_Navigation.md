# LGR：基于LLM的前沿排序方法，用于目标物体导航任务

发布时间：2025年03月26日

`LLM应用` `机器人` `人工智能`

> LGR: LLM-Guided Ranking of Frontiers for Object Goal Navigation

# 摘要

> 目标导向导航（OGN）是机器人和AI领域的基础任务，其关键应用包括移动机器人图像数据库（MRID）。特别是在未知或动态环境中，无地图导航至关重要。本研究通过利用大型语言模型（LLMs）的常识推理能力，改进了近期的模块化无地图OGN系统。我们专注于解决基于前沿探索中的访问顺序问题，将其转化为前沿排序问题。研究发现，虽然LLMs无法确定单个前沿的绝对价值，但它们擅长利用图像上下文，评估多个前沿间的相对价值。我们通过动态管理前沿列表，并使用LLM作为排序模型，将排序结果表示为倒数排名向量，这非常适合多视图、多查询信息融合。我们在Habitat-Sim环境中验证了方法的有效性。

> Object Goal Navigation (OGN) is a fundamental task for robots and AI, with key applications such as mobile robot image databases (MRID). In particular, mapless OGN is essential in scenarios involving unknown or dynamic environments. This study aims to enhance recent modular mapless OGN systems by leveraging the commonsense reasoning capabilities of large language models (LLMs). Specifically, we address the challenge of determining the visiting order in frontier-based exploration by framing it as a frontier ranking problem. Our approach is grounded in recent findings that, while LLMs cannot determine the absolute value of a frontier, they excel at evaluating the relative value between multiple frontiers viewed within a single image using the view image as context. We dynamically manage the frontier list by adding and removing elements, using an LLM as a ranking model. The ranking results are represented as reciprocal rank vectors, which are ideal for multi-view, multi-query information fusion. We validate the effectiveness of our method through evaluations in Habitat-Sim.

[Arxiv](https://arxiv.org/abs/2503.20241)