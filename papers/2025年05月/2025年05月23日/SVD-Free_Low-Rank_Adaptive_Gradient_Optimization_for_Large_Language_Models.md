# 面向大型语言模型的无奇异值分解低秩自适应梯度优化

发布时间：2025年05月23日

`LLM理论` `大型语言模型`

> SVD-Free Low-Rank Adaptive Gradient Optimization for Large Language Models

# 摘要

> 低秩优化在大型语言模型（LLMs）的训练中展现出巨大潜力，通过将学习限制在低维空间，从而有效减少自适应优化器的内存占用。传统方法通常借助奇异值分解（SVD）来投影线性层的梯度。然而，对大型模型的每一层单独应用基于SVD的方法不仅计算成本高昂，还会因存储投影矩阵而增加额外的内存负担。针对这一问题，我们提出了一种计算高效且概念简洁的两步方法，用于近似基于SVD的梯度投影到低维空间。首先，我们利用离散余弦变换（DCT）的预定义正交矩阵构建完整的正交基。其次，我们根据每个层梯度与基的对齐程度，自适应地选择基列。在我们的方法中，每个投影矩阵通过一次矩阵乘法和一个轻量级的排序步骤来确定最相关的基向量获得。由于正交基是预定义的，因此它们只需在训练开始时计算一次。在训练过程中，我们仅存储所选列的索引，从而避免了为每一层存储完整的投影矩阵。通过在预训练和微调任务上的数值实验，我们验证了我们的双重策略在近似最优低秩投影方面的有效性。与昂贵的基于SVD的方法相比，我们的方法不仅性能相当，还实现了更快的运行速度和更低的内存使用。

> Low-rank optimization has emerged as a promising direction in training large language models (LLMs) to reduce the memory usage of adaptive optimizers by constraining learning to a lower-dimensional space. Prior work typically projects gradients of linear layers using approaches based on Singular Value Decomposition (SVD). However, applying SVD-based procedures individually to each layer in large models is computationally expensive and incurs additional memory costs due to storing the projection matrices. In this work, we propose a computationally efficient and conceptually simple two-step procedure to approximate SVD-based gradient projections into lower-dimensional spaces. First, we construct a complete orthogonal basis using predefined orthogonal matrices of the Discrete Cosine Transform (DCT). Second, we adaptively select basis columns based on their alignment with the gradient of each layer. Each projection matrix in our method is obtained via a single matrix multiplication followed by a lightweight sorting step to identify the most relevant basis vectors. Due to the predefined nature of the orthogonal bases, they are computed once at the start of training. During training, we store only the indices of the selected columns, avoiding the need to store full projection matrices for each layer. Our numerical experiments on both pre-training and fine-tuning tasks demonstrate the effectiveness of our dual strategy in approximating optimal low-rank projections, matching the performance of costly SVD-based methods while achieving faster runtime and reduced memory usage.

[Arxiv](https://arxiv.org/abs/2505.17967)