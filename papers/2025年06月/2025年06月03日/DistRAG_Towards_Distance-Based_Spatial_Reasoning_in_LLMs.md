# # **DistRAG：探索大型语言模型中的基于距离的空间推理方法**

发布时间：2025年06月03日

`RAG` `地理信息系统` `知识图谱`

> DistRAG: Towards Distance-Based Spatial Reasoning in LLMs

# 摘要

> 许多现实任务适合使用大型语言模型（LLMs），但这些任务往往需要空间推理能力，例如兴趣点 (POI) 推荐和行程规划。然而，LLMs本身缺乏可靠的空间推理能力，尤其是关于距离的推理。为了解决这一问题，我们开发了一种新颖的方法DistRAG，使LLM能够检索在训练过程中未显式学习的相关空间信息。我们的方法将城市和城镇之间的测地线距离编码到图中，并检索与问题相关的上下文子图。通过这项技术，我们的方法使LLM能够回答它本身无法回答的距离推理问题。考虑到LLM可能被问及的地点种类繁多，DistRAG为构建一个基本的`世界模型`提供了一个灵活的第一步，以补充LLMs中存储的语言知识。

> Many real world tasks where Large Language Models (LLMs) can be used require spatial reasoning, like Point of Interest (POI) recommendation and itinerary planning. However, on their own LLMs lack reliable spatial reasoning capabilities, especially about distances. To address this problem, we develop a novel approach, DistRAG, that enables an LLM to retrieve relevant spatial information not explicitly learned during training. Our method encodes the geodesic distances between cities and towns in a graph and retrieves a context subgraph relevant to the question. Using this technique, our method enables an LLM to answer distance-based reasoning questions that it otherwise cannot answer. Given the vast array of possible places an LLM could be asked about, DistRAG offers a flexible first step towards providing a rudimentary `world model' to complement the linguistic knowledge held in LLMs.

[Arxiv](https://arxiv.org/abs/2506.03424)