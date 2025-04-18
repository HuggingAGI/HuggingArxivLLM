# 支持任意低精度通用GPU计算的虚拟机在大语言模型服务中的应用

发布时间：2025年04月17日

`其他

摘要讨论了大型语言模型（LLMs）的部署优化，特别是低精度计算的改进，属于技术实现层面的优化，不属于Agent、RAG、LLM应用或LLM理论类别，因此归类为其他。` `GPU`

> A Virtual Machine for Arbitrary Low-Precision GPGPU Computation in LLM Serving

# 摘要

> 大型语言模型（LLMs）的部署对于AI应用至关重要，但需要显著的计算资源，尤其是内存带宽和计算吞吐量。低精度计算作为一种关键优化技术，能够在减少资源消耗的同时提升效率。然而，现有的低精度内核生成方法仅限于权重位宽为2的幂次，并且由于高级GPU编程抽象的存在，性能表现欠佳。这些抽象限制了关键优化，如细粒度寄存器管理和优化的内存访问模式，这些对于高效低精度计算至关重要。本文中，我们提出了一种专为通用GPU（GPGPU）计算设计的虚拟机（VM），支持任意位宽的低精度数据类型，同时保持GPU的可编程性。该虚拟机具有线程块级编程模型、分层内存空间、新颖的代数布局系统，并且全面支持多种低精度数据类型。通过自动向量化和指令选择，VM程序被编译为高效的GPU程序。大量实验表明，我们的虚拟机能够高效支持完整的低精度数据类型谱系，并在支持的类型上超越现有的先进低精度内核。与现有编译器如Triton和Ladder，以及QuantLLM和Marlin等手优化内核相比，我们的虚拟机分别实现了1.75x、2.61x、1.29x和1.03x的性能提升。


> Serving Large Language Models (LLMs) is critical for AI-powered applications but demands substantial computational resources, particularly in memory bandwidth and computational throughput. Low-precision computation has emerged as a key technique to improve efficiency while reducing resource consumption. Existing approaches for generating low-precision kernels are limited to weight bit widths that are powers of two and suffer from suboptimal performance due to high-level GPU programming abstractions. These abstractions restrict critical optimizations, such as fine-grained register management and optimized memory access patterns, which are essential for efficient low-precision computations. In this paper, we introduce a virtual machine (VM) designed for General-Purpose GPU (GPGPU) computing, enabling support for low-precision data types with arbitrary bit widths while maintaining GPU programmability. The proposed VM features a thread-block-level programming model, a hierarchical memory space, a novel algebraic layout system, and extensive support for diverse low-precision data types. VM programs are compiled into highly efficient GPU programs with automatic vectorization and instruction selection. Extensive experiments demonstrate that our VM efficiently supports a full spectrum of low-precision data types, and outperforms state-of-the-art low-precision kernels on their supported types. Compared to existing compilers like Triton and Ladder, as well as hand-optimized kernels such as QuantLLM and Marlin, our VM achieves performance improvements of 1.75x, 2.61x, 1.29x and 1.03x, respectively.

[Arxiv](https://arxiv.org/abs/2504.12984)