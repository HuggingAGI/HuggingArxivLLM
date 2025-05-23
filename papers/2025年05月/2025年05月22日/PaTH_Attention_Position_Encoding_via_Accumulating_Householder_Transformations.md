# PaTH 注意力：基于累积豪斯霍尔德变换的位置编码

发布时间：2025年05月22日

`LLM理论` `人工智能`

> PaTH Attention: Position Encoding via Accumulating Householder Transformations

# 摘要

> 注意力机制是现代大型语言模型（LLMs）及AI领域中的核心要素。由于其自身具有置换不变性，因此位置编码对于语言等结构化领域的建模至关重要。旋转位置编码（RoPE）已成为事实上的标准位置编码方法，并被众多现代LLMs采用。然而，RoPE中两个序列元素间的键/查询变换仅依赖于相对位置，与实际输入无关，这限制了其表达能力。

本文提出了一种灵活的数据相关位置编码方案PaTH，基于Householder（类似）变换的累积乘积，其中每次变换都是输入的函数。我们通过紧凑表示的Householder矩阵乘积，推导出高效的并行训练算法，并实现了一种类似FlashAttention的分块算法以最小化I/O成本。在合成基准和真实世界语言建模实验中，PaTH均展现出优于RoPE和其他近期基线的性能。

> The attention mechanism is a core primitive in modern large language models (LLMs) and AI more broadly. Since attention by itself is permutation-invariant, position encoding is essential for modeling structured domains such as language. Rotary position encoding (RoPE) has emerged as the de facto standard approach for position encoding and is part of many modern LLMs. However, in RoPE the key/query transformation between two elements in a sequence is only a function of their relative position and otherwise independent of the actual input. This limits the expressivity of RoPE-based transformers.
  This paper describes PaTH, a flexible data-dependent position encoding scheme based on accumulated products of Householder(like) transformations, where each transformation is data-dependent, i.e., a function of the input. We derive an efficient parallel algorithm for training through exploiting a compact representation of products of Householder matrices, and implement a FlashAttention-style blockwise algorithm that minimizes I/O cost. Across both targeted synthetic benchmarks and moderate-scale real-world language modeling experiments, we find that PaTH demonstrates superior performance compared to RoPE and other recent baselines.

[Arxiv](https://arxiv.org/abs/2505.16381)