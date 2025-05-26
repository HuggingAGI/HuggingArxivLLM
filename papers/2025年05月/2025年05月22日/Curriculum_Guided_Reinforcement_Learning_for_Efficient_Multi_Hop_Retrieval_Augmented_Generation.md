# 一种用于高效多跳检索增强生成的课程指导强化学习方法。

发布时间：2025年05月22日

`RAG` `问答系统`

> Curriculum Guided Reinforcement Learning for Efficient Multi Hop Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）使大型语言模型（LLMs）基于最新的外部证据进行推理，但现有的多跳RAG流水线仍然存在冗余子查询、探索深度不足或搜索链过长的问题。为此，我们提出了EVO-RAG——一个基于课程指导的强化学习框架，能够从早期的广泛探索逐步优化到后期的精准调整。EVO-RAG通过结合一个包含七个因素的分步奖励向量（涵盖相关性、冗余性、效率和答案准确性）以及一个随时间动态调整权重的调度器，实现了智能体的高效训练。通过直接偏好优化在多头奖励模型上训练，该智能体能够灵活掌握何时进行搜索、回溯、回答或拒绝。在HotpotQA、2WikiMultiHopQA、MuSiQue和Bamboogle四个多跳问答基准测试中，EVO-RAG在Exact Match指标上超越现有RAG基线4.6个百分点，同时将平均检索深度降低了15%。消融实验进一步证明了课程分阶段和动态奖励调度的互补优势。因此，EVO-RAG为构建高效可靠的多跳RAG系统提供了一套通用解决方案。

> Retrieval-augmented generation (RAG) grounds large language models (LLMs) in up-to-date external evidence, yet existing multi-hop RAG pipelines still issue redundant subqueries, explore too shallowly, or wander through overly long search chains. We introduce EVO-RAG, a curriculum-guided reinforcement learning framework that evolves a query-rewriting agent from broad early-stage exploration to concise late-stage refinement. EVO-RAG couples a seven-factor, step-level reward vector (covering relevance, redundancy, efficiency, and answer correctness) with a time-varying scheduler that reweights these signals as the episode unfolds. The agent is trained with Direct Preference Optimization over a multi-head reward model, enabling it to learn when to search, backtrack, answer, or refuse. Across four multi-hop QA benchmarks (HotpotQA, 2WikiMultiHopQA, MuSiQue, and Bamboogle), EVO-RAG boosts Exact Match by up to 4.6 points over strong RAG baselines while trimming average retrieval depth by 15 %. Ablation studies confirm the complementary roles of curriculum staging and dynamic reward scheduling. EVO-RAG thus offers a general recipe for building reliable, cost-effective multi-hop RAG systems.

[Arxiv](https://arxiv.org/abs/2505.17391)