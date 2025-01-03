# FastAttention: 将 FlashAttention2 扩展至 NPU 与低资源 GPU

发布时间：2024年10月21日

`LLM应用

**理由**：这篇论文主要讨论了如何优化和适配 FlashAttention 系列算法，以提升大型语言模型（LLM）在推理阶段的效率。具体来说，论文提出了 FastAttention，通过一系列优化策略（如两级分块策略、分块掩码策略等）来提升 LLM 在 NPU 和低资源 GPU 上的推理性能。这些优化直接应用于 LLM 的推理过程，属于 LLM 在实际应用中的性能优化问题，因此应归类为 **LLM应用**。` `人工智能` `硬件加速`

> FastAttention: Extend FlashAttention2 to NPUs and Low-resource GPUs

# 摘要

> # 摘要
FlashAttention 系列在 LLM 推理中应用广泛，但仅支持 Ampere 和 Hopper 等高端 GPU 架构，难以移植到 NPU 和低资源 GPU 上，且在多 NPU 或 GPU 推理场景中效率较低。为此，我们提出了 FastAttention，首次将 FlashAttention 系列适配到 NPU 和低资源 GPU 上，显著提升 LLM 推理效率。我们以 Ascend NPU 和 Volta 架构 GPU 为例，设计了 FastAttention。通过引入两级分块策略加速运行时、分块掩码策略节省内存、分块-AllReduce 策略减少通信开销，成功将 FlashAttention 迁移到 Ascend NPU 上。同时，我们通过优化共享内存操作数布局和引入 CPU-GPU 协作策略，将 FlashAttention 适配到 Volta 架构 GPU 上，实现高效内存利用。在 Ascend NPU 上，FastAttention 相比标准注意力实现加速 10.7 倍，Llama-7B 的吞吐量提升 5.16 倍。在 Volta GPU 上，FastAttention 相比 	exttt{xformers} 加速 1.43 倍，Pangu-38B 使用 FasterTransformer 实现端到端加速 1.46 倍。结合 CPU-GPU 协作策略，FastAttention 在 8 个 V100 GPU 上支持最大输入长度 256K。所有代码即将开源。

> FlashAttention series has been widely applied in the inference of large language models (LLMs). However, FlashAttention series only supports the high-level GPU architectures, e.g., Ampere and Hopper. At present, FlashAttention series is not easily transferrable to NPUs and low-resource GPUs. Moreover, FlashAttention series is inefficient for multi- NPUs or GPUs inference scenarios. In this work, we propose FastAttention which pioneers the adaptation of FlashAttention series for NPUs and low-resource GPUs to boost LLM inference efficiency. Specifically, we take Ascend NPUs and Volta-based GPUs as representatives for designing our FastAttention. We migrate FlashAttention series to Ascend NPUs by proposing a novel two-level tiling strategy for runtime speedup, tiling-mask strategy for memory saving and the tiling-AllReduce strategy for reducing communication overhead, respectively. Besides, we adapt FlashAttention for Volta-based GPUs by redesigning the operands layout in shared memory and introducing a simple yet effective CPU-GPU cooperative strategy for efficient memory utilization. On Ascend NPUs, our FastAttention can achieve a 10.7$\times$ speedup compared to the standard attention implementation. Llama-7B within FastAttention reaches up to 5.16$\times$ higher throughput than within the standard attention. On Volta architecture GPUs, FastAttention yields 1.43$\times$ speedup compared to its equivalents in \texttt{xformers}. Pangu-38B within FastAttention brings 1.46$\times$ end-to-end speedup using FasterTransformer. Coupled with the propose CPU-GPU cooperative strategy, FastAttention supports a maximal input length of 256K on 8 V100 GPUs. All the codes will be made available soon.

[Arxiv](https://arxiv.org/abs/2410.16663)