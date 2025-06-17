# ROSAQ: 一种基于旋转的显著性感知权重量化方法，助力高效压缩大型语言模型

发布时间：2025年06月16日

`LLM应用` `人工智能` `计算机科学`

> ROSAQ: Rotation-based Saliency-Aware Weight Quantization for Efficiently Compressing Large Language Models

# 摘要

> 量化技术作为一种有效降低大型语言模型 (LLMs) 内存需求的方法，受到广泛研究，同时它还有可能提升延迟时间。我们利用 transformer 的旋转不变性这一特性，提出了基于旋转的显著性感知权重量化方法 (ROSAQ)。该方法在投影特征空间中识别显著通道，而不是在原始特征空间中，其中投影后的“主要”维度自然被视为“显著”特征。所提出的 ROSAQ 包括三个部分：1）基于 PCA 的投影，首先在标定数据集上进行主成分分析 (PCA)，然后通过 PCA 投影进行转换；2）显著通道识别，选择对应于 K 个最大特征值的维度作为显著通道；3）混合精度的显著性感知量化，使用 FP16 表示显著维度，使用 INT3/4 表示其他维度。实验结果表明，ROSAQ 在性能上优于基于原始特征空间的显著性感知量化和其他现有的量化方法。通过内核融合，ROSAQ 在生成 256 个 token（批大小为 64）时，与 FP16 实现相比，速度提升了约 2.3 倍。

> Quantization has been widely studied as an effective technique for reducing the memory requirement of large language models (LLMs), potentially improving the latency time as well. Utilizing the characteristic of rotational invariance of transformer, we propose the rotation-based saliency-aware weight quantization (ROSAQ), which identifies salient channels in the projection feature space, not in the original feature space, where the projected "principal" dimensions are naturally considered as "salient" features. The proposed ROSAQ consists of 1) PCA-based projection, which first performs principal component analysis (PCA) on a calibration set and transforms via the PCA projection, 2) Salient channel dentification, which selects dimensions corresponding to the K-largest eigenvalues as salient channels, and 3) Saliency-aware quantization with mixed-precision, which uses FP16 for salient dimensions and INT3/4 for other dimensions. Experiment results show that ROSAQ shows improvements over the baseline saliency-aware quantization on the original feature space and other existing quantization methods. With kernel fusion, ROSAQ presents about 2.3x speed up over FP16 implementation in generating 256 tokens with a batch size of 64.

[Arxiv](https://arxiv.org/abs/2506.13472)