# FlashMLA-ETAP：加速MLA推理的高效转置注意力管道，在NVIDIA H20 GPU上实现性能提升

发布时间：2025年05月13日

`其他` `计算机体系结构` `计算机科学`

> FlashMLA-ETAP: Efficient Transpose Attention Pipeline for Accelerating MLA Inference on NVIDIA H20 GPUs

# 摘要

> 在单机多GPU服务器上部署DeepSeek-R1 671B模型时，Multi-Head Latent Attention (MLA)的高效推理面临挑战。本文介绍了一种全新的框架FlashMLA-ETAP，专门针对NVIDIA H20 GPU的单实例部署场景优化MLA推理性能。我们提出了高效转置注意力管道（ETAP），通过重新配置注意力计算中的转置操作，使KV上下文长度与WGMMA操作中的\(M\)-dimension对齐，从而大幅减少冗余计算。在64K长度序列（批量大小16）下，FlashMLA-ETAP较FlashMLA实现2.78倍加速，较FlashAttention-3和FlashInfer分别提升5.24倍和4.94倍，同时保持数值稳定性，其RMSE（\(1.25 	imes 10^{-5}\)）较FlashAttention-3低15.2倍。此外，ETAP的设计支持与FlashAttention-3和FlashInfer等框架无缝集成，并配有详细理论分析。本研究填补了资源受限推理的关键空白，为中端GPU提供可扩展解决方案，并为硬件感知优化的广泛应用铺平道路。代码已开源：https://github.com/pengcuo/FlashMLA-ETAP。

> Efficient inference of Multi-Head Latent Attention (MLA) is challenged by deploying the DeepSeek-R1 671B model on a single Multi-GPU server. This paper introduces FlashMLA-ETAP, a novel framework that enhances MLA inference for the single-instance deployment scenario on NVIDIA H20 GPUs. We propose the Efficient Transpose Attention Pipeline (ETAP), which reconfigures attention computation through transposition to align the KV context length with the \(M\)-dimension in WGMMA operations, significantly reducing redundant computations. FlashMLA-ETAP achieves a 2.78x speedup over FlashMLA at 64K sequence length (batch size 16), with 5.24x and 4.94x improvements over FlashAttention-3 and FlashInfer, respectively, while maintaining numerical stability with a 15.2x lower RMSE (\(1.25 \times 10^{-5}\)) than FlashAttention-3. Furthermore, ETAP's design enables seamless integration into frameworks like FlashAttention-3 and FlashInfer, supported by a detailed theoretical analysis. Our work addresses a critical gap in resource-constrained inference, offering a scalable solution for mid-tier GPUs and paving the way for broader adoption in hardware-aware optimization. Code is available at https://github.com/pengcuo/FlashMLA-ETAP.

[Arxiv](https://arxiv.org/abs/2506.01969)