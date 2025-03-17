# 玉米淀粉：分布式多模态训练必须具备多模态感知能力

发布时间：2025年03月14日

`LLM理论

这篇论文主要探讨了多模态大型语言模型（MLLMs）的高效训练框架设计，属于模型训练方法和优化的范畴，因此归类为LLM理论。` `人工智能`

> Cornstarch: Distributed Multimodal Training Must Be Multimodality-Aware

# 摘要

> 多模态大型语言模型（MLLMs）通过结合异构模型架构，提升了大型语言模型（LLMs）的能力，使其能够处理图像和音频等多种模态数据。然而，MLLM模型结构和数据类型的异构性，使得现有LLM训练框架难以直接应用于MLLM的高效训练。本文中，我们首次提出了通用的分布式MLLM训练框架Cornstarch。该框架支持模块化MLLM构建，实现组件模型的组合式并行化，并针对MLLM的管道和上下文并行引入了专门优化，从而实现高效的分布式MLLM训练。实验结果表明，Cornstarch在训练吞吐量方面超越现有最优方案，提升幅度最高可达【数学公式】倍。

> Multimodal large language models (MLLMs) extend the capabilities of large language models (LLMs) by combining heterogeneous model architectures to handle diverse modalities like images and audio. However, this inherent heterogeneity in MLLM model structure and data types makes makeshift extensions to existing LLM training frameworks unsuitable for efficient MLLM training.
  In this paper, we present Cornstarch, the first general-purpose distributed MLLM training framework. Cornstarch facilitates modular MLLM construction, enables composable parallelization of constituent models, and introduces MLLM-specific optimizations to pipeline and context parallelism for efficient distributed MLLM training. Our evaluation shows that Cornstarch outperforms state-of-the-art solutions by up to $1.57\times$ in terms of training throughput.

[Arxiv](https://arxiv.org/abs/2503.11367)