# 可视化策略与奖励的互动，用于指导大型语言模型的零阶偏好优化

发布时间：2025年03月05日

`LLM应用

理由：这篇论文主要探讨了零阶优化方法在大型语言模型中的应用，特别是在偏好优化方面的创新。它不仅提出了新的算法，还通过实验证明了其在生成任务中的有效性，因此属于LLM应用类别。` `偏好优化`

> Visualising Policy-Reward Interplay to Inform Zeroth-Order Preference Optimisation of Large Language Models

# 摘要

> 利用一阶方法（如反向传播）微调大型语言模型计算成本高昂。零阶优化（ZO）通过函数评估而非梯度计算，降低了内存使用，但在高维模型中收敛速度慢。因此，零阶优化的研究在大型语言模型中主要聚焦于分类任务，而忽略了更复杂的生成任务。本文提出了一种名为ZOPrO的新型零阶算法，专为大型语言模型中的	extit{偏好优化}设计。我们从分析传统（一阶）偏好优化过程中策略模型与奖励模型的交互入手，揭示了它们的相对更新模式。基于这些发现，我们对同时扰动随机近似（SPSA）进行了调整，结合针对性的采样策略，以加速收敛。通过在文本摘要、机器翻译和对话式助手等任务上的实验，我们证明了我们的方法不仅能够持续增强奖励信号，还实现了与一阶方法相当的收敛速度。尽管在某些方面尚未超越现有最优方法，但我们的研究首次将零阶优化应用于大型语言模型的偏好优化，突破了分类任务的局限，为这一全新且尚未充分探索的研究领域奠定了基础。代码和可视化内容可在https://github.com/alessioGalatolo/VisZOPrO获取

> Fine-tuning LLMs with first-order methods like back-propagation is computationally intensive. Zeroth-Order (ZO) optimisation, using function evaluations instead of gradients, reduces memory usage but suffers from slow convergence in high-dimensional models. As a result, ZO research in LLMs has mostly focused on classification, overlooking more complex generative tasks. In this paper, we introduce ZOPrO, a novel ZO algorithm designed for \textit{Preference Optimisation} in LLMs. We begin by analysing the interplay between policy and reward models during traditional (first-order) Preference Optimisation, uncovering patterns in their relative updates. Guided by these insights, we adapt Simultaneous Perturbation Stochastic Approximation (SPSA) with a targeted sampling strategy to accelerate convergence. Through experiments on summarisation, machine translation, and conversational assistants, we demonstrate that our method consistently enhances reward signals while achieving convergence times comparable to first-order methods. While it falls short of some state-of-the-art methods, our work is the first to apply Zeroth-Order methods to Preference Optimisation in LLMs, going beyond classification tasks and paving the way for a largely unexplored research direction. Code and visualisations are available at https://github.com/alessioGalatolo/VisZOPrO

[Arxiv](https://arxiv.org/abs/2503.03460)