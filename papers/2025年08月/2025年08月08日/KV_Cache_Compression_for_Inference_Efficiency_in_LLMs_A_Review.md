# 键值缓存压缩在大型语言模型推理效率中的应用综述

发布时间：2025年08月08日

`LLM理论` `计算机科学` `人工智能`

> KV Cache Compression for Inference Efficiency in LLMs: A Review

# 摘要

> 大型语言模型的快速发展推动了推理上下文长度的持续增长，随之而来的是键值（KV）缓存需求的指数级攀升。这一趋势引发了显著的内存瓶颈，制约了模型的推理效率和扩展能力。因此，优化KV缓存成为提升性能和效率的关键。本研究系统性地梳理了当前的KV缓存优化技术，涵盖选择性标记策略、量化及注意力压缩等压缩方法。我们深入评估了这些方法的有效性、权衡及其适用场景，全面分析了它们对内存使用和推理速度的影响。特别关注现有方法的局限性与挑战，例如与不同模型和任务的兼容性问题。此外，本研究还展望了未来的研究方向，包括混合优化技术、自适应动态策略及软硬件协同设计，旨在提升推理效率并推动大型语言模型的实际应用。

> Withtherapid advancement of large language models (LLMs), the context length for inference has been continuously increasing, leading to an exponential growth in the demand for Key-Value (KV) caching. This has resulted in a significant memory bottleneck, limiting the inference efficiency and scalability of the models. Therefore, optimizing the KV cache during inference is crucial for enhancing performance and efficiency. This review systematically examines current KV cache optimization techniques, including compression strategies such as selective token strategies, quantization, and attention compression. We evaluate the effectiveness, trade-offs, and application scenarios of these methods, providing a comprehensive analysis of their impact on memory usage and inference speed. We focus on identifying the limitations and challenges of existing methods, such as compatibility issues with different models and tasks. Additionally, this review highlights future research directions, including hybrid optimization techniques, adaptive dynamic strategies, and software-hardware co-design. These approaches aim to improve inference efficiency and promote the practical application of large language models.

[Arxiv](https://arxiv.org/abs/2508.06297)