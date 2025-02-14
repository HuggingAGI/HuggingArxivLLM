# 单一模型能否同时掌握多轮对话与工具使用？ CALM：统一的对话智能体语言模型

发布时间：2025年02月12日

`Agent` `任务导向对话` `语言代理`

> Can a Single Model Master Both Multi-turn Conversations and Tool Use? CALM: A Unified Conversational Agentic Language Model

# 摘要

> 具有API调用功能的大型语言模型（LLMs）能够构建有效的语言代理（LA），并革新了传统的任务导向对话（TOD）范式。然而，现有方法面临一个关键挑战：TOD系统通常基于有限的目标API进行训练，当与新服务交互时，需依赖新数据来保持性能，而语言代理（LA）则未经过在多轮对话中维持用户意图的训练。鉴于多轮对话管理和复杂功能调用对高效对话代理的重要性，我们在三个基准测试中评估了这些能力：MultiWOZ 2.4（TOD）、BFCL V3（LA）和API-Bank（LA）。分析发现，专门的方法在单一领域表现优异，但在另一领域则不尽如人意。为解决这一问题，我们提出了CALM（会话代理语言模型），一种融合了对话与代理能力的统一框架。我们构建了CALM-IT，一个精心设计的多任务数据集，将多轮ReAct推理与复杂API使用相结合。通过CALM-IT训练的CALM 8B、CALM 70B和CALM 405B模型，在所有三个基准测试中均超越了现有顶级领域模型，包括GPT-4o。

> Large Language Models (LLMs) with API-calling capabilities enabled building effective Language Agents (LA), while also revolutionizing the conventional task-oriented dialogue (TOD) paradigm. However, current approaches face a critical dilemma: TOD systems are often trained on a limited set of target APIs, requiring new data to maintain their quality when interfacing with new services, while LAs are not trained to maintain user intent over multi-turn conversations. Because both robust multi-turn management and advanced function calling are crucial for effective conversational agents, we evaluate these skills on three popular benchmarks: MultiWOZ 2.4 (TOD), BFCL V3 (LA), and API-Bank (LA), and our analyses reveal that specialized approaches excel in one domain but underperform in the other. To bridge this chasm, we introduce CALM (Conversational Agentic Language Model), a unified approach that integrates both conversational and agentic capabilities. We created CALM-IT, a carefully constructed multi-task dataset that interleave multi-turn ReAct reasoning with complex API usage. Using CALM-IT, we train three models CALM 8B, CALM 70B, and CALM 405B, which outperform top domain-specific models, including GPT-4o, across all three benchmarks.

[Arxiv](https://arxiv.org/abs/2502.08820)