# DeepRAG: 大型语言模型的逐步检索思考

发布时间：2025年02月03日

`RAG

理由：这篇论文主要讨论了如何通过检索增强生成（RAG）来优化大型语言模型（LLMs）的推理能力。论文提出了DeepRAG框架，将检索增强推理建模为马尔可夫决策过程（MDP），并通过迭代分解查询来动态决定检索外部知识还是依赖参数推理。这表明论文的核心内容集中在RAG技术的应用和改进上，因此应归类为RAG。` `信息检索`

> DeepRAG: Thinking to Retrieval Step by Step for Large Language Models

# 摘要

> 大型语言模型（LLMs）在推理方面展现了巨大潜力，但受限于参数知识的时效性、准确性和覆盖范围，它们仍面临严重的事实幻觉问题。同时，将推理与检索增强生成（RAG）结合也颇具挑战，任务分解无效和冗余检索可能引入噪声，降低响应质量。本文提出DeepRAG框架，将检索增强推理建模为马尔可夫决策过程（MDP），实现战略性和自适应的检索。通过迭代分解查询，DeepRAG在每一步动态决定是检索外部知识还是依赖参数推理。实验表明，DeepRAG在提升检索效率的同时，将答案准确率提高了21.99%，展现了其在优化检索增强推理方面的卓越效果。

> Large Language Models (LLMs) have shown remarkable potential in reasoning while they still suffer from severe factual hallucinations due to timeliness, accuracy, and coverage of parametric knowledge. Meanwhile, integrating reasoning with retrieval-augmented generation (RAG) remains challenging due to ineffective task decomposition and redundant retrieval, which can introduce noise and degrade response quality. In this paper, we propose DeepRAG, a framework that models retrieval-augmented reasoning as a Markov Decision Process (MDP), enabling strategic and adaptive retrieval. By iteratively decomposing queries, DeepRAG dynamically determines whether to retrieve external knowledge or rely on parametric reasoning at each step. Experiments show that DeepRAG improves retrieval efficiency while improving answer accuracy by 21.99%, demonstrating its effectiveness in optimizing retrieval-augmented reasoning.

[Arxiv](https://arxiv.org/abs/2502.01142)