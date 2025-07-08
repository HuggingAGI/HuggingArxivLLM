# 稀疏且平等的多智能体辩论：CortexDebate

发布时间：2025年07月05日

`LLM应用` `人工智能` `多智能体系统`

> CortexDebate: Debating Sparsely and Equally for Multi-Agent Debate

# 摘要

> 目前，单个大型语言模型（LLM）在幻觉和推理能力方面存在显著问题。为了解决这些问题，多智能体辩论（MAD）作为一种有效策略应运而生，通过让LLM智能体之间进行深入的任务辩论来提升性能。然而，现有的MAD方法存在两大挑战：输入上下文过长导致性能下降，以及过度自信的智能体主导辩论降低效果。为此，我们提出了一种名为“CortexDebate”的新型MAD方法。受人类大脑皮层区域之间建立稀疏且动态优化网络的启发，CortexDebate在LLM智能体之间构建了一个稀疏的辩论图，每个智能体仅与对其有帮助的智能体进行互动。为了优化这一结构，我们设计了基于麦肯锡的辩论物质（MDM）模块，该模块通过整合社会学中的麦肯锡信任公式，能够进行可信评估并优化辩论图。通过在四种任务类型下的八种数据集上的大量实验，我们充分验证了CortexDebate的优越性能。

> Nowadays, single Large Language Model (LLM) struggles with critical issues such as hallucination and inadequate reasoning abilities. To mitigate these issues, Multi-Agent Debate (MAD) has emerged as an effective strategy, where LLM agents engage in in-depth debates with others on tasks. However, existing MAD methods face two major issues: (a) too lengthy input contexts, which causes LLM agents to get lost in plenty of input information and experiences performance drop; and (b) the overconfidence dilemma, where self-assured LLM agents dominate the debate, leading to low debating effectiveness. To address these limitations, we propose a novel MAD method called "CortexDebate". Inspired by the human brain's tendency to establish a sparse and dynamically optimized network among cortical areas governed by white matter, CortexDebate constructs a sparse debating graph among LLM agents, where each LLM agent only debates with the ones that are helpful to it. To optimize the graph, we propose a module named McKinsey-based Debate Matter (MDM), which acts as an artificial analog to white matter. By integrating the McKinsey Trust Formula, a well-established measure of trustworthiness from sociology, MDM enables credible evaluations that guide graph optimization. The effectiveness of our CortexDebate has been well demonstrated by extensive experimental results across eight datasets from four task types.

[Arxiv](https://arxiv.org/abs/2507.03928)