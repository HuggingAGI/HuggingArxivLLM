# 高效统一GPU内核实现跨硬件与精度的奇异值计算

发布时间：2025年08月08日

`其他` `科学计算` `机器学习`

> Performant Unified GPU Kernels for Portable Singular Value Computation Across Hardware and Precision

# 摘要

> 本文提出了一种基于QR算法的奇异值计算方法的可移植、GPU加速Julia实现。奇异值分解（SVD）是科学计算和机器学习中的基础工具，提供最优的低秩矩阵近似。在大规模机器学习管道（包括大型语言模型（LLMs））中，其重要性进一步提升，因为它支持低秩适应（LoRA）。实现的算法基于经典的两阶段QR降阶方法，依次将矩阵约简为带状形式和双对角形式。我们的实现利用了Julia的多重分派和元编程功能，结合GPUArrays和KernelAbstractions框架，提供了一个统一的类型和硬件无关的函数。它支持多种GPU架构和数据类型，据我们所知，这是首个支持Apple Metal GPU和半精度的GPU加速奇异值实现。在多个GPU后端和数据类型上的性能结果表明，可移植性并不以牺牲性能为代价：统一函数在矩阵规模大于1024x1024时，超越了大多数线性代数库（MAGMA、SLATE、rocSOLVER、oneMKL），并且对于大型矩阵，其性能达到了cuSOLVER的80%-90%。

> This paper presents a portable, GPU-accelerated implementation of a QR-based singular value computation algorithm in Julia. The singular value ecomposition (SVD) is a fundamental numerical tool in scientific computing and machine learning, providing optimal low-rank matrix approximations. Its importance has increased even more in large-scale machine learning pipelines, including large language models (LLMs), where it enables low-rank adaptation (LoRA). The implemented algorithm is based on the classic two-stage QR reduction, consisting of successive matrix reduction to band form and bidiagonal form. Our implementation leverages Julia's multiple dispatch and metaprogramming capabilities, integrating with the GPUArrays and KernelAbstractions frameworks to provide a unified type and hardware-agnostic function. It supports diverse GPU architectures and data types, and is, to our knowledge, the first GPU-accelerated singular value implementation to support Apple Metal GPUs and half precision. Performance results on multiple GPU backends and data types demonstrate that portability does not require sacrificing performance: the unified function outperforms most linear algebra libraries (MAGMA, SLATE, rocSOLVER, oneMKL) for matrix sizes larger than 1024x1024, and achieves 80%-90% of the performance of cuSOLVER for large matrices.

[Arxiv](https://arxiv.org/abs/2508.06339)