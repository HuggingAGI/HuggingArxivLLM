# Driving-RAG：驾驶场景的嵌入、搜索与RAG应用实践

发布时间：2025年04月06日

`RAG` `自动驾驶` `智能汽车`

> Driving-RAG: Driving Scenarios Embedding, Search, and RAG Applications

# 摘要

> 驾驶场景数据在智能汽车与自动驾驶发展中扮演着越来越重要的角色。准确且高效的场景数据搜索对在线车辆决策规划与离线场景生成仿真都至关重要，它能够利用场景经验提升整体性能。尤其是在自动驾驶中应用大型语言模型（LLMs）和检索增强生成（RAG）系统的情况下，相关需求变得更加迫切。本文中，我们引入了Driving-RAG框架，旨在解决RAG系统在高效场景数据嵌入、搜索及应用方面的挑战。我们的嵌入模型在向量空间中对齐了基本场景信息与场景距离度量。结合典型场景采样方法与层次化可导航小世界结构，能够高效地进行场景向量搜索，同时保持高准确性。此外，基于图知识的重组机制增强了与提示场景的相关性，并增强了LLM的生成能力。我们在典型的轨迹规划任务中验证了所提框架的有效性，特别是在复杂交互场景（如匝道和交叉路口）中，展示了其在RAG应用中的优势。

> Driving scenario data play an increasingly vital role in the development of intelligent vehicles and autonomous driving. Accurate and efficient scenario data search is critical for both online vehicle decision-making and planning, and offline scenario generation and simulations, as it allows for leveraging the scenario experiences to improve the overall performance. Especially with the application of large language models (LLMs) and Retrieval-Augmented-Generation (RAG) systems in autonomous driving, urgent requirements are put forward. In this paper, we introduce the Driving-RAG framework to address the challenges of efficient scenario data embedding, search, and applications for RAG systems. Our embedding model aligns fundamental scenario information and scenario distance metrics in the vector space. The typical scenario sampling method combined with hierarchical navigable small world can perform efficient scenario vector search to achieve high efficiency without sacrificing accuracy. In addition, the reorganization mechanism by graph knowledge enhances the relevance to the prompt scenarios and augment LLM generation. We demonstrate the effectiveness of the proposed framework on typical trajectory planning task for complex interactive scenarios such as ramps and intersections, showcasing its advantages for RAG applications.

[Arxiv](https://arxiv.org/abs/2504.04419)