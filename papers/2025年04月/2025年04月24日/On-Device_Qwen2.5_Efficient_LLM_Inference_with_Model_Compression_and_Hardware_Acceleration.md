# # 设备端 Qwen2.5：结合模型压缩与硬件加速实现高效推理

发布时间：2025年04月24日

`LLM应用` `边缘计算` `硬件加速`

> On-Device Qwen2.5: Efficient LLM Inference with Model Compression and Hardware Acceleration

# 摘要

> 基于Transformer的大型语言模型（LLMs）显著提升了AI能力，但在边缘设备部署面临高计算需求、内存带宽限制和能源消耗等挑战。本文针对这些问题，提出了一种在Xilinx Kria KV260边缘平台上高效部署Qwen2.5-0.5B模型的框架。该平台是一个集成了ARM Cortex-A53 CPU和可重配置FPGA逻辑的异构系统。通过结合FPGA加速执行流水线的激活感知权重量化（AWQ），本文方法提升了模型压缩率和系统吞吐量。此外，我们提出了一种混合执行策略，智能地将计算密集型操作 offload 到 FPGA，同时利用 CPU 处理较轻的任务，从而有效平衡计算负载并最大化整体性能。与原模型相比，我们的框架实现了55.08%的模型压缩率，并以5.1 tokens/秒的速度生成输出，优于基线性能的2.8 tokens/秒。

> Transformer-based Large Language Models (LLMs) have significantly advanced AI capabilities but pose considerable challenges for deployment on edge devices due to high computational demands, memory bandwidth constraints, and energy consumption. This paper addresses these challenges by presenting an efficient framework for deploying the Qwen2.5-0.5B model on the Xilinx Kria KV260 edge platform, a heterogeneous system integrating an ARM Cortex-A53 CPU with reconfigurable FPGA logic. Leveraging Activation-aware Weight Quantization (AWQ) with FPGA-accelerated execution pipelines, the proposed approach enhances both model compression rate and system throughput. Additionally, we propose a hybrid execution strategy that intelligently offloads compute-intensive operations to the FPGA while utilizing the CPU for lighter tasks, effectively balancing the computational workload and maximizing overall performance. Our framework achieves a model compression rate of 55.08% compared to the original model and produces output at a rate of 5.1 tokens per second, outperforming the baseline performance of 2.8 tokens per second.

[Arxiv](https://arxiv.org/abs/2504.17376)