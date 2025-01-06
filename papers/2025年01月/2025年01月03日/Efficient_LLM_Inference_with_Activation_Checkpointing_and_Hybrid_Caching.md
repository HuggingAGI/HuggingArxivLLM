# 高效LLM推理：激活检查点与混合缓存的结合

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了如何通过优化LLM推理系统（HybridServe）来降低生成token的成本和提高GPU计算资源的利用率。这涉及到LLM在实际应用中的性能优化和成本控制，属于LLM在实际应用中的技术改进和优化，因此应归类为LLM应用。` `人工智能` `系统优化`

> Efficient LLM Inference with Activation Checkpointing and Hybrid Caching

# 摘要

> # 摘要
近年来，随着大型语言模型（LLMs）规模的急剧增长，生成token的成本也随之飙升，因为需要大量GPU来满足内存需求。为了在放宽延迟限制的同时降低LLM推理成本，研究者们纷纷将目光投向利用主机内存扩展GPU内存。然而，依赖主机内存的LLM推理引擎常常面临GPU计算资源利用率低下的问题，因为大量时间被耗费在通过主机-GPU互连加载模型上。为了解决这一难题，我们推出了HybridServe——一个基于激活缓存的LLM推理系统。该系统通过在中间推理阶段存储激活检查点，实现了在模型参数从主机内存传输到GPU时快速重建KV缓存。与传统的从头计算KV缓存的方法不同，HybridServe巧妙地绕过了投影和FFN操作。为了在激活重建和参数加载之间找到最佳平衡点，我们提出了一种KV-激活混合缓存方案，通过优化关键值和激活缓存的比例来调整重建时间。实验表明，我们的系统在模型权重和KV缓存卸载方面，比现有最先进的方法提升了2.19倍的吞吐量。

> Recent large language models (LLMs) with enormous model sizes use many GPUs to meet memory capacity requirements incurring substantial costs for token generation. To provide cost-effective LLM inference with relaxed latency constraints, extensive research has focused on expanding GPU memory by leveraging the host memory. However, LLM inference engines that utilize the host memory often face underutilization of GPU compute units, as a considerable portion of inference time is spent in loading the model onto the GPU via host-GPU interconnect. To tackle these challenges of the host memory offloading for LLM, we introduce HybridServe, an LLM inference system with activation checkpointing based on activation caching. The activation cache stores activation checkpoints generated during intermediate inference stages, allowing the fast recomputation of KV cache while model parameters are transferred to GPU from host memory. Unlike conventional methods that recompute the KV cache from scratch using token IDs, the activation cache allows bypassing projection and FFN operations. To balance between the activation recomputation and parameter loading overhead, this study proposes a KV-activation hybrid caching scheme which finds the best ratio of the key-value and activation caches to adjust the recomputation time. Our system achieves 2.19x throughput improvement over the state-of-the-art prior work for offloading both model weights and KV cache.

[Arxiv](https://arxiv.org/abs/2501.01792)