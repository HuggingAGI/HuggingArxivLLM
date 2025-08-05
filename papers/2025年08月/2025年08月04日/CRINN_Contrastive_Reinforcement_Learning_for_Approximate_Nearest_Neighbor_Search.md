# CRINN：一种基于对比强化学习的近似最近邻搜索方法

发布时间：2025年08月04日

`RAG` `算法优化`

> CRINN: Contrastive Reinforcement Learning for Approximate Nearest Neighbor Search

# 摘要

> # 摘要
近似最近邻搜索（ANNS）算法在近期的AI应用中变得至关重要，特别是在检索增强生成（RAG）和基于智能体的LLM应用中。本文中，我们提出了CRINN，这是一种全新的ANNS算法范式。CRINN将ANNS优化视为一个强化学习问题，其中执行速度作为奖励信号。这种方法能够自动生成越来越快的ANNS实现，同时保持准确性约束。

我们的实验评估在六个广泛使用的NNS基准数据集上验证了CRINN的有效性。与最先进的开源ANNS算法相比，CRINN在其中三个数据集（GIST-960-Euclidean、MNIST-784-Euclidean 和 GloVe-25-angular）上实现了最佳性能，并在另外两个数据集（SIFT-128-Euclidean 和 GloVe-25-angular）上并列第一。CRINN的成功影响远不止于ANNS优化：它验证了增强强化学习的LLMs可以作为一个有效的工具，用于自动化需要专业知识和劳动密集型手动调整的复杂算法优化。代码可在https://github.com/deepreinforce-ai/CRINN上找到。

> Approximate nearest-neighbor search (ANNS) algorithms have become increasingly critical for recent AI applications, particularly in retrieval-augmented generation (RAG) and agent-based LLM applications. In this paper, we present CRINN, a new paradigm for ANNS algorithms. CRINN treats ANNS optimization as a reinforcement learning problem where execution speed serves as the reward signal. This approach enables the automatic generation of progressively faster ANNS implementations while maintaining accuracy constraints. Our experimental evaluation demonstrates CRINN's effectiveness across six widely-used NNS benchmark datasets. When compared against state-of-the-art open-source ANNS algorithms, CRINN achieves best performance on three of them (GIST-960-Euclidean, MNIST-784-Euclidean, and GloVe-25-angular), and tied for first place on two of them (SIFT-128-Euclidean and GloVe-25-angular). The implications of CRINN's success reach well beyond ANNS optimization: It validates that LLMs augmented with reinforcement learning can function as an effective tool for automating sophisticated algorithmic optimizations that demand specialized knowledge and labor-intensive manual refinement.Code can be found at https://github.com/deepreinforce-ai/CRINN

[Arxiv](https://arxiv.org/abs/2508.02091)