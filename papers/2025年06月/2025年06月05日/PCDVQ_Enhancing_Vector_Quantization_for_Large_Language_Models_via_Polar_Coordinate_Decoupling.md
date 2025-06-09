# # PCDVQ：通过极坐标解耦提升大型语言模型的向量量化

发布时间：2025年06月05日

`LLM应用` `边缘计算` `模型优化`

> PCDVQ: Enhancing Vector Quantization for Large Language Models via Polar Coordinate Decoupling

# 摘要

> 大语言模型（LLMs）在边缘部署中面临巨大挑战，主要源于其庞大的参数规模。向量量化（VQ）作为一种基于聚类的量化方法，因其极低的比特率（甚至2比特）和显著的精度而成为解决这一问题的普遍方案。由于向量在数学和物理中具有方向和大小两个属性，现有的VQ研究通常采用耦合方式对它们进行量化。然而，我们发现方向对量化表现出显著更高的敏感度，相比之下，大小的敏感度较低。例如，分别对LLaMA-2-7B权重向量的方向和大小进行聚类后，零样本任务的精度下降分别为【数学公式】46.5%和【数学公式】2.3%。这一差距甚至会随着聚类中心的减少而扩大。此外，欧氏距离作为当前VQ工作中衡量向量相似性的常见指标，更侧重于减少大小误差。这一特性与上述发现相悖，不可避免地导致更大的量化误差。针对这些问题，本文提出了一种名为极坐标解耦向量量化（PCDVQ）的有效且高效的VQ框架，包含两个关键模块：1）极坐标解耦（PCD），将向量转换为极坐标表示，并对方向和大小参数进行独立量化。2）分布对齐码本构建（DACC），根据源分布优化方向和大小码本。实验结果表明，PCDVQ在2比特级别下，零样本任务的准确率比基线方法至少高出【数学公式】1.5%，成功为高精度且高度压缩的大语言模型开辟了新范式。

> Large Language Models (LLMs) face significant challenges in edge deployment due to their massive parameter scale. Vector Quantization (VQ), a clustering-based quantization method, serves as a prevalent solution to this issue for its extremely low-bit (even at 2-bit) and considerable accuracy. Since a vector is a quantity in mathematics and physics that has both direction and magnitude, existing VQ works typically quantize them in a coupled manner. However, we find that direction exhibits significantly greater sensitivity to quantization compared to the magnitude. For instance, when separately clustering the directions and magnitudes of weight vectors in LLaMA-2-7B, the accuracy drop of zero-shot tasks are 46.5\% and 2.3\%, respectively. This gap even increases with the reduction of clustering centers. Further, Euclidean distance, a common metric to access vector similarities in current VQ works, places greater emphasis on reducing the magnitude error. This property is contrary to the above finding, unavoidably leading to larger quantization errors. To these ends, this paper proposes Polar Coordinate Decoupled Vector Quantization (PCDVQ), an effective and efficient VQ framework consisting of two key modules: 1) Polar Coordinate Decoupling (PCD), which transforms vectors into their polar coordinate representations and perform independent quantization of the direction and magnitude parameters.2) Distribution Aligned Codebook Construction (DACC), which optimizes the direction and magnitude codebooks in accordance with the source distribution. Experimental results show that PCDVQ outperforms baseline methods at 2-bit level by at least 1.5\% zero-shot accuracy, establishing a novel paradigm for accurate and highly compressed LLMs.

[Arxiv](https://arxiv.org/abs/2506.05432)