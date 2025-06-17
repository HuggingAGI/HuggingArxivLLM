# # LOP：学习最优剪枝策略，实现多语言大语言模型的高效按需扩展

发布时间：2025年06月15日

`LLM应用

摘要中讨论了结构化剪枝技术在多模态大语言模型中的应用，提出了一种新的剪枝框架LOP，以提高剪枝效率和效果。这属于LLM的应用层面的优化和改进，因此归类为LLM应用。` `人工智能` `计算机硬件`

> LOP: Learning Optimal Pruning for Efficient On-Demand MLLMs Scaling

# 摘要

> 结构化剪枝技术在多模态大语言模型（MLLMs）的部署中至关重要，尤其在从边缘设备到云服务器的各类硬件平台上。然而，现有的剪枝方法通常依赖迭代搜索来确定最优策略，这导致了巨大的计算开销。为了解决这一问题，我们提出了LOP——一种高效神经剪枝框架，能够从目标剪枝约束中学习最优策略，从而避免了传统计算密集型的搜索方法。LOP通过训练自回归神经网络（NNs）直接预测适应目标约束的分层剪枝策略，从而消除了耗时的迭代搜索。实验结果表明，LOP不仅在各项指标上超越现有最优剪枝方法，还实现了多达三个数量级的速度提升，展现出显著的优势。

> Structural pruning techniques are essential for deploying multimodal large language models (MLLMs) across various hardware platforms, from edge devices to cloud servers. However, current pruning methods typically determine optimal strategies through iterative search processes, resulting in substantial computational overhead for on-demand MLLMs adaptation. To address this challenge, we propose LOP, an efficient neural pruning framework that learns optimal pruning strategies from the target pruning constraint, eliminating the need for computationally expensive search-based methods. LOP approach trains autoregressive neural networks (NNs) to directly predict layer-wise pruning strategies adaptive to the target pruning constraint, eliminating the time-consuming iterative searches. Experimental results across multiple tasks show that LOP outperforms state-of-the-art pruning methods in various metrics while achieving up to three orders of magnitude speedup.

[Arxiv](https://arxiv.org/abs/2506.12826)