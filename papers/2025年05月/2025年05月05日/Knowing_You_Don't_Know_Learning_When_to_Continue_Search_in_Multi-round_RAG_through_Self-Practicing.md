# 知所未知：多轮 RAG 中何时继续搜索的自我学习探索

发布时间：2025年05月05日

`RAG` `问答系统` `对话系统`

> Knowing You Don't Know: Learning When to Continue Search in Multi-round RAG through Self-Practicing

# 摘要

> 检索增强生成（RAG）在提升语言模型的知识储备和减少AI生成的幻觉方面表现出色，推动了其广泛应用。然而，对于需要多轮检索的复杂任务，仍面临挑战：现有系统要么在已有足够信息时继续无谓搜索，要么在信息不足时贸然给出错误答案。现有解决方案要么依赖大量昂贵的人工标注数据，要么导致性能欠佳。
    本文提出	extbf{SIM-RAG}框架，旨在增强RAG系统的自我意识和多轮检索能力。训练时，我们让RAG系统通过自练多轮检索生成合成数据，每对问答都可能探索多种检索路径，并根据是否成功找到正确答案进行标注。基于此数据，我们训练了一个轻量级的信息充足性评论员。推理时，评论员通过上下文强化学习评估每轮检索是否充分，指导检索决策并提升系统自我意识。
    多个知名RAG基准的实验表明，SIM-RAG是一个高效且实用的多轮RAG解决方案。该框架无需修改现有LLMs或搜索引擎，仅添加轻量级组件，且无需昂贵的中间检索过程监督数据，真正实现了系统与数据的双重高效。

> Retrieval Augmented Generation (RAG) has shown strong capability in enhancing language models' knowledge and reducing AI generative hallucinations, driving its widespread use. However, complex tasks requiring multi-round retrieval remain challenging, and early attempts tend to be overly optimistic without a good sense of self-skepticism. Current multi-round RAG systems may continue searching even when enough information has already been retrieved, or they may provide incorrect answers without having sufficient information or knowledge. Existing solutions either require large amounts of expensive human-labeled process supervision data or lead to subpar performance.
  This paper aims to address these limitations by introducing a new framework, \textbf{SIM-RAG}, to explicitly enhance RAG systems' self-awareness and multi-round retrieval capabilities. To train SIM-RAG, we first let a RAG system self-practice multi-round retrieval, augmenting existing question-answer pairs with intermediate inner monologue reasoning steps to generate synthetic training data. For each pair, the system may explore multiple retrieval paths, which are labeled as successful if they reach the correct answer and unsuccessful otherwise. Using this data, we train a lightweight information sufficiency Critic. At inference time, the Critic evaluates whether the RAG system has retrieved sufficient information at each round, guiding retrieval decisions and improving system-level self-awareness through in-context reinforcement learning.
  Experiments across multiple prominent RAG benchmarks show that SIM-RAG is an effective multi-round RAG solution. Furthermore, this framework is system-efficient, adding a lightweight component to RAG without requiring modifications to existing LLMs or search engines, and data-efficient, eliminating the need for costly human-annotated mid-step retrieval process supervision data.

[Arxiv](https://arxiv.org/abs/2505.02811)