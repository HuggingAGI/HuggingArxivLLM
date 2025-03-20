# 推理努力与问题复杂性：LLMs中的缩放分析

发布时间：2025年03月19日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在推理能力方面的表现，特别是它们在处理不同复杂度的问题时的推理努力变化。研究揭示了LLMs在逻辑连贯性和推理可扩展性方面的根本性局限，并分析了现有模型之间的性能差异。这些内容属于对LLMs理论和机制的深入研究，因此归类为LLM理论。` `人工智能` `逻辑推理`

> Reasoning Effort and Problem Complexity: A Scaling Analysis in LLMs

# 摘要

> 大型语言模型（LLMs）不仅在文本生成方面表现出色，其推理能力也因训练范式的革新而取得突破。本研究聚焦于模型推理能力随问题复杂度的变化规律。我们以具有线性时间解法的无限扩展帐篷谜题为研究对象，揭示了推理努力的扩展特性。研究发现，推理努力虽随问题规模增长，但仅在特定复杂度阈值内显著提升。一旦超过该阈值，推理努力不仅停止增长，反而可能下降。这一现象揭示了当前LLMs在逻辑连贯性上的根本性局限，特别是在处理复杂问题时的不足，同时也凸显了提升推理可扩展性的迫切需求。此外，研究还显示，面对日益复杂的逻辑谜题，现有先进推理模型间存在显著性能差异。

> Large Language Models (LLMs) have demonstrated remarkable text generation capabilities, and recent advances in training paradigms have led to breakthroughs in their reasoning performance. In this work, we investigate how the reasoning effort of such models scales with problem complexity. We use the infinitely scalable Tents puzzle, which has a known linear-time solution, to analyze this scaling behavior. Our results show that reasoning effort scales with problem size, but only up to a critical problem complexity. Beyond this threshold, the reasoning effort does not continue to increase, and may even decrease. This observation highlights a critical limitation in the logical coherence of current LLMs as problem complexity increases, and underscores the need for strategies to improve reasoning scalability. Furthermore, our results reveal significant performance differences between current state-of-the-art reasoning models when faced with increasingly complex logical puzzles.

[Arxiv](https://arxiv.org/abs/2503.15113)