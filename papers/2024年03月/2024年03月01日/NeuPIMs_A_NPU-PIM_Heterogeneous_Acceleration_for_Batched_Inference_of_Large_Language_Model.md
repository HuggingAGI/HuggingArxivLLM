# NeuPIMs，为解决大型语言模型批量推理问题而生，是一种融合了NPU与PIM技术的高效异构加速方案。

发布时间：2024年03月01日

`LLM理论`

> NeuPIMs: A NPU-PIM Heterogeneous Acceleration for Batched Inference of Large Language Model

# 摘要

> 现今的Transformer架构LLMs由一系列解码器模块构成，模块内含三大核心部件——QKV生成、多头注意力机制及前馈神经网络。在批处理过程中，QKV生成与前馈网络涉及大量的矩阵-矩阵运算（GEMM），而多头注意力机制则偏向于对带宽需求高的矩阵-向量运算（GEMV）。尽管如TPU或NPU这类机器学习加速器在处理GEMM方面表现出色，但对于GEMV计算却不够高效；与此相反，内存内计算技术PIM虽在GEMV计算上占优，却不擅长处理GEMM。鉴于此，我们创新提出了一种名为NeuPIMs的异构加速系统，该系统巧妙结合了专注GEMM的经典NPU与优化GEMV的PIM设备。然而，在实现NPU与PIM的有效融合时，如何让两者针对不同内核类型实现并发操作成为一大难题。一方面，现存的PIM一般采取“区块化”运作模式，无法支持NPU与PIM的同时激活；另一方面，LLMs中GEMM与GEMV运算间的内在依赖关系限制了它们的并行处理性能。为解决这些问题，NeuPIMs在各存储单元中引入了双重行缓存设计，以便同时调度内存读写操作与PIM指令，并采用了运行时子批次交错技术，充分利用批处理并行优势，实现在单一NeuPIMs节点内部对两个独立子批次进行流水线处理。经验证明，相较于仅使用NPU方案以及简单的NPU-PIM一体化系统，NeuPIMs在吞吐量方面取得了高达2.3倍和1.6倍的显著提升。

> Modern transformer-based Large Language Models (LLMs) are constructed with a series of decoder blocks. Each block comprises three key components: (1) QKV generation, (2) multi-head attention, and (3) feed-forward networks. In batched processing, QKV generation and feed-forward networks involve compute-intensive matrix-matrix multiplications (GEMM), while multi-head attention requires bandwidth-heavy matrix-vector multiplications (GEMV). Machine learning accelerators like TPUs or NPUs are proficient in handling GEMM but are less efficient for GEMV computations. Conversely, Processing-in-Memory (PIM) technology is tailored for efficient GEMV computation, while it lacks the computational power to effectively handle GEMM. Inspired by this insight, we propose NeuPIMs, a heterogeneous accelerator-based system that jointly exploits a conventional GEMM-focused NPU and GEMV-optimized PIM devices. The main challenge in efficiently integrating NPU and PIM lies in enabling concurrent operations on both platforms, each addressing a specific kernel type. First, existing PIMs typically operate in a "blocked" mode, allowing only either NPU or PIM to be active at any given time. Second, the inherent dependencies between GEMM and GEMV in LLMs restrict their parallel processing. To tackle these challenges, NeuPIMs is equipped with dual row buffers in each bank, facilitating the simultaneous management of memory read/write operations and PIM commands. Further, NeuPIMs employs a runtime sub-batch interleaving technique to maximize concurrent execution, leveraging batch parallelism to allow two independent sub-batches to be pipelined within a single NeuPIMs node. Our evaluation demonstrates that compared to an NPU-only approach and a naïve NPU-PIM integrated system, NeuPIMs achieves 2.3$\times$ and 1.6$\times$ throughput improvement, respectively.

[Arxiv](https://arxiv.org/abs/2403.00579)