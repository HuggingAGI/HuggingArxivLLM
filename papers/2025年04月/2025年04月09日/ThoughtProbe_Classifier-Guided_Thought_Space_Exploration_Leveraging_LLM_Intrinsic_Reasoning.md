# ThoughtProbe：基于分类器引导的思维空间探索，通过利用大型语言模型的内在推理能力实现.

发布时间：2025年04月09日

`LLM理论` `大型语言模型`

> ThoughtProbe: Classifier-Guided Thought Space Exploration Leveraging LLM Intrinsic Reasoning

# 摘要

> 预训练的大型语言模型（LLMs）展现出了内在推理能力，这些能力在扩展响应空间时自然显现。然而，关于这些能力的神经表征机制及其最优利用方法仍不明确。本研究发现，简单的线性分类器能够有效识别LLMs激活空间中的推理能力，尤其在特定表征类型和网络层中表现突出。基于此，我们提出了一种分类器引导的搜索框架，用于策略性地探索树状响应空间。在每个节点扩展中，分类器作为评分和排序机制，通过识别并优先选择更具深度的推理方向，高效分配计算资源。完成树状扩展后，我们从所有分支中收集答案，形成候选答案池。我们还提出了一种基于分支聚合的选择方法，通过对所有支持分支的思考性得分进行聚合，从而在候选池中识别出最优答案。实验结果表明，我们的框架不仅全面覆盖了有效的推理链，还显著提升了多个算术推理基准测试的表现。

> Pre-trained large language models (LLMs) have been demonstrated to possess intrinsic reasoning capabilities that can emerge naturally when expanding the response space. However, the neural representation mechanisms underlying these intrinsic capabilities and approaches for their optimal utilization remain inadequately understood. In this work, we make the key discovery that a simple linear classifier can effectively detect intrinsic reasoning capabilities in LLMs' activation space, particularly within specific representation types and network layers. Based on this finding, we propose a classifier-guided search framework that strategically explore a tree-structured response space. In each node expansion, the classifier serves as a scoring and ranking mechanism that efficiently allocates computational resources by identifying and prioritizing more thoughtful reasoning directions for continuation. After completing the tree expansion, we collect answers from all branches to form a candidate answer pool. We propose a branch-aggregation selection method that marginalizes over all supporting branches by aggregating their thoughtfulness scores, thereby identifying the optimal answer from the pool. Experimental results show that our framework's comprehensive exploration not only covers valid reasoning chains but also effectively identifies them, achieving significant improvements across multiple arithmetic reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2504.06650)