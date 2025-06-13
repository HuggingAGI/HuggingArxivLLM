# # ClusterUCB：用于LLMs定向微调的高效梯度数据选择方法

发布时间：2025年06月11日

`LLM应用

理由：这篇论文探讨了在监督微调过程中优化数据选择的方法，属于大型语言模型的应用层面优化，因此归类为LLM应用。` `机器学习`

> ClusterUCB: Efficient Gradient-Based Data Selection for Targeted Fine-Tuning of LLMs

# 摘要

> 基于梯度的数据影响近似方法在大型语言模型的监督微调中被用于选择有用的数据样本。然而，微调过程中计算梯度所需的资源消耗使其难以在实际中应用。本文提出了一种结合聚类和改进Upper Confidence Bound (UCB)算法的高效基于梯度的数据选择框架。基于相似梯度特征的数据样本具有相似影响的直觉，我们首先对训练数据池进行聚类。然后，我们将跨集群的数据选择建模为受计算预算约束的分配问题，并采用多臂老虎机模型来解决。通过改进的UCB算法，在迭代采样过程中记录历史数据影响信息以直接估计各集群分布，并采用冷启动策略平衡探索与开发。实验结果表明，我们的ClusterUCB框架在实现与原始方法相当效果的同时，大幅降低了计算消耗。

> Gradient-based data influence approximation has been leveraged to select useful data samples in the supervised fine-tuning of large language models. However, the computation of gradients throughout the fine-tuning process requires too many resources to be feasible in practice. In this paper, we propose an efficient gradient-based data selection framework with clustering and a modified Upper Confidence Bound (UCB) algorithm. Based on the intuition that data samples with similar gradient features will have similar influences, we first perform clustering on the training data pool. Then, we frame the inter-cluster data selection as a constrained computing budget allocation problem and consider it a multi-armed bandit problem. A modified UCB algorithm is leveraged to solve this problem. Specifically, during the iterative sampling process, historical data influence information is recorded to directly estimate the distributions of each cluster, and a cold start is adopted to balance exploration and exploitation. Experimental results on various benchmarks show that our proposed framework, ClusterUCB, can achieve comparable results to the original gradient-based data selection methods while greatly reducing computing consumption.

[Arxiv](https://arxiv.org/abs/2506.10288)