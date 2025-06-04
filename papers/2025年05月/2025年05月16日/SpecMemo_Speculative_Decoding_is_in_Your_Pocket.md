# # SpecMemo：Speculative Decoding触手可及

发布时间：2025年05月16日

`LLM应用` `资源受限环境` `分布式计算`

> SpecMemo: Speculative Decoding is in Your Pocket

# 摘要

> 推测性解码技术在大型语言模型任务中取得了显著进展，已在各类LLM任务中展现出显著加速效果。然而，这一技术在移动GPU等内存受限设备上的实际应用仍面临重大挑战。本文提出了一种名为SpecMemo的设备感知推理引擎，通过智能控制内存分配，在内存受限设备上实现了支持推测性解码的多轮对话机器人。我们通过理论建模推测性解码的内存占用，确定了在保持加速效果下的最低内存预算。SpecMemo在实证中实现了对冗余内存分配的最小化，同时保持了推测性解码带来的性能提升。在MT-Bench基准测试中，SpecMemo保留了96%的推测性解码吞吐量，同时将生成内存减少了65%。在多GPU场景下，我们通过分布式部署Llama-2-70B-Chat模型，提出了全新的批量推测性解码方法，显著提升了多块小型服务器GPU的利用率。这一框架相较于八块AMD MI250 GPU的分布式和批量标准解码，实现了2倍的加速效果。当批量大小为10时，推理吞吐量提升了8倍。我们的工作为资源受限环境下的LLM应用提供了高效解决方案，助力真实世界中LLM应用的快速、低成本部署。


> Recent advancements in speculative decoding have demonstrated considerable speedup across a wide array of large language model (LLM) tasks. Speculative decoding inherently relies on sacrificing extra memory allocations to generate several candidate tokens, of which acceptance rate drives the speedup. However, deploying speculative decoding on memory-constrained devices, such as mobile GPUs, remains as a significant challenge in real-world scenarios. In this work, we present a device-aware inference engine named SpecMemo that can smartly control memory allocations at finer levels to enable multi-turn chatbots with speculative decoding on such limited memory devices. Our methodology stems from theoretically modeling memory footprint of speculative decoding to determine a lower bound on the required memory budget while retaining speedup. SpecMemo empirically acquires a careful balance between minimizing redundant memory allocations for rejected candidate tokens and maintaining competitive performance gains from speculation. Notably, with SpecMemo's memory management, we maintain 96% of overall throughput from speculative decoding on MT-Bench, with reduced generation-memory by 65% on single Nvidia Titan RTX. Given multiple constrained GPUs, we build on top of previous speculative decoding architectures to facilitate big-model inference by distributing Llama-2-70B-Chat model, on which we provide novel batched speculative decoding to increase usability of multiple small server GPUs. This novel framework demonstrates 2x speedup over distributed and batched vanilla decoding with the base model on eight AMD MI250 GPUs. Moreover, inference throughput increases remarkably 8x with batch size 10. Our work contributes to democratized LLM applications in resource-constrained environments, providing a pathway for faster and cheaper deployment of real-world LLM applications with robust performance.

[Arxiv](https://arxiv.org/abs/2506.01986)