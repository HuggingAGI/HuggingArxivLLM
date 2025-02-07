# TeZO: 在零阶优化中强化时间维度的低秩性，助力大型语言模型微调

发布时间：2025年01月31日

`LLM理论

**理由**：该论文主要讨论了零阶优化（ZO）在LLMs高效微调任务中的应用，并提出了一种新的低秩ZO估计器TeZO。论文的核心内容涉及LLMs的优化算法和理论分析，属于对LLMs底层理论的研究和改进，因此应归类为LLM理论。` `机器学习` `优化算法`

> TeZO: Empowering the Low-Rankness on the Temporal Dimension in the Zeroth-Order Optimization for Fine-tuning LLMs

# 摘要

> 零阶优化（ZO）在LLMs的高效微调任务中表现出色。最新进展结合梯度的低秩特性，推出了低秩ZO估计器，进一步降低了GPU内存消耗。然而，现有研究大多只关注单个梯度的低秩性，忽视了训练过程中所有梯度共享的一个更广泛特性——它们近似位于同一子空间。本文综合考虑这两个因素，提出了一种新颖的低秩ZO估计器TeZO，它能同时捕捉模型和时间维度上的低秩性。具体来说，我们将时间维度上的ZO扰动表示为3D张量，并通过规范多分量分解（CPD）提取每个低秩2D矩阵，大幅降低训练成本。TeZO还可轻松扩展为Adam变体，内存消耗比MeZO-SGD更少，仅需MeZO-Adam约35%的内存。理论分析和实验研究均验证了其高效性，在较低的时间和内存开销下实现了与SOTA相当的结果。

> Zeroth-order optimization (ZO) has demonstrated remarkable promise in efficient fine-tuning tasks for Large Language Models (LLMs). In particular, recent advances incorporate the low-rankness of gradients, introducing low-rank ZO estimators to further reduce GPU memory consumption. However, most existing works focus solely on the low-rankness of each individual gradient, overlooking a broader property shared by all gradients throughout the training, i.e., all gradients approximately reside within a similar subspace. In this paper, we consider two factors together and propose a novel low-rank ZO estimator, TeZO, which captures the low-rankness across both the model and temporal dimension. Specifically, we represent ZO perturbations along the temporal dimension as a 3D tensor and employ Canonical Polyadic Decomposition (CPD) to extract each low-rank 2D matrix, significantly reducing the training cost. TeZO can also be easily extended to the Adam variant while consuming less memory than MeZO-SGD, and requiring about only 35% memory of MeZO-Adam. Both comprehensive theoretical analysis and extensive experimental research have validated its efficiency, achieving SOTA-comparable results with lower overhead of time and memory.

[Arxiv](https://arxiv.org/abs/2501.19057)