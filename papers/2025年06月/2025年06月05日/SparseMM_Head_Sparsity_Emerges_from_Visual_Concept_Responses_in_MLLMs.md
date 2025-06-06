# SparseMM: 多模态大型语言模型中视觉概念响应揭示头部稀疏性

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）的注意力机制，特别是在视觉输入处理方面的稀疏性现象，并提出了一种优化策略SparseMM，用于加速推理过程。研究集中在模型的应用优化和实际性能提升，属于LLM应用的范畴。` `人工智能`

> SparseMM: Head Sparsity Emerges from Visual Concept Responses in MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）通常通过在预训练大型语言模型（LLMs）的基础上扩展视觉功能来构建。在本研究中，我们通过分析MLLMs的注意力机制，探讨其如何处理视觉输入。令人惊讶的是，我们发现了一种稀疏现象：仅约5%的注意力头（称为视觉头）在LLMs中对视觉理解起主要作用。为了高效识别这些头，我们设计了一个无需训练的框架，通过针对性的响应分析量化头级别的视觉相关性。在此基础上，我们提出了SparseMM，这是一种基于视觉得分为LLMs中的各头分配非对称计算预算的KV-Cache优化策略，利用视觉头的稀疏性加速MLLMs的推理过程。与忽略视觉特性的现有KV-Cache加速方法不同，SparseMM在解码过程中优先考虑视觉语义的保留。在主流多模态基准测试中的广泛评估表明，SparseMM实现了更优的准确性和效率平衡。值得注意的是，SparseMM在生成过程中实现了1.38倍的实时加速和52%的内存减少，同时在效率测试中保持了与现有方法相当的性能。我们的项目已开源，地址为https://github.com/CR400AF-A/SparseMM。


> Multimodal Large Language Models (MLLMs) are commonly derived by extending pre-trained Large Language Models (LLMs) with visual capabilities. In this work, we investigate how MLLMs process visual inputs by analyzing their attention mechanisms. We reveal a surprising sparsity phenomenon: only a small subset (approximately less than 5%) of attention heads in LLMs actively contribute to visual understanding, termed visual heads. To identify these heads efficiently, we design a training-free framework that quantifies head-level visual relevance through targeted response analysis. Building on this discovery, we introduce SparseMM, a KV-Cache optimization strategy that allocates asymmetric computation budgets to heads in LLMs based on their visual scores, leveraging the sparity of visual heads for accelerating the inference of MLLMs. Compared with prior KV-Cache acceleration methods that ignore the particularity of visual, SparseMM prioritizes stress and retaining visual semantics during decoding. Extensive evaluations across mainstream multimodal benchmarks demonstrate that SparseMM achieves superior accuracy-efficiency trade-offs. Notably, SparseMM delivers 1.38x real-time acceleration and 52% memory reduction during generation while maintaining performance parity on efficiency test. Our project is open sourced at https://github.com/CR400AF-A/SparseMM.

[Arxiv](https://arxiv.org/abs/2506.05344)