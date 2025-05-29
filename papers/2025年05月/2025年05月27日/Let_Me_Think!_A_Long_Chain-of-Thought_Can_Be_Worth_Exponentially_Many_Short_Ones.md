# 让我想想！一条长长的思考链，可能比指数级多的短链更有价值。

发布时间：2025年05月27日

`LLM理论` `人工智能` `计算机科学`

> Let Me Think! A Long Chain-of-Thought Can Be Worth Exponentially Many Short Ones

# 摘要

> 推理时间计算成为提升大型语言模型推理能力的新兴关键方向。尽管已展现出令人瞩目的性能，但如何优化推理时间计算资源的分配仍存在诸多未知。核心问题是，应优先采用序列扩展（如更长的思维链）还是并行扩展（如多个短思维链的多数投票）。本研究旨在通过展示存在推理场景下序列扩展较并行扩展具有指数级优势的现象，阐明推理时间扩展的全景图。这些场景基于具有挑战性的图分布中的图连通性问题。我们通过涵盖多种语言模型的全面实验验证了理论发现，包括专为不同思维链策略设计的图连通性模型，以及大型推理模型。


> Inference-time computation has emerged as a promising scaling axis for improving large language model reasoning. However, despite yielding impressive performance, the optimal allocation of inference-time computation remains poorly understood. A central question is whether to prioritize sequential scaling (e.g., longer chains of thought) or parallel scaling (e.g., majority voting across multiple short chains of thought). In this work, we seek to illuminate the landscape of test-time scaling by demonstrating the existence of reasoning settings where sequential scaling offers an exponential advantage over parallel scaling. These settings are based on graph connectivity problems in challenging distributions of graphs. We validate our theoretical findings with comprehensive experiments across a range of language models, including models trained from scratch for graph connectivity with different chain of thought strategies as well as large reasoning models.

[Arxiv](https://arxiv.org/abs/2505.21825)