# 面向检索器的通用强化学习查询改写方法，基于非结构化真实文档

发布时间：2025年07月31日

`RAG` `信息检索`

> Generalized Reinforcement Learning for Retriever-Specific Query Rewriter with Unstructured Real-World Documents

# 摘要

> 检索增强生成（RAG）系统的性能高度依赖于有效的查询构建，但如何优化针对多样化非结构化文档的查询仍是一个难题。我们提出了	extbf{RL-QR}，一个无需人工标注数据的强化学习框架，专门用于优化检索器的查询重写，支持纯文本和多模态数据库。通过场景-问题配对合成和广义奖励策略优化（GRPO），RL-QR能够训练出针对特定检索器的优化器，显著提升跨领域检索效果。在工业级数据实验中，$	ext{RL-QR}_{	ext{multi-modal}}$使多模态RAG的NDCG@3提升了11%，而$	ext{RL-QR}_{	ext{lexical}}$为词汇检索器带来了9%的性能提升。然而，语义和混合检索器的优化仍具挑战，这可能源于训练目标的不一致。我们的研究不仅展示了RL-QR在RAG系统查询优化方面的潜力，还为现实世界中的检索任务提供了一种高效且无需标注的解决方案，同时也为未来在语义检索领域的改进指明了方向。

> Retrieval-Augmented Generation (RAG) systems rely heavily on effective query formulation to unlock external knowledge, yet optimizing queries for diverse, unstructured real-world documents remains a challenge. We introduce \textbf{RL-QR}, a reinforcement learning framework for retriever-specific query rewriting that eliminates the need for human-annotated datasets and extends applicability to both text-only and multi-modal databases. By synthesizing scenario-question pairs and leveraging Generalized Reward Policy Optimization (GRPO), RL-QR trains query rewriters tailored to specific retrievers, enhancing retrieval performance across varied domains. Experiments on industrial in-house data demonstrate significant improvements, with $\text{RL-QR}_{\text{multi-modal}}$ achieving an 11\% relative gain in NDCG@3 for multi-modal RAG and $\text{RL-QR}_{\text{lexical}}$ yielding a 9\% gain for lexical retrievers. However, challenges persist with semantic and hybrid retrievers, where rewriters failed to improve performance, likely due to training misalignments. Our findings highlight RL-QR's potential to revolutionize query optimization for RAG systems, offering a scalable, annotation-free solution for real-world retrieval tasks, while identifying avenues for further refinement in semantic retrieval contexts.

[Arxiv](https://arxiv.org/abs/2507.23242)