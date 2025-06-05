# FlashMLA-ETAP: 在 NVIDIA H20 GPU 上加速 MLA 推理的高效转置注意力管道

发布时间：2025年06月03日

`LLM应用` `计算机体系结构` `硬件加速`

> FlashMLA-ETAP: Efficient Transpose Attention Pipeline for Accelerating MLA Inference on NVIDIA H20 GPUs

# 摘要

> 在单机多GPU服务器上部署DeepSeek-R1 671B模型时，多头潜在注意力（MLA）的高效推理面临挑战。本文提出了一种针对NVIDIA H20 GPU单实例部署场景的新型框架FlashMLA-ETAP。我们设计了高效转置注意力流水线（ETAP），通过转置重新配置注意力计算，使KV上下文长度与WGMMA操作中的【数学公式】维度对齐，从而大幅减少冗余计算。在64K序列长度（批量大小16）下，FlashMLA-ETAP相比FlashMLA实现了2.78倍的速度提升，相比FlashAttention-3和FlashInfer分别提升了5.24倍和4.94倍，同时保持数值稳定性，其均方根误差（RMSE）为【数学公式】，比FlashAttention-3低15.2倍。此外，ETAP的设计支持与FlashAttention-3和FlashInfer等框架无缝集成，并辅以详尽的理论分析。我们的工作填补了资源受限推理中的关键空白，为中端GPU提供了可扩展的解决方案，并为硬件感知优化的广泛应用铺平了道路。代码可在https://github.com/pengcuo/FlashMLA-ETAP获取。

> Efficient inference of Multi-Head Latent Attention (MLA) is challenged by deploying the DeepSeek-R1 671B model on a single Multi-GPU server. This paper introduces FlashMLA-ETAP, a novel framework that enhances MLA inference for the single-instance deployment scenario on NVIDIA H20 GPUs. We propose the Efficient Transpose Attention Pipeline (ETAP), which reconfigures attention computation through transposition to align the KV context length with the \(M\)-dimension in WGMMA operations, significantly reducing redundant computations. FlashMLA-ETAP achieves a 2.78x speedup over FlashMLA at 64K sequence length (batch size 16), with 5.24x and 4.94x improvements over FlashAttention-3 and FlashInfer, respectively, while maintaining numerical stability with a 15.2x lower RMSE (\(1.25 \times 10^{-5}\)) than FlashAttention-3. Furthermore, ETAP's design enables seamless integration into frameworks like FlashAttention-3 and FlashInfer, supported by a detailed theoretical analysis. Our work addresses a critical gap in resource-constrained inference, offering a scalable solution for mid-tier GPUs and paving the way for broader adoption in hardware-aware optimization. Code is available at https://github.com/pengcuo/FlashMLA-ETAP.

[Arxiv](https://arxiv.org/abs/2506.01969)