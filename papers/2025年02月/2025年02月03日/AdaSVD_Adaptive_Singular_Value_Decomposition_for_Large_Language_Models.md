# AdaSVD: 大型语言模型的自适应奇异值分解

发布时间：2025年02月03日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型（LLMs）的压缩技术，特别是通过奇异值分解（SVD）来减少内存需求。论文提出了一种新的自适应SVD压缩方法（AdaSVD），并对其进行了实验验证。这些内容属于对LLMs的理论研究和优化，因此分类为LLM理论。` `模型压缩`

> AdaSVD: Adaptive Singular Value Decomposition for Large Language Models

# 摘要

> 大型语言模型（LLMs）在NLP任务中表现出色，但其庞大的内存需求给资源受限设备的部署带来了挑战。奇异值分解（SVD）作为一种高效的LLMs压缩技术，能大幅降低内存开销。然而，现有SVD方法难以有效缓解截断误差，导致性能与原始模型存在差距。此外，统一压缩比率忽视了不同层的重要性差异。为此，我们提出了AdaSVD，一种自适应SVD压缩方法。AdaSVD通过adaComp交替更新奇异矩阵U和V^T，自适应补偿截断误差，并通过adaCR根据层的重要性分配压缩比率。实验表明，AdaSVD在多个LLM家族和评估指标上均优于现有SOTA方法，在显著减少内存需求的同时保持了卓越性能。代码和模型将在https://github.com/ZHITENGLI/AdaSVD上提供。

> Large language models (LLMs) have achieved remarkable success in natural language processing (NLP) tasks, yet their substantial memory requirements present significant challenges for deployment on resource-constrained devices. Singular Value Decomposition (SVD) has emerged as a promising compression technique for LLMs, offering considerable reductions in memory overhead. However, existing SVD-based methods often struggle to effectively mitigate the errors introduced by SVD truncation, leading to a noticeable performance gap when compared to the original models. Furthermore, applying a uniform compression ratio across all transformer layers fails to account for the varying importance of different layers. To address these challenges, we propose AdaSVD, an adaptive SVD-based LLM compression approach. Specifically, AdaSVD introduces adaComp, which adaptively compensates for SVD truncation errors by alternately updating the singular matrices U and V^T. Additionally, AdaSVD introduces adaCR, which adaptively assigns layer-specific compression ratios based on the relative importance of each layer. Extensive experiments across multiple LLM families and evaluation metrics demonstrate that AdaSVD consistently outperforms state-of-the-art (SOTA) SVD-based methods, achieving superior performance with significantly reduced memory requirements. The code and models will be available at https://github.com/ZHITENGLI/AdaSVD.

[Arxiv](https://arxiv.org/abs/2502.01403)