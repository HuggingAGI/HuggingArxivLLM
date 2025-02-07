# # 缓存我，如果你必须：大型语言模型的自适应键值量化

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了如何通过改进键值（KV）缓存的压缩方法来提高大型语言模型（LLMs）的部署效率。具体来说，论文提出了AQUA-KV方法，通过自适应量化和挖掘键值间的依赖关系来优化缓存压缩。这些技术直接应用于LLMs的实际部署和推理过程中，属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。`

> Cache Me If You Must: Adaptive Key-Value Quantization for Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）的高效部署依赖于键值（KV）缓存，以减少重复计算并处理长输出。对于大型上下文，键值缓存可能占用数十GB内存，因为它们存储了每个标记和层的向量表示。最近的研究表明，可以通过量化、剪枝或合并来压缩这些向量，但这些方法在追求高压缩率时往往会牺牲质量。本研究旨在通过两个关键观察改进键值压缩：1）不同层间键和值的固有依赖关系，2）内部网络状态的高效压缩机制。我们提出了AQUA-KV，一种自适应量化的键值缓存方法，利用紧凑适配器挖掘键值间的依赖关系，并“最优”压缩无法预测的信息。AQUA-KV显著提升了压缩率，同时在最先进的LLM家族上保持了高精度。在Llama 3.2 LLMs上，我们实现了每值2-2.5位的近乎无损推理，困惑度和LongBench分数的相对误差低于1%。AQUA-KV简单高效，可在单个GPU上1-6小时内完成校准，即使是70B模型。

> Efficient real-world deployments of large language models (LLMs) rely on Key-Value (KV) caching for processing and generating long outputs, reducing the need for repetitive computation. For large contexts, Key-Value caches can take up tens of gigabytes of device memory, as they store vector representations for each token and layer. Recent work has shown that the cached vectors can be compressed through quantization, pruning or merging, but these techniques often compromise quality towards higher compression rates. In this work, we aim to improve Key & Value compression by exploiting two observations: 1) the inherent dependencies between keys and values across different layers, and 2) high-compression mechanisms for internal network states. We propose AQUA-KV, an adaptive quantization for Key-Value caches that relies on compact adapters to exploit existing dependencies between Keys and Values, and aims to "optimally" compress the information that cannot be predicted. AQUA-KV significantly improves compression rates, while maintaining high accuracy on state-of-the-art LLM families. On Llama 3.2 LLMs, we achieve near-lossless inference at 2-2.5 bits per value with under $1\%$ relative error in perplexity and LongBench scores. AQUA-KV is one-shot, simple, and efficient: it can be calibrated on a single GPU within 1-6 hours, even for 70B models.

[Arxiv](https://arxiv.org/abs/2501.19392)