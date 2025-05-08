# 分组序列排列旋转：优化量化过程中的旋转变换以实现免费量化

发布时间：2025年05月02日

`LLM理论

摘要讨论了大型语言模型（LLMs）在部署时的计算成本问题，特别是后训练量化（PTQ）技术。论文提出了一种新的方法，利用Walsh-Hadamard变换和分组sequency排列旋转（GSR）来改进旋转矩阵，从而降低量化误差并提升模型性能。这属于模型优化和理论层面的研究，因此归类为LLM理论。` `量化技术`

> Grouped Sequency-arranged Rotation: Optimizing Rotation Transformation for Quantization for Free

# 摘要

> 大型语言模型 (LLMs) 部署时面临计算成本高昂的挑战，而后训练量化 (PTQ) 提供了一种解决方案。然而，现有基于旋转的方法在处理 2 位等极低位宽时效果不佳。我们提出了一种无需训练的新方法，用于构建改进的旋转矩阵，以克服现有方法的局限性。我们的主要贡献包括利用基于 Walsh-Hadamard 变换的 sequency 顺序排列，将相似的频率成分聚类，从而显著降低量化误差并提升性能。此外，我们提出了一种基于分块对角矩阵的分组 sequency 排列旋转 (GSR)，通过使用较小的 Walsh 块有效隔离异常值的影响，并在无需任何训练的情况下实现与优化方法相当的性能。我们的方法在推理任务和 WikiText-2 数据集上的困惑度 (PPL) 评分中表现出稳健的性能。即使在现有学习旋转技术的基础上应用，我们的方法也能进一步提升结果。

> Large Language Models (LLMs) face deployment challenges due to high computational costs, and while Post-Training Quantization (PTQ) offers a solution, existing rotation-based methods struggle at very low bit-widths like 2-bit. We introduce a novel, training-free approach to construct an improved rotation matrix, addressing the limitations of current methods. The key contributions include leveraging the Walsh-Hadamard transform with sequency ordering, which clusters similar frequency components to reduce quantization error compared to standard Hadamard matrices, significantly improving performance. Furthermore, we propose a Grouped Sequency-arranged Rotation (GSR) using block-diagonal matrices with smaller Walsh blocks, effectively isolating outlier impacts and achieving performance comparable to optimization-based methods without requiring any training. Our method demonstrates robust performance on reasoning tasks and Perplexity (PPL) score on WikiText-2. Our method also enhances results even when applied over existing learned rotation techniques.

[Arxiv](https://arxiv.org/abs/2505.03810)