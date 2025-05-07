# RetroInfer：面向大规模长上下文LLM推理的向量存储方法

发布时间：2025年05月05日

`LLM应用` `人工智能`

> RetroInfer: A Vector-Storage Approach for Scalable Long-Context LLM Inference

# 摘要

> 大型语言模型（LLMs）上下文长度的不断增长为高效推理带来了巨大挑战，主要受限于GPU内存和带宽。我们推出RetroInfer，一个全新系统，将关键-值（KV）缓存重新构想为向量存储系统，利用固有注意力稀疏性加速长上下文LLM推理。其核心是感知注意力的波浪索引，通过三元注意力近似、精度有界注意力估计和分段聚类技术，实现关键令牌的高效准确检索。波浪缓冲区则负责协调KV缓存位置，并跨GPU和CPU重叠计算与数据传输，维持高吞吐量。与之前基于稀疏性的方法不同，RetroInfer无需在模型准确性上妥协，即可实现强大性能。实验结果显示，在长上下文基准测试中，RetroInfer在GPU内存限制下比完全注意力快4.5倍，扩展KV缓存到CPU内存时，比稀疏注意力基线快10.5倍，同时保持完全注意力级别的准确性。

> The growing context lengths of large language models (LLMs) pose significant challenges for efficient inference, primarily due to GPU memory and bandwidth constraints. We present RetroInfer, a novel system that reconceptualizes the key-value (KV) cache as a vector storage system which exploits the inherent attention sparsity to accelerate long-context LLM inference. At its core is the wave index, an Attention-aWare VEctor index that enables efficient and accurate retrieval of critical tokens through techniques such as tripartite attention approximation, accuracy-bounded attention estimation, and segmented clustering. Complementing this is the wave buffer, which coordinates KV cache placement and overlaps computation and data transfer across GPU and CPU to sustain high throughput. Unlike prior sparsity-based methods that struggle with token selection and hardware coordination, RetroInfer delivers robust performance without compromising model accuracy. Experiments on long-context benchmarks show up to 4.5X speedup over full attention within GPU memory limits and up to 10.5X over sparse attention baselines when KV cache is extended to CPU memory, all while preserving full-attention-level accuracy.

[Arxiv](https://arxiv.org/abs/2505.02922)