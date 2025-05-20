# # 叠加推理：连续思维链的理论视角

发布时间：2025年05月18日

`LLM理论` `人工智能` `机器学习`

> Reasoning by Superposition: A Theoretical Perspective on Chain of Continuous Thought

# 摘要

> 大型语言模型（LLMs）在众多应用中表现出色，尤其是通过链式思维（CoTs）技术解决复杂推理问题，该技术会在回答问题前生成 ``思考标记''。虽然现有理论表明，离散标记的CoTs能提升LLMs能力，但近期关于连续CoTs的研究尚未完全揭示其为何在有向图可达性等推理任务中优于离散方法。本文证明，一个带有 $D$ 步连续CoTs 的两层变压器能解决有向图可达性问题，其中 $D$ 是图的直径，而离散CoTs 的常数深度变压器需 $O(n^2)$ 解码步骤（$D < n$）。我们的构造中，每个连续思维向量是叠加状态，同时编码多个搜索前沿（即并行BFS），而离散CoTs 只能选择单路径，导致更多步骤的顺序搜索，可能陷入局部解。实验表明，我们的理论与训练结果一致。值得注意的是，叠加状态的多路径搜索在训练连续CoTs 时自动出现，无需显式监督。

> Large Language Models (LLMs) have demonstrated remarkable performance in many applications, including challenging reasoning problems via chain-of-thoughts (CoTs) techniques that generate ``thinking tokens'' before answering the questions. While existing theoretical works demonstrate that CoTs with discrete tokens boost the capability of LLMs, recent work on continuous CoTs lacks a theoretical understanding of why it outperforms discrete counterparts in various reasoning tasks such as directed graph reachability, a fundamental graph reasoning problem that includes many practical domain applications as special cases. In this paper, we prove that a two-layer transformer with $D$ steps of continuous CoTs can solve the directed graph reachability problem, where $D$ is the diameter of the graph, while the best known result of constant-depth transformers with discrete CoTs requires $O(n^2)$ decoding steps where $n$ is the number of vertices ($D<n$). In our construction, each continuous thought vector is a superposition state that encodes multiple search frontiers simultaneously (i.e., parallel breadth-first search (BFS)), while discrete CoTs must choose a single path sampled from the superposition state, which leads to sequential search that requires many more steps and may be trapped into local solutions. We also performed extensive experiments to verify that our theoretical construction aligns well with the empirical solution obtained via training dynamics. Notably, encoding of multiple search frontiers as a superposition state automatically emerges in training continuous CoTs, without explicit supervision to guide the model to explore multiple paths simultaneously.

[Arxiv](https://arxiv.org/abs/2505.12514)