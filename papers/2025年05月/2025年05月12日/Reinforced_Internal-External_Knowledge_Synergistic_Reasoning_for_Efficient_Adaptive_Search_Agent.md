# 强化内外知识协同推理，实现高效自适应搜索代理

发布时间：2025年05月12日

`RAG` `知识推理`

> Reinforced Internal-External Knowledge Synergistic Reasoning for Efficient Adaptive Search Agent

# 摘要

> 检索增强生成（RAG）是降低大型语言模型（LLMs）幻觉现象的常用策略。虽然强化学习（RL）能够通过激活检索能力使LLMs充当搜索代理，但现有方法往往未能充分利用其内部知识，导致检索冗余、潜在有害的知识冲突以及推理延迟增加。为了解决这些限制，亟需一种高效且自适应的搜索代理，能够识别最佳检索时机，并协同整合参数化（内部）和检索到的（外部）知识。本文介绍了强化内外知识协同推理代理（IKEA），该模型能够识别自身知识边界，优先利用内部知识，并仅在内部知识被认为不足时才诉诸外部搜索。这是通过一种新型的知识边界感知奖励函数和知识边界感知训练数据集实现的。这些设计旨在实现面向内部-外部知识协同的强化学习，激励模型提供准确答案，减少不必要的检索，并在自身知识不足时鼓励适当的外部搜索。在多个知识推理任务上的评估表明，IKEA显著优于基线方法，大幅降低了检索频率，并展现了强大的泛化能力。

> Retrieval-augmented generation (RAG) is a common strategy to reduce hallucinations in Large Language Models (LLMs). While reinforcement learning (RL) can enable LLMs to act as search agents by activating retrieval capabilities, existing ones often underutilize their internal knowledge. This can lead to redundant retrievals, potential harmful knowledge conflicts, and increased inference latency. To address these limitations, an efficient and adaptive search agent capable of discerning optimal retrieval timing and synergistically integrating parametric (internal) and retrieved (external) knowledge is in urgent need. This paper introduces the Reinforced Internal-External Knowledge Synergistic Reasoning Agent (IKEA), which could indentify its own knowledge boundary and prioritize the utilization of internal knowledge, resorting to external search only when internal knowledge is deemed insufficient. This is achieved using a novel knowledge-boundary aware reward function and a knowledge-boundary aware training dataset. These are designed for internal-external knowledge synergy oriented RL, incentivizing the model to deliver accurate answers, minimize unnecessary retrievals, and encourage appropriate external searches when its own knowledge is lacking. Evaluations across multiple knowledge reasoning tasks demonstrate that IKEA significantly outperforms baseline methods, reduces retrieval frequency significantly, and exhibits robust generalization capabilities.

[Arxiv](https://arxiv.org/abs/2505.07596)