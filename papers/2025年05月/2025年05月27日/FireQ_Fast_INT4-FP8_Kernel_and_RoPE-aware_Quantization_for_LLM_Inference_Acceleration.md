# FireQ：加速LLM推理的快速INT4-FP8内核与RoPE感知量化技术

发布时间：2025年05月27日

`LLM应用` `人工智能` `机器学习`

> FireQ: Fast INT4-FP8 Kernel and RoPE-aware Quantization for LLM Inference Acceleration

# 摘要

> 大型语言模型的广泛应用面临内存带宽限制带来的推理吞吐量瓶颈，为此我们提出了后训练量化（PTQ）的解决方案。本文中，我们推出FireQ，这是一个协同设计的PTQ框架，搭配INT4-FP8矩阵乘法核，能够全面加速大型语言模型的线性层推理。FireQ通过将线性层权重和键值量化为INT4，激活和查询量化为FP8，显著提升了推理效率。此外，我们在预填阶段引入三阶段流水线，优化了FlashAttention-3核，有效缩短了首次令牌生成时间。为减少量化带来的精度损失，我们开发了专门针对线性层和注意力层的新型异常值平滑技术。在线性层中，我们采用逐张量缩放防止INT4量化带来的下溢，同时通过逐通道缩放弥补INT4量化粒度的不足。在注意力层中，我们结合RoPE前和RoPE后的缩放策略，有效解决了旋转位置嵌入（RoPE）带来的量化挑战。实验结果表明，FireQ在Llama2-7B的前馈网络层推理速度上比QServe快1.68倍，在Llama3-8B的预填阶段性能上快1.26倍，同时仅带来微小的精度损失。

> As large language models become increasingly prevalent, memory bandwidth constraints significantly limit inference throughput, motivating post-training quantization (PTQ). In this paper, we propose FireQ, a co-designed PTQ framework and an INT4-FP8 matrix multiplication kernel that accelerates LLM inference across all linear layers. Specifically, FireQ quantizes linear layer weights and key-values to INT4, and activations and queries to FP8, significantly enhancing throughput. Additionally, we introduce a three-stage pipelining for the prefill phase, which modifies the FlashAttention-3 kernel, effectively reducing time-to-first-token in the prefill phase. To minimize accuracy loss from quantization, we develop novel outlier smoothing techniques tailored separately for linear and attention layers. In linear layers, we explicitly use per-tensor scaling to prevent underflow caused by the FP8 quantization scaling factor of INT4 quantization, and channel-wise scaling to compensate for coarse granularity of INT4. In attention layers, we address quantization challenges posed by rotary positional embeddings (RoPE) by combining pre-RoPE and post-RoPE scaling strategies. FireQ significantly outperforms state-of-the-art methods, achieving 1.68x faster inference in feed-forward network layers on Llama2-7B and 1.26x faster prefill phase performance on Llama3-8B compared to QServe, with negligible accuracy loss.

[Arxiv](https://arxiv.org/abs/2505.20839)