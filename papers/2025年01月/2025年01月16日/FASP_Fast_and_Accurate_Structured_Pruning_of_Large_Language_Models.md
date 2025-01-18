# FASP: 大型语言模型的高效精准结构化剪枝

发布时间：2025年01月16日

`LLM理论

**理由**：这篇论文主要讨论的是如何通过结构化剪枝来优化大型语言模型（LLMs）的计算和内存需求，属于对LLMs的理论研究和优化方法的探讨，因此归类为LLM理论。` `模型压缩`

> FASP: Fast and Accurate Structured Pruning of Large Language Models

# 摘要

> 随着大型语言模型（LLMs）规模的迅速扩大，其计算和内存需求也大幅增加，这对资源受限设备的高效部署提出了挑战。结构化剪枝作为一种有效的模型压缩方法，能够在保持性能的同时减少这些需求。本文提出了一种新颖的LLMs结构化剪枝框架——FASP（快速准确的结构化剪枝），该框架兼顾速度与精度。FASP采用了一种独特的剪枝结构，将连续层相互连接，能够在移除某一层列的同时，消除前一层中相应的行，且不会带来额外的性能损失。受Wanda启发的剪枝指标计算高效，能够有效选择剪枝组件。此外，我们还提出了一种恢复机制，通过调整剪枝后的剩余权重来提升模型的保真度。我们在OPT和LLaMA模型系列上对FASP进行了评估，结果显示其在下游任务的困惑度和准确性上均优于现有方法。FASP在单个NVIDIA RTX 4090 GPU上实现了显著的加速，例如OPT-125M模型仅需17秒，LLaMA-30B模型仅需15分钟即可完成剪枝，使其成为优化LLMs的实用解决方案。

> The rapid increase in the size of large language models (LLMs) has significantly escalated their computational and memory demands, posing challenges for efficient deployment, especially on resource-constrained devices. Structured pruning has emerged as an effective model compression method that can reduce these demands while preserving performance. In this paper, we introduce FASP (Fast and Accurate Structured Pruning), a novel structured pruning framework for LLMs that emphasizes both speed and accuracy. FASP employs a distinctive pruning structure that interlinks sequential layers, allowing for the removal of columns in one layer while simultaneously eliminating corresponding rows in the preceding layer without incurring additional performance loss. The pruning metric, inspired by Wanda, is computationally efficient and effectively selects components to prune. Additionally, we propose a restoration mechanism that enhances model fidelity by adjusting the remaining weights post-pruning. We evaluate FASP on the OPT and LLaMA model families, demonstrating superior performance in terms of perplexity and accuracy on downstream tasks compared to state-of-the-art methods. Our approach achieves significant speed-ups, pruning models such as OPT-125M in 17 seconds and LLaMA-30B in 15 minutes on a single NVIDIA RTX 4090 GPU, making it a highly practical solution for optimizing LLMs.

[Arxiv](https://arxiv.org/abs/2501.09412)