# # LAG：从笛卡尔视角看逻辑增强生成

发布时间：2025年08月07日

`LLM理论` `专业领域`

> LAG: Logic-Augmented Generation from a Cartesian Perspective

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出色，但在需要专业知识的领域却常因生成幻觉而受限。检索增强生成（RAG）虽通过整合外部知识有所改善，但其在复杂推理场景中仍显不足，主要由于直接语义检索和缺乏结构化逻辑组织的局限。本文受笛卡尔《方法论》启发，提出了一种全新的逻辑增强生成（LAG）范式，通过系统性问题分解和依赖感知推理重新定义知识增强。具体来说，LAG将复杂问题拆解为按逻辑依赖顺序排列的原子子问题，并依次解决，利用先前答案指导后续检索，确保每一步的逻辑扎实。为防止错误传播，LAG引入逻辑终止机制，在遇到无法回答的子问题时立即停止推理，避免计算浪费。最终，LAG整合所有子问题的解决方案生成可靠回答。实验结果表明，LAG显著提升了推理稳健性，减少了幻觉，并使LLM的问题解决更贴近人类认知，为现有RAG系统提供了一种原理性的替代方案。

> Large language models (LLMs) have demonstrated remarkable capabilities across a wide range of tasks, yet exhibit critical limitations in knowledge-intensive tasks, often generating hallucinations when faced with questions requiring specialized expertise. While retrieval-augmented generation (RAG) mitigates this by integrating external knowledge, it struggles with complex reasoning scenarios due to its reliance on direct semantic retrieval and lack of structured logical organization. Inspired by Cartesian principles from \textit{Discours de la méthode}, this paper introduces Logic-Augmented Generation (LAG), a novel paradigm that reframes knowledge augmentation through systematic question decomposition and dependency-aware reasoning. Specifically, LAG first decomposes complex questions into atomic sub-questions ordered by logical dependencies. It then resolves these sequentially, using prior answers to guide context retrieval for subsequent sub-questions, ensuring stepwise grounding in logical chain. To prevent error propagation, LAG incorporates a logical termination mechanism that halts inference upon encountering unanswerable sub-questions and reduces wasted computation on excessive reasoning. Finally, it synthesizes all sub-resolutions to generate verified responses. Experiments on four benchmark datasets demonstrate that LAG significantly enhances reasoning robustness, reduces hallucination, and aligns LLM problem-solving with human cognition, offering a principled alternative to existing RAG systems.

[Arxiv](https://arxiv.org/abs/2508.05509)