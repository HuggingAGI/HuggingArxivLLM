# 叠加推理：从连续思维链的视角出发的理论探讨

发布时间：2025年05月18日

`LLM理论` `图推理` `模型推理`

> Reasoning by Superposition: A Theoretical Perspective on Chain of Continuous Thought

# 摘要

> 大型语言模型（LLMs）在众多应用中表现卓越，尤其在通过思维链（CoTs）技术解决复杂推理问题时，该技术会在回答问题前生成“思考标记”。尽管现有理论研究表明，基于离散标记的思维链能够提升LLMs的能力，但近期关于连续思维链的研究缺乏对其为何在有向图可达性等推理任务中超越离散方法的理论理解。有向图可达性是一个包含众多实际领域应用作为特例的基本图推理问题。本文证明，配备有【数学公式】步连续思维链的两层Transformer能够解决有向图可达性问题，其中【数学公式】为图的直径，而基于离散思维链的常数深度Transformer的最佳已知结果需要【数学公式】解码步骤，其中【数学公式】为顶点数量（【数学公式】）。在我们的构造中，每个连续思维向量是一种叠加态，能同时编码多个搜索前沿（即并行广度优先搜索（BFS）），而离散思维链必须从叠加态中选择单一路径，导致需要更多步骤的顺序搜索，并可能陷入局部解。我们还进行了大量实验，验证了我们的理论构造与通过训练动力学获得的经验解的良好一致性。值得注意的是，在训练连续思维链时，将多个搜索前沿编码为叠加态的能力会自动出现，而无需显式监督来引导模型同时探索多条路径。

> Large Language Models (LLMs) have demonstrated remarkable performance in many applications, including challenging reasoning problems via chain-of-thoughts (CoTs) techniques that generate ``thinking tokens'' before answering the questions. While existing theoretical works demonstrate that CoTs with discrete tokens boost the capability of LLMs, recent work on continuous CoTs lacks a theoretical understanding of why it outperforms discrete counterparts in various reasoning tasks such as directed graph reachability, a fundamental graph reasoning problem that includes many practical domain applications as special cases. In this paper, we prove that a two-layer transformer with $D$ steps of continuous CoTs can solve the directed graph reachability problem, where $D$ is the diameter of the graph, while the best known result of constant-depth transformers with discrete CoTs requires $O(n^2)$ decoding steps where $n$ is the number of vertices ($D<n$). In our construction, each continuous thought vector is a superposition state that encodes multiple search frontiers simultaneously (i.e., parallel breadth-first search (BFS)), while discrete CoTs must choose a single path sampled from the superposition state, which leads to sequential search that requires many more steps and may be trapped into local solutions. We also performed extensive experiments to verify that our theoretical construction aligns well with the empirical solution obtained via training dynamics. Notably, encoding of multiple search frontiers as a superposition state automatically emerges in training continuous CoTs, without explicit supervision to guide the model to explore multiple paths simultaneously.

[Arxiv](https://arxiv.org/abs/2505.12514)