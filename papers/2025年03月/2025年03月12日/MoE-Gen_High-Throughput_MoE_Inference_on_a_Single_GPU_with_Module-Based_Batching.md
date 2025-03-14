# MoE-Gen：单GPU实现高吞吐量MoE推理的模块化批处理方案

发布时间：2025年03月12日

`LLM应用` `大规模语言模型` `推理优化`

> MoE-Gen: High-Throughput MoE Inference on a Single GPU with Module-Based Batching

# 摘要

> 本文提出了一种针对单 GPU 执行优化的高吞吐量 MoE 推理系统——MoE-Gen。现有的推理系统主要依赖基于模型的或连续的 batching 策略，这些策略最初为交互式推理设计，导致 MoE 的核心模块（注意力模块和专家模块）批次过小，严重制约了吞吐量。为此，我们创新性地引入了模块化 batching，通过在主机内存中累积令牌，并动态在 GPU 上启动大批次，从而最大化 GPU 利用率。同时，我们针对 MoE 中各模块的批次大小进行了优化，使 GPU 计算与通信实现最大程度的重叠，从而显著提升吞吐量。实验结果表明，MoE-Gen 的吞吐量较采用基于模型的 batching 的最先进系统（FlexGen、MoE-Lightning、DeepSpeed）提升了 8-31 倍，且在 DeepSeek 和 Mixtral 等流行 MoE 模型的离线推理任务中，较 vLLM 和 Ollama 等连续 batching 系统实现了更大的吞吐量提升。MoE-Gen 的源代码已公开发布，访问地址为 https://github.com/EfficientMoE/MoE-Gen。

> This paper presents MoE-Gen, a high-throughput MoE inference system optimized for single-GPU execution. Existing inference systems rely on model-based or continuous batching strategies, originally designed for interactive inference, which result in excessively small batches for MoE's key modules-attention and expert modules-leading to poor throughput. To address this, we introduce module-based batching, which accumulates tokens in host memory and dynamically launches large batches on GPUs to maximize utilization. Additionally, we optimize the choice of batch sizes for each module in an MoE to fully overlap GPU computation and communication, maximizing throughput. Evaluation demonstrates that MoE-Gen achieves 8-31x higher throughput compared to state-of-the-art systems employing model-based batching (FlexGen, MoE-Lightning, DeepSpeed), and offers even greater throughput improvements over continuous batching systems (e.g., vLLM and Ollama) on popular MoE models (DeepSeek and Mixtral) across offline inference tasks. MoE-Gen's source code is publicly available at https://github.com/EfficientMoE/MoE-Gen

[Arxiv](https://arxiv.org/abs/2503.09716)