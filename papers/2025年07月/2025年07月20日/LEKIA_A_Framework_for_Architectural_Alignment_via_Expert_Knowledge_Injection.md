# LEKIA：借助专家知识注入实现架构对齐的技术框架

发布时间：2025年07月20日

`LLM应用` `高风险领域` `特殊教育`

> LEKIA: A Framework for Architectural Alignment via Expert Knowledge Injection

# 摘要

> 在高风险领域部署大型语言模型（LLMs）面临双重挑战：深度动态专家知识注入与细致价值对齐。现有方法通常分别应对这两个挑战，导致知识与对齐之间存在持久张力；注重知识的方法（如检索增强生成，RAG）在深度对齐能力上有限，而注重对齐的方法（如基于人类反馈的强化学习，RLHF）在敏捷注入专家智慧方面则面临困难。

本文提出了一种新的协作理念——专家拥有AI行为设计，通过架构对齐这一范式实现，将知识注入与价值对齐统一在一个名为分层专家知识注入架构（LEKIA）的框架中。LEKIA作为一个智能中间件，无需修改LLM的权重，通过三层结构引导其推理过程：理论层负责核心原则，实践层提供示例案例，评估层实现实时、符合价值观的自我修正。

我们通过成功实现一个基于LEKIA的心理支持助手在特殊教育领域的应用，展示了该范式的有效性。我们的工作为构建更负责任和专家驱动的AI提供了路径，赋能领域专家直接架构AI行为，解决知识与对齐之间的张力。

> Deploying Large Language Models (LLMs) in high-stakes domains is impeded by a dual challenge: the need for deep, dynamic expert knowledge injection and nuanced value alignment. Prevailing paradigms often address these challenges separately, creating a persistent tension between knowledge and alignment; knowledge-focused methods like Retrieval-Augmented Generation (RAG) have limited deep alignment capabilities, while alignment-focused methods like Reinforcement Learning from Human Feedback (RLHF) struggle with the agile injection of expert wisdom. This paper introduces a new collaborative philosophy, Expert-owned AI behavior design, realized through Architectural Alignment-a paradigm that unifies these two goals within a single framework called the Layered Expert Knowledge Injection Architecture (LEKIA). LEKIA operates as an intelligent intermediary that guides an LLM's reasoning process without altering its weights, utilizing a three-tiered structure: a Theoretical Layer for core principles, a Practical Layer for exemplary cases, and an Evaluative Layer for real-time, value-aligned self-correction. We demonstrate the efficacy of this paradigm through the successful implementation of a LEKIA-based psychological support assistant for the special education field. Our work presents a path toward more responsible and expert-driven AI, empowering domain specialists to directly architect AI behavior and resolve the tension between knowledge and alignment.

[Arxiv](https://arxiv.org/abs/2507.14944)