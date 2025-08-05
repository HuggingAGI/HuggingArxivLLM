# MAO-ARAG: 多智能体编排用于自适应检索增强生成

发布时间：2025年08月01日

`RAG` `人工智能`

> MAO-ARAG: Multi-Agent Orchestration for Adaptive Retrieval-Augmented Generation

# 摘要

> 在问答（QA）系统中，检索增强生成（RAG）已成为提升回答准确性并减少幻觉问题的关键。RAG系统分为单轮、迭代和推理三种架构，分别针对不同问题类型进行优化。然而，由于实际问题复杂性各异，固定化的RAG流程难以兼顾性能与成本。为此，我们提出了基于多智能体编排的自适应RAG框架MAO-ARAG。该框架采用多轮设计，包含问题重述、文档选择和生成等多个执行器智能体。规划器智能体会根据具体问题，智能选择和整合合适的执行器，定制专属流程，在控制成本的同时生成优质答案。通过强化学习训练，规划器智能体以F1分数为奖励、成本为惩罚，持续优化答案质量。实验结果表明，MAO-ARAG通过动态规划工作流程，不仅保证了答案质量，还将成本和延迟控制在合理范围内。代码已开源，地址为https://github.com/chenyiqun/Agentic-RAG。

> In question-answering (QA) systems, Retrieval-Augmented Generation (RAG) has become pivotal in enhancing response accuracy and reducing hallucination issues. The architecture of RAG systems varies significantly, encompassing single-round RAG, iterative RAG, and reasoning RAG, each tailored to address different types of queries. Due to the varying complexity of real-world queries, a fixed RAG pipeline often struggles to balance performance and cost efficiency across different queries. To address this challenge, we propose an adaptive RAG framework called MAO-ARAG, which leverages multi-agent orchestration. Our adaptive RAG is conceived as a multi-turn framework. Specifically, we define multiple executor agents, representing typical RAG modules such as query reformulation agents, document selection agent, and generation agents. A planner agent intelligently selects and integrates the appropriate agents from these executors into a suitable workflow tailored for each query, striving for high-quality answers while maintaining reasonable costs. During each turn, the planner agent is trained using reinforcement learning, guided by an outcome-based reward (F1 score) and a cost-based penalty, continuously improving answer quality while keeping costs within a reasonable range. Experiments conducted on multiple QA datasets demonstrate that our approach, which dynamically plans workflows for each query, not only achieves high answer quality but also maintains both cost and latency within acceptable limits.The code of MAO-ARAG is on https://github.com/chenyiqun/Agentic-RAG.

[Arxiv](https://arxiv.org/abs/2508.01005)