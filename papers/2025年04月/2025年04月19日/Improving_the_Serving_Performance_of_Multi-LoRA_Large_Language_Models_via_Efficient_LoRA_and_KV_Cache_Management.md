# 通过高效LoRA和KV缓存管理优化多LoRA大型语言模型的服务性能

发布时间：2025年04月19日

`LLM应用` `大型语言模型` `缓存管理`

> Improving the Serving Performance of Multi-LoRA Large Language Models via Efficient LoRA and KV Cache Management

# 摘要

> 多低秩适配器（Multi-LoRAs）正逐渐成为大型语言模型（LLM）特定任务应用的热门选择。对于多LoRA服务，将热门的KV缓存和LoRA适配器缓存至加速器的高带宽内存中可以提升推理性能。然而，现有的多LoRA推理系统未能优化服务性能如首词响应时间（TTFT），在缓存LoRAs和KV时忽略了使用依赖关系。因此，我们提出了FASTLIBRA，一个多LoRA缓存系统，旨在优化服务性能。 FASTLIBRA包含一个感知依赖关系的缓存管理器和一个性能驱动的缓存交换器。缓存管理器在推理过程中维护LoRAs和KV缓存之间的使用依赖关系，并使用统一的缓存池。缓存交换器根据统一的成本模型，在HBM空闲或忙碌时，分别决定LoRAs和KV缓存的换入或换出。实验结果表明，与现有最先进方法相比，FASTLIBRA平均将TTFT降低了63.4%。

> Multiple Low-Rank Adapters (Multi-LoRAs) are gaining popularity for task-specific Large Language Model (LLM) applications. For multi-LoRA serving, caching hot KV caches and LoRA adapters in high bandwidth memory of accelerations can improve inference performance. However, existing Multi-LoRA inference systems fail to optimize serving performance like Time-To-First-Toke (TTFT), neglecting usage dependencies when caching LoRAs and KVs. We therefore propose FASTLIBRA, a Multi-LoRA caching system to optimize the serving performance. FASTLIBRA comprises a dependency-aware cache manager and a performance-driven cache swapper. The cache manager maintains the usage dependencies between LoRAs and KV caches during the inference with a unified caching pool. The cache swapper determines the swap-in or out of LoRAs and KV caches based on a unified cost model, when the HBM is idle or busy, respectively. Experimental results show that ELORA reduces the TTFT by 63.4% on average, compared to state-of-the-art works.

[Arxiv](https://arxiv.org/abs/2505.03756)