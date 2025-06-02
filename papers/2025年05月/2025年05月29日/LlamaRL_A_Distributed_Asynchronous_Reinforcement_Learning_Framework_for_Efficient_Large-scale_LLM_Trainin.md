# LlamaRL：一个高效的大规模LLM训练分布式异步强化学习框架

发布时间：2025年05月29日

`LLM应用` `人工智能`

> LlamaRL: A Distributed Asynchronous Reinforcement Learning Framework for Efficient Large-scale LLM Trainin

# 摘要

> 强化学习 (RL) 已成为提升大型语言模型 (LLMs) 能力的最有效后训练方法。然而，由于对延迟和内存的高要求，开发一个能够高效管理数百到数千亿参数策略模型的 RL 框架极具挑战性。

本文中，我们介绍了 LlamaRL——一个专为 GPU 集群设计的完全分布式、异步 RL 框架，支持从少量到数千个设备的高效训练，适用于 8B、70B 和 405B 参数等多种规模的大型 LLM。LlamaRL 采用基于原生 PyTorch 的单控制器架构，实现了模块化设计、易用性和对数千个 GPU 的无缝扩展。我们从理论上分析了 LlamaRL 的效率优势，证明其异步设计能够带来严格的 RL 加速。实证结果表明，通过采用模型本地卸载、异步非策略训练和分布式直接内存访问等最佳实践，LlamaRL 在 405B 参数策略模型上的速度提升可达 10.7 倍，显著优于 DeepSpeed-Chat 类系统。此外，随着模型规模的增加，其效率优势进一步凸显，充分展现了该框架在大规模 RL 训练中的潜力。


> Reinforcement Learning (RL) has become the most effective post-training approach for improving the capabilities of Large Language Models (LLMs). In practice, because of the high demands on latency and memory, it is particularly challenging to develop an efficient RL framework that reliably manages policy models with hundreds to thousands of billions of parameters.
  In this paper, we present LlamaRL, a fully distributed, asynchronous RL framework optimized for efficient training of large-scale LLMs with various model sizes (8B, 70B, and 405B parameters) on GPU clusters ranging from a handful to thousands of devices. LlamaRL introduces a streamlined, single-controller architecture built entirely on native PyTorch, enabling modularity, ease of use, and seamless scalability to thousands of GPUs. We also provide a theoretical analysis of LlamaRL's efficiency, including a formal proof that its asynchronous design leads to strict RL speed-up. Empirically, by leveraging best practices such as colocated model offloading, asynchronous off-policy training, and distributed direct memory access for weight synchronization, LlamaRL achieves significant efficiency gains -- up to 10.7x speed-up compared to DeepSpeed-Chat-like systems on a 405B-parameter policy model. Furthermore, the efficiency advantage continues to grow with increasing model scale, demonstrating the framework's suitability for future large-scale RL training.

[Arxiv](https://arxiv.org/abs/2505.24034)