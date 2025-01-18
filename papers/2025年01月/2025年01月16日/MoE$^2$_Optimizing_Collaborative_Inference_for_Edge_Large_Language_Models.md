# MoE$^2$: 边缘大型语言模型协作推理的优化

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了如何利用边缘LLMs的异构能力来提升推理性能，并提出了一种新颖的边缘LLMs协作推理框架（MoE$^2$）。论文的核心在于优化LLM在边缘计算环境中的应用，特别是在能量和延迟约束下的推理性能。这属于LLM在实际应用中的优化和部署，因此归类为LLM应用。` `边缘计算`

> MoE$^2$: Optimizing Collaborative Inference for Edge Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）在自然语言处理任务中展现了卓越的能力。利用边缘LLMs的异构能力，对于新兴应用至关重要，因为它能显著提升成本效益并降低延迟。本文提出了一种新颖的边缘LLMs协作推理框架——	extit{Mixture-of-Edge-Experts (MoE$^2$)}。我们通过联合门控和专家选择问题，在能量和延迟约束下优化推理性能。与传统MoE问题不同，由于边缘LLMs在属性上的组合性和异质性，LLM专家选择更具挑战性。为此，我们设计了一种两级专家选择机制，揭示了专家选择中门控参数的保优性，从而简化了训练和选择过程。此外，我们利用目标的单调性，提出了一种离散单调优化算法，以实现最优专家选择。我们在NVIDIA Jetson AGX Orins和NVIDIA RTX 4090 GPU上部署了边缘服务器，并进行了大量实验。结果表明，MoE$^2$方法在各种LLM模型上均表现出性能提升，能够在不同延迟和能量预算下实现最佳权衡，并在多种系统资源约束下优于基线方法。

> Large language models (LLMs) have demonstrated remarkable capabilities across a wide range of natural language processing tasks. Exploiting the heterogeneous capabilities of edge LLMs is crucial for diverse emerging applications, as it enables greater cost-effectiveness and reduced latency. In this work, we introduce \textit{Mixture-of-Edge-Experts (MoE$^2$)}, a novel collaborative inference framework for edge LLMs. We formulate the joint gating and expert selection problem to optimize inference performance under energy and latency constraints. Unlike conventional MoE problems, LLM expert selection is significantly more challenging due to the combinatorial nature and the heterogeneity of edge LLMs across various attributes. To this end, we propose a two-level expert selection mechanism through which we uncover an optimality-preserving property of gating parameters across expert selections. This property enables the decomposition of the training and selection processes, significantly reducing complexity. Furthermore, we leverage the objective's monotonicity and design a discrete monotonic optimization algorithm for optimal expert selection. We implement edge servers with NVIDIA Jetson AGX Orins and NVIDIA RTX 4090 GPUs, and perform extensive experiments. Our results validate that performance improvements of various LLM models and show that our MoE$^2$ method can achieve optimal trade-offs among different delay and energy budgets, and outperforms baselines under various system resource constraints.

[Arxiv](https://arxiv.org/abs/2501.09410)