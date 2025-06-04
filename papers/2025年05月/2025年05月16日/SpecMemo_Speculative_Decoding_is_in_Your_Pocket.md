# SpecMemo：推测式解码就在你手中

发布时间：2025年05月16日

`LLM应用` `人工智能` `云计算`

> SpecMemo: Speculative Decoding is in Your Pocket

# 摘要

> 推测式解码技术在大型语言模型任务中展现出显著加速效果，但其内存消耗问题限制了在移动端等资源受限设备上的应用。本研究提出了一款名为SpecMemo的智能推理引擎，通过精妙的内存管理策略，在保证性能的前提下大幅降低了内存占用。在MT-Bench基准测试中，SpecMemo实现了96%的推测式解码吞吐量，同时将内存占用降低了65%。针对多GPU环境，我们创新性地提出了分布式批量推测式解码方案，使八张AMD MI250 GPU的推理速度提升了2倍，批处理吞吐量更是达到了8倍的惊人增长。这一突破性成果为资源受限环境下的LLM应用落地提供了高效解决方案，推动了人工智能技术的普惠化发展。

> Recent advancements in speculative decoding have demonstrated considerable speedup across a wide array of large language model (LLM) tasks. Speculative decoding inherently relies on sacrificing extra memory allocations to generate several candidate tokens, of which acceptance rate drives the speedup. However, deploying speculative decoding on memory-constrained devices, such as mobile GPUs, remains as a significant challenge in real-world scenarios. In this work, we present a device-aware inference engine named SpecMemo that can smartly control memory allocations at finer levels to enable multi-turn chatbots with speculative decoding on such limited memory devices. Our methodology stems from theoretically modeling memory footprint of speculative decoding to determine a lower bound on the required memory budget while retaining speedup. SpecMemo empirically acquires a careful balance between minimizing redundant memory allocations for rejected candidate tokens and maintaining competitive performance gains from speculation. Notably, with SpecMemo's memory management, we maintain 96% of overall throughput from speculative decoding on MT-Bench, with reduced generation-memory by 65% on single Nvidia Titan RTX. Given multiple constrained GPUs, we build on top of previous speculative decoding architectures to facilitate big-model inference by distributing Llama-2-70B-Chat model, on which we provide novel batched speculative decoding to increase usability of multiple small server GPUs. This novel framework demonstrates 2x speedup over distributed and batched vanilla decoding with the base model on eight AMD MI250 GPUs. Moreover, inference throughput increases remarkably 8x with batch size 10. Our work contributes to democratized LLM applications in resource-constrained environments, providing a pathway for faster and cheaper deployment of real-world LLM applications with robust performance.

[Arxiv](https://arxiv.org/abs/2506.01986)