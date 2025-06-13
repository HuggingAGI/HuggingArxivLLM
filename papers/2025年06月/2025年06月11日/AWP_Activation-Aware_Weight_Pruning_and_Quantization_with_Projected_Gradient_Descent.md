# # AWP: 基于激活感知的权重剪枝与投影梯度下降量化技术

发布时间：2025年06月11日

`LLM理论` `边缘计算` `模型优化`

> AWP: Activation-Aware Weight Pruning and Quantization with Projected Gradient Descent

# 摘要

> 针对大型语言模型 (LLMs) 的庞大体量，我们采用量化与剪枝等模型压缩方法，尤其在边缘设备上表现突出。本研究聚焦于层后训练的量化与剪枝技术。通过建立激活感知权重剪枝与稀疏近似问题的关联，并借鉴迭代硬阈值算法 (IHT) 的成功经验，我们提出了一种基于投影梯度下降的统一方法 (AWP)，用于实现激活感知权重剪枝与量化。实验结果证实，AWP 在 LLM 剪枝与量化方面超越现有最优方法。此外，我们还提供了该方法在剪枝任务中的理论收敛性保证。

> To address the enormous size of Large Language Models (LLMs), model compression methods, such as quantization and pruning, are often deployed, especially on edge devices. In this work, we focus on layer-wise post-training quantization and pruning. Drawing connections between activation-aware weight pruning and sparse approximation problems, and motivated by the success of Iterative Hard Thresholding (IHT), we propose a unified method for Activation-aware Weight pruning and quantization via Projected gradient descent (AWP). Our experiments demonstrate that AWP outperforms state-of-the-art LLM pruning and quantization methods. Theoretical convergence guarantees of the proposed method for pruning are also provided.

[Arxiv](https://arxiv.org/abs/2506.10205)