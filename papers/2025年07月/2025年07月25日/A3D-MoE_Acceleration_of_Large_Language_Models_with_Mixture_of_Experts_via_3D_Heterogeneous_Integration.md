# # A3D-MoE: 利用三维异构集成技术加速大型语言模型的专家混合模型
A3D-MoE: 通过三维异构集成加速大型语言模型的专家混合模型

发布时间：2025年07月25日

`LLM应用

摘要讨论了大型语言模型（LLMs）的推理效率问题，并提出了一种名为A3D-MoE的系统来优化基于MoE的LLMs的推理过程。该系统通过硬件架构和调度策略的优化，显著提升了性能和能效。这些改进直接针对LLMs的实际应用，因此属于LLM应用类别。` `硬件架构` `计算机体系结构`

> A3D-MoE: Acceleration of Large Language Models with Mixture of Experts via 3D Heterogeneous Integration

# 摘要

> 传统大型语言模型（LLMs）拥有庞大的参数量，从数十GB到数TB不等，这使得推理过程能耗极高且成本昂贵，因为在计算过程中需要将所有权重加载到片上处理单元。近期，专家混合模型（MoE）架构作为一种高效替代方案应运而生，承诺通过减少每令牌激活的权重数量实现高效推理。然而，基于MoE的细粒度LLMs面临几个挑战：1) 运行时的可变负载导致任意GEMV-GEMM比率，从而降低硬件利用率；2) 传统的基于MoE的LLM服务调度无法将注意力操作与MoE操作融合，导致延迟增加和硬件利用率下降；3) 尽管比传统LLMs更高效，但从DRAM加载专家仍会消耗大量能源并占用大量DRAM带宽。

针对这些挑战，我们提出以下解决方案：1) A3D-MoE，一种采用最新垂直集成技术的3D异质集成系统，显著提升内存带宽同时降低片上网络（NoC）开销和能耗；2) 一种3D自适应GEMV-GEMM比率数列阵列，结合V-Cache高效数据复用和新颖的统一3D数据流，解决由不同负载引起的任意GEMV-GEMM比率导致的硬件利用率降低问题；3) 一种硬件资源感知的操作融合调度器，将注意力操作与MoE操作融合，提升硬件性能；4) 基于MoE评分感知的HBM访问减少机制，通过奇偶专家放置进一步降低DRAM访问次数和带宽需求。

我们的评估结果显示，A3D-MoE带来了显著的性能提升，延迟降低了1.8倍至2倍，能耗减少了2倍至4倍，吞吐量提升了1.44倍至1.8倍，相较于现有最优方案表现更佳。


> Conventional large language models (LLMs) are equipped with dozens of GB to TB of model parameters, making inference highly energy-intensive and costly as all the weights need to be loaded to onboard processing elements during computation. Recently, the Mixture-of-Experts (MoE) architecture has emerged as an efficient alternative, promising efficient inference with less activated weights per token. Nevertheless, fine-grained MoE-based LLMs face several challenges: 1) Variable workloads during runtime create arbitrary GEMV-GEMM ratios that reduce hardware utilization, 2) Traditional MoE-based scheduling for LLM serving cannot fuse attention operations with MoE operations, leading to increased latency and decreased hardware utilization, and 3) Despite being more efficient than conventional LLMs, loading experts from DRAM still consumes significant energy and requires substantial DRAM bandwidth. Addressing these challenges, we propose: 1) A3D-MoE, a 3D Heterogeneous Integration system that employs state-of-the-art vertical integration technology to significantly enhance memory bandwidth while reducing Network-on-Chip (NoC) overhead and energy consumption. 2) A 3D-Adaptive GEMV-GEMM-ratio systolic array with V-Cache efficient data reuse and a novel unified 3D dataflow to solve the problem of reduced hardware utilization caused by arbitrary GEMV-GEMM ratios from different workloads, 3) A Hardware resource-aware operation fusion scheduler that fuses attention operations with MoE operations to enhance hardware performance, and 4) MoE Score-Aware HBM access reduction with even-odd expert placement that reduces DRAM access and bandwidth requirements. Our evaluation results indicate that A3D-MoE delivers significant performance enhancements, reducing latency by a factor of 1.8x to 2x and energy consumption by 2x to 4x, while improving throughput by 1.44x to 1.8x compared to the state-of-the-art.

[Arxiv](https://arxiv.org/abs/2507.19142)