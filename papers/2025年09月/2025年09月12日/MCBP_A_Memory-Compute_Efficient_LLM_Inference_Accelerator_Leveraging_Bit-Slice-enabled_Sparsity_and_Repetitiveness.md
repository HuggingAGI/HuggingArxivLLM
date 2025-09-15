# MCBP：一种借助位切片稀疏性与重复性的存储-计算高效大语言模型推理加速器

发布时间：2025年09月12日

`LLM应用` `基础理论`

> MCBP: A Memory-Compute Efficient LLM Inference Accelerator Leveraging Bit-Slice-enabled Sparsity and Repetitiveness

# 摘要

> 大型语言模型（LLMs）在推理时面临严重的延迟瓶颈，受限于GEMM运算、权重访问及KV缓存访问的效率问题，尤其在实时场景下更为突出。因此亟需一种兼具计算与内存效率的通用加速器。然而现有Transformer加速器多聚焦于值级处理，难以兼顾计算与内存的协同优化，错失了细粒度的优化空间。本文提出MCBP——一种基于位粒度的计算-内存高效算法-硬件协同设计，通过挖掘位切片（BS）的重复性与稀疏性来加速LLM推理。MCBP的三大核心创新包括：1）位切片重复性计算缩减（BRCR）：利用位切片向量间的隐藏冗余消除GEMM冗余计算；2）位切片稀疏性双态编码（BSTC）：借助高阶位切片权重的显著稀疏性降低权重访问开销；3）位粒度渐进式预测（BGPP）：通过基于提前终止的位粒度预测减少KV缓存访问。这些技术在定制加速器架构的支持下，有效缓解了GEMM运算、权重访问及KV缓存访问的压力。26项基准测试结果显示，MCBP相比Nvidia A100 GPU实现了9.43倍的速度提升和31.1倍的能效优化；与现有最优Transformer加速器相比，其能耗较Spatten、FACT和SOFA分别降低35倍、5.2倍和3.2倍。

> Large language models (LLMs) face significant inference latency due to inefficiencies in GEMM operations, weight access, and KV cache access, especially in real-time scenarios. This highlights the need for a versatile compute-memory efficient accelerator. Unfortunately, existing Transformer accelerators struggle to address both aspects simultaneously, as they focus on value-level processing, missing fine-grained opportunities to optimize computation and memory collaboratively. This paper introduces MCBP, a bit-grained compute-memory efficient algorithm-hardware co-design that leverages bit-slice (BS) enabled repetitiveness and sparsity to accelerate LLM inference. MCBP features three key innovations: 1) BS-repetitiveness-enabled computation reduction (BRCR), which eliminates redundant GEMM computations via leveraging redundancy hidden among BS vectors; 2) BS-sparsity-enabled two-state coding (BSTC), which reduces weight access via exploiting significant sparsity in high-order bit-slice weight; 3) Bit-grained progressive prediction (BGPP), which reduces KV cache access by leveraging early-termination-based bit-grained prediction. These techniques, supported by custom accelerator designs, effectively alleviate the burden in GEMM, weight access, and KV cache access. Extensive experiments on 26 benchmarks show that MCBP achieves 9.43x speed up and 31.1x higher energy efficiency than Nvidia A100 GPU. Compared to SOTA Transformer accelerators, MCBP achieves 35x, 5.2x and 3.2x energy saving than Spatten, FACT and SOFA, respectively.

[Arxiv](https://arxiv.org/abs/2509.10372)