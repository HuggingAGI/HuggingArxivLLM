# 助力向量架构在机器学习中的应用：专为矩阵乘法设计的CAMP架构

发布时间：2025年04月10日

`其他` `计算机体系结构` `机器学习`

> Empowering Vector Architectures for ML: The CAMP Architecture for Matrix Multiplication

# 摘要

> 本研究提出了一种名为笛卡尔累积矩阵流水线 (CAMP) 的创新架构，旨在提升向量架构 (VAs) 和单指令多数据 (SIMD) 单元中矩阵乘法的性能。CAMP 优化了量化神经网络 (QNNs) 的处理效率。矩阵乘法是机器学习应用的基石，其量化版本因其更高效的运算而日益受欢迎。然而，现有的向量架构和 SIMD 支持单元在高效处理这些量化格式方面仍面临挑战。在本研究中，我们提出了 CAMP，这是一种简单而有效的架构，采用了混合乘法器。CAMP 架构显著提升了向量架构在处理量化数据方面的性能，使得矩阵乘法在多个平台上能够更高效地执行，特别针对 ARMv8 可扩展向量扩展 (SVE) 和边缘 RISC-V SIMD 架构。除了提升吞吐量，CAMP 的架构设计还促进了能效，使其成为低功耗应用的理想解决方案。在一系列大型语言模型 (LLMs) 和卷积神经网络 (CNNs) 上的评估表明，采用所提出的微架构进行矩阵乘法操作，与 ARM A64FX 核心和基于 RISC-V 的边缘片上系统 (SoC) 相比，性能提升高达 17 倍和 23 倍。此外，使用 Synopsys 工具对 CAMP 微架构进行综合和布线（PnR），针对 ARM TSMC 7nm（适用于 A64FX）和 GlobalFoundries 22nm（适用于 RISC-V SoC）进行设计，与基线设计相比，仅增加了 1% 和 4% 的面积开销。

> This study presents the Cartesian Accumulative Matrix Pipeline (CAMP) architecture, a novel approach designed to enhance matrix multiplication in Vector Architectures (VAs) and Single Instruction Multiple Data (SIMD) units. CAMP improves the processing efficiency of Quantized Neural Networks (QNNs). Matrix multiplication is a cornerstone of machine learning applications, and its quantized versions are increasingly popular for more efficient operations. Unfortunately, existing VAs and SIMD-support units struggle to efficiently handle these quantized formats. In this work, we propose CAMP, a simple yet effective architecture that leverages a hybrid multiplier. The CAMP architecture significantly advances the performance of vector architectures in handling quantized data, enabling more efficient execution of matrix multiplication across various platforms, specifically targeting the ARMv8 Scalable Vector Extension (SVE) and edge RISC-V SIMD-based architectures. In addition to increasing throughput, CAMP's architectural design also contributes to energy efficiency, making it an effective solution for low-power applications. Evaluations on a range of Large Language Models (LLMs) and Convolutional Neural Networks (CNNs) demonstrate that matrix multiplication operations using the proposed micro-architecture achieve up to 17$\times$ and 23$\times$ performance improvements compared to their respective baselines, the ARM A64FX core and a RISC-V-based edge System-on-Chip (SoC). Furthermore, synthesis and place-and-route (PnR) of the CAMP micro-architecture using Synopsys tools -- targeting ARM TSMC 7nm for A64FX and GlobalFoundries 22nm for the RISC-V SoC -- add only 1\% and 4\% area overhead, respectively, compared to the baseline designs.

[Arxiv](https://arxiv.org/abs/2504.08137)