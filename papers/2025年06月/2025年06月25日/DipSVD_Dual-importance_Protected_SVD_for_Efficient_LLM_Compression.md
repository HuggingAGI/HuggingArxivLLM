# DipSVD：一种通过双重要性保护的奇异值分解实现高效大语言模型压缩的方法

发布时间：2025年06月25日

`LLM应用` `机器学习` `人工智能`

> DipSVD: Dual-importance Protected SVD for Efficient LLM Compression

# 摘要

> 面对大型语言模型（LLMs）日益增长的计算需求和部署成本，研究者们提出了多种压缩方法。与量化和不规则剪枝相比，SVD压缩凭借其出色的硬件兼容性和理论保障脱颖而出。然而，现有的基于SVD的方法仅关注原始矩阵与压缩矩阵的整体差异，却忽视了对矩阵内关键组件的保护，这导致压缩模型性能欠佳。针对这一问题，本文提出了一种双层重要性保护机制，以提升基于SVD的压缩方法：(1) 局部重要性保护：通过通道加权的数据白化技术，保留每个权重矩阵中最重要的奇异向量；(2) 全局重要性保护：通过启发式或优化方法，使不重要的层承担更大的压缩负担，从而最大限度地减少压缩对关键层的影响。大量实验结果表明，DipSVD在多个基准测试中超越了现有的基于SVD的压缩方法，尤其在高压缩比下实现了更优的模型性能。

> The ever-increasing computational demands and deployment costs of large language models (LLMs) have spurred numerous compressing methods. Compared to quantization and unstructured pruning, SVD compression offers superior hardware compatibility and theoretical guarantees. However, existing SVD-based methods focus on the overall discrepancy between the original and compressed matrices while overlooking the protection of critical components within the matrix, which leads to inferior performance in the compressed models. This paper proposes a dual-level importance protection mechanism to enhance SVD-based compression methods: (1) local importance protection: preserving the most critical singular vectors within each weight matrix through channel-weighted data whitening; and (2) global importance protection: enabling less important layers to bear a greater portion of the compression burden through either a heuristic or optimization-based approach, thereby minimizing the impact of compression on critical layers. Extensive experiments demonstrate that DipSVD outperforms existing SVD-based compression approaches across multiple benchmarks, achieving superior model performance especially at high model compression ratios.

[Arxiv](https://arxiv.org/abs/2506.20353)