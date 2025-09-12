# HD-MoE：面向混合专家大型语言模型（LLMs）的混合动态并行——基于3D近内存处理

发布时间：2025年09月11日

`其他` `基础理论`

> HD-MoE: Hybrid and Dynamic Parallelism for Mixture-of-Expert LLMs with 3D Near-Memory Processing

# 摘要

> 采用混合专家（MoE）架构的大型语言模型（LLMs）在降低计算成本的同时，性能更上一层楼，但也带来了更高的内存容量和带宽需求。近内存处理（NMP）加速器通过混合键合技术将内存直接堆叠于计算单元，凭借高带宽与高能效优势，成为MoE模型的理想架构之选。然而，NMP加速器由分布式内存与计算单元构成，MoE计算的映射方式直接决定LLM推理效率。现有的并行映射策略——张量并行（TP）与专家并行（EP）——要么通信成本高昂，要么计算利用率失衡，最终造成效率不佳。而MoE LLMs的动态路由机制更是让这一效率难题雪上加霜。为此，本文提出HD-MoE，旨在自动优化NMP加速器上的MoE并行计算。HD-MoE融合离线自动混合并行映射算法与在线动态调度策略，既能降低通信成本，又能最大化计算利用率。实验结果显示，HD-MoE较TP提速1.1-1.8倍，较EP提速1.1-1.5倍，对比采用计算平衡并行策略的基线混合TP-EP方案也有1.0-1.4倍的加速效果。

> Large Language Models (LLMs) with Mixture-of-Expert (MoE) architectures achieve superior model performance with reduced computation costs, but at the cost of high memory capacity and bandwidth requirements. Near-Memory Processing (NMP) accelerators that stack memory directly on the compute through hybrid bonding have demonstrated high bandwidth with high energy efficiency, becoming a promising architecture for MoE models. However, as NMP accelerators comprise distributed memory and computation, how to map the MoE computation directly determines the LLM inference efficiency. Existing parallel mapping strategies, including Tensor Parallelism (TP) and Expert Parallelism (EP), suffer from either high communication costs or unbalanced computation utilization, leading to inferior efficiency. The dynamic routing mechanism of MoE LLMs further aggravates the efficiency challenges. Therefore, in this paper, we propose HD-MoE to automatically optimize the MoE parallel computation across an NMP accelerator. HD-MoE features an offline automatic hybrid parallel mapping algorithm and an online dynamic scheduling strategy to reduce the communication costs while maximizing the computation utilization. With extensive experimental results, we demonstrate that HD-MoE achieves a speedup ranging from 1.1x to 1.8x over TP, 1.1x to 1.5x over EP, and 1.0x to 1.4x over the baseline Hybrid TP-EP with Compute-Balanced parallelism strategies.

[Arxiv](https://arxiv.org/abs/2509.09420)