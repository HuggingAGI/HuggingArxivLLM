# Sparse-dLLM：通过动态缓存淘汰加速扩散式大语言模型的运行

发布时间：2025年08月04日

`LLM应用`

> Sparse-dLLM: Accelerating Diffusion LLMs with Dynamic Cache Eviction

# 摘要

> 扩散式大语言模型 (dLLMs) 在推理和并行解码方面实现了突破性进展，但其推理过程中的二次计算复杂度和内存开销却令人望而却步。现有的缓存技术通过存储全层状态加速解码，但其高昂的内存占用限制了其在长上下文场景中的应用。通过对 dLLMs 中注意力模式的深入分析，我们发现跨层稀疏性持续存在，关键标记在整个解码过程中始终保持显著，而低相关标记则始终不重要。这一发现启发了我们对选择性缓存替换策略的研究。我们提出 Sparse-dLLM，这是首个无需训练的框架，通过延迟双向稀疏缓存将动态缓存替换与稀疏注意力相结合。通过利用标记显著性的稳定性，该框架保留了关键标记，并采用注意力引导策略动态移除不重要的前缀/后缀条目。在 LLaDA 和 Dream 系列上的大量实验表明，与原生 dLLMs 相比，Sparse-dLLM 的吞吐量提升了高达 10 倍，同时保持了相当的性能和相近的峰值内存占用，显著超越了以往方法在效率和效果方面的表现。

> Diffusion Large Language Models (dLLMs) enable breakthroughs in reasoning and parallel decoding but suffer from prohibitive quadratic computational complexity and memory overhead during inference. Current caching techniques accelerate decoding by storing full-layer states, yet impose substantial memory usage that limit long-context applications. Our analysis of attention patterns in dLLMs reveals persistent cross-layer sparsity, with pivotal tokens remaining salient across decoding steps and low-relevance tokens staying unimportant, motivating selective cache eviction. We propose Sparse-dLLM, the first training-free framework integrating dynamic cache eviction with sparse attention via delayed bidirectional sparse caching. By leveraging the stability of token saliency over steps, it retains critical tokens and dynamically evicts unimportant prefix/suffix entries using an attention-guided strategy. Extensive experiments on LLaDA and Dream series demonstrate Sparse-dLLM achieves up to 10$\times$ higher throughput than vanilla dLLMs, with comparable performance and similar peak memory costs, outperforming previous methods in efficiency and effectiveness.

[Arxiv](https://arxiv.org/abs/2508.02558)