# TeLLMe：高效能三元大语言模型加速器，专为边缘FPGA预填充与解码而设计

发布时间：2025年04月22日

`LLM应用` `边缘计算`

> TeLLMe: An Energy-Efficient Ternary LLM Accelerator for Prefilling and Decoding on Edge FPGAs

# 摘要

> 在边缘平台上部署大型语言模型（LLMs）面临高计算和内存需求带来的挑战。尽管低比特量化方法（如BitNet、DeepSeek）能够以1.58比特的权重实现高精度压缩，但边缘部署仍受限于片上资源、功耗预算以及常被忽视的预填阶段延迟。我们提出TeLLMe——首个专为低功耗FPGA（如AMD KV260）设计的三元LLM加速器，全面支持1.58比特权重和8比特激活的预填与自回归解码。主要贡献包括：1）一种结合分组激活与在线预计算的三元矩阵乘法查找表引擎，显著减少资源占用；2）一种带反向重排方案的高效带宽注意力模块，加速预填过程；3）一个专为超低比特推理优化的紧耦合归一化与量化-反量化单元。在7瓦功耗预算下，TeLLMe实现1024-token上下文每秒9个tokens的吞吐量，64至128个token提示的预填延迟为0.55至1.15秒，标志着能效的重大突破，并为生成式AI在边缘FPGA上树立了新标杆。

> Deploying large language models (LLMs) on edge platforms is challenged by their high computational and memory demands. Although recent low-bit quantization methods (e.g., BitNet, DeepSeek) compress weights to as little as 1.58 bits with minimal accuracy loss, edge deployment is still constrained by limited on-chip resources, power budgets, and the often-neglected latency of the prefill phase. We present TeLLMe, the first ternary LLM accelerator for low-power FPGAs (e.g., AMD KV260) that fully supports both prefill and autoregressive decoding using 1.58-bit weights and 8-bit activations. Our contributions include: (1) a table-lookup matrix engine for ternary matmul that merges grouped activations with online precomputation to minimize resource use; (2) a fused, bandwidth-efficient attention module featuring a reversed reordering scheme to accelerate prefill; and (3) a tightly integrated normalization and quantization--dequantization unit optimized for ultra-low-bit inference. Under a 7W power budget, TeLLMe delivers up to 9 tokens/s throughput over 1,024-token contexts and prefill latencies of 0.55--1.15 s for 64--128 token prompts, marking a significant energy-efficiency advance and establishing a new edge FPGA benchmark for generative AI.

[Arxiv](https://arxiv.org/abs/2504.16266)