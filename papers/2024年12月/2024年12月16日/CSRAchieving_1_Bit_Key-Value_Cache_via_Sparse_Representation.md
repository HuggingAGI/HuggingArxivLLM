# CSR：借助稀疏表示达成 1 位键值缓存

发布时间：2024年12月16日

`LLM应用` `计算机` `人工智能`

> CSR:Achieving 1 Bit Key-Value Cache via Sparse Representation

# 摘要

> 利用大型语言模型（LLMs）的长上下文文本应用的出现带来了重大的可扩展性难题，尤其体现在内存占用上。负责存储注意力键和值以减少冗余计算的键值（KV）缓存呈线性增长，这可能致使内存消耗大幅上升，甚至可能导致模型在内存资源有限时无法运行。为应对此问题，我们提出了一种名为缓存稀疏表示（CSR）的新方法，它将密集的键值缓存张量转化为稀疏索引和权重，在 LLM 推理时提供更节省内存的表示形式。此外，我们引入了 NeuralDict，这是一种基于神经网络的新型方法，用于自动生成我们稀疏表示中所用的字典。我们的大量实验表明，CSR 在内存受限的环境中功能强大，同时实现了与最先进的 KV 缓存量化算法相当的性能。

> The emergence of long-context text applications utilizing large language models (LLMs) has presented significant scalability challenges, particularly in memory footprint. The linear growth of the Key-Value (KV) cache responsible for storing attention keys and values to minimize redundant computations can lead to substantial increases in memory consumption, potentially causing models to fail to serve with limited memory resources. To address this issue, we propose a novel approach called Cache Sparse Representation (CSR), which converts the KV cache by transforming the dense Key-Value cache tensor into sparse indexes and weights, offering a more memory-efficient representation during LLM inference. Furthermore, we introduce NeuralDict, a novel neural network-based method for automatically generating the dictionary used in our sparse representation. Our extensive experiments demonstrate that CSR achieves performance comparable to state-of-the-art KV cache quantization algorithms while maintaining robust functionality in memory-constrained environments.

[Arxiv](https://arxiv.org/abs/2412.11741)