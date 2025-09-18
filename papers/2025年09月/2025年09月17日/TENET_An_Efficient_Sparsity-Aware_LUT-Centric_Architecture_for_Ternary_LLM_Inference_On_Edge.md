# TENET：面向边缘端三值大型语言模型推理的高效稀疏感知、以LUT为中心架构

发布时间：2025年09月17日

`LLM应用` `基础理论`

> TENET: An Efficient Sparsity-Aware LUT-Centric Architecture for Ternary LLM Inference On Edge

# 摘要

> 三元量化技术凭借减少大型语言模型（LLM）计算与内存占用的优势，已成为实现高效实时推理部署的关键手段，且不会显著牺牲模型精度。然而传统LLM推理平台（如GPU）却难以充分发挥其潜力：一方面缺乏对三元算术和内存专用化的原生支持，另一方面在小批量实时场景中硬件利用率极低。为此，本研究提出TENET——一种稀疏感知的LUT中心架构，通过协同优化算法、计算与内存，专为三元LLM推理打造。为提升三元线性层效率，TENET设计了稀疏三元LUT（STL）核心，借助对称预计算查找表优化三元混合精度GEMM；同时引入动态激活N:M稀疏性，充分挖掘每个token激活中的稀疏特性。此外，我们还开发了基于LUT的64B:80B三元权重解压缩模块，以释放三元值的内存效率。在系统层面，TENET是一款具备完全可编程性的异构加速器，集成了STL核心与高精度核心，并配套设计线性投影感知稀疏注意力数据流，优化内存访问与硬件利用率。我们在FPGA和ASIC平台均实现了TENET原型验证，实验表明：在不同模型规模与工作负载下，TENET-FPGA和TENET-ASIC相较A100 GPU，能效分别提升【数学公式】和【数学公式】；在端到端推理延迟上，TENET-ASIC更实现【数学公式】的平均提速。

> Ternary quantization has emerged as a powerful technique for reducing both computational and memory footprint of large language models (LLM), enabling efficient real-time inference deployment without significantly compromising model accuracy. Conventional LLM inference platforms (e.g GPUs) cannot capitalize on its benefits, as they (i) lack native support for ternary arithmetic and memory specialization and (ii) remain severely under-utilized in low-batch, real-time scenarios. In this work, we propose TENET, a sparse-aware LUT-centric architecture that co-optimizes algorithm, compute, and memory for ternary LLM inference. To maximize the efficiency of Ternary Linear layer, TENET introduces a Sparse Ternary LUT (STL) core that optimizes ternary mixed-precision GEMM using a symmetric precompute lookup table. It also features Dynamic Activation N:M Sparsity to exploit the sparsity within the activation of each token. Additionally, we propose a LUT-based 64B:80B ternary weight decompression module to fully exploit the memory efficiency of ternary values. At the system level, we design a heterogeneous TENET accelerator with full programmability that integrates STL cores with high-precision cores. An associated Linear-Projection-aware Sparse Attention dataflow is introduced to optimize memory access and hardware utilization. We implement TENET accelerator prototype on both FPGA and ASIC platforms. Experiments across various model sizes and workloads demonstrate that TENET-FPGA and TENET-ASIC improve energy efficiency by 4.3$\times$ and 21.1$\times$, respectively, compared to the A100 GPU. Furthermore, TENET-ASIC achieves a 2.7$\times$ average speedup compared to the A100 GPU in end-to-end inference latency.

[Arxiv](https://arxiv.org/abs/2509.13765)