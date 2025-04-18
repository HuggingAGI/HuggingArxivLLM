# InstructRAG: 基于指令图的检索增强生成方法，用于LLM任务规划

发布时间：2025年04月17日

`RAG` `任务规划` `智能体`

> InstructRAG: Leveraging Retrieval-Augmented Generation on Instruction Graphs for LLM-Based Task Planning

# 摘要

> 近期，大型语言模型（LLMs）的突破使其能够担任复杂任务规划的智能体角色。传统方法通常借助思考-行动-观察（TAO）流程提升模型性能，但受限于模型对复杂任务理解的不足。检索增强生成（RAG）通过结合外部数据库，为任务规划开辟了新途径。本文指出在将RAG应用于任务规划时的两大关键挑战（可扩展性和可迁移性），并提出基于多智能体元强化学习框架的创新解决方案——InstructRAG。该方案包含用于管理历史指令路径的图结构，一个通过强化学习扩展知识覆盖范围的RL-Agent，以及一个通过元学习提升任务适应能力的ML-Agent。两个Agent协同训练，共同优化整体规划效果。实验结果表明，在四个主流任务规划数据集上，InstructRAG不仅显著提升了任务规划性能，更实现了高达19.2%的性能提升，展现出对新任务的高效适应能力。

> Recent advancements in large language models (LLMs) have enabled their use as agents for planning complex tasks. Existing methods typically rely on a thought-action-observation (TAO) process to enhance LLM performance, but these approaches are often constrained by the LLMs' limited knowledge of complex tasks. Retrieval-augmented generation (RAG) offers new opportunities by leveraging external databases to ground generation in retrieved information. In this paper, we identify two key challenges (enlargability and transferability) in applying RAG to task planning. We propose InstructRAG, a novel solution within a multi-agent meta-reinforcement learning framework, to address these challenges. InstructRAG includes a graph to organize past instruction paths (sequences of correct actions), an RL-Agent with Reinforcement Learning to expand graph coverage for enlargability, and an ML-Agent with Meta-Learning to improve task generalization for transferability. The two agents are trained end-to-end to optimize overall planning performance. Our experiments on four widely used task planning datasets demonstrate that InstructRAG significantly enhances performance and adapts efficiently to new tasks, achieving up to a 19.2% improvement over the best existing approach.

[Arxiv](https://arxiv.org/abs/2504.13032)