# LongSpec：长上下文推测性解码，通过高效草稿生成与验证实现

发布时间：2025年02月24日

`LLM应用` `软件工程`

> LongSpec: Long-Context Speculative Decoding with Efficient Drafting and Verification

# 摘要

> Speculative decoding 成为缓解大型语言模型 (LLMs) 自回归解码高延迟的有力技术。尽管如此，其在 LLMs 中的实际应用仍面临三大挑战：草稿模型内存需求激增、短训练语料与长上下文推理间的分布偏差，以及注意力机制实现效率低下。本研究针对这些挑战，提升 long-context 场景下 speculative decoding 的效能。首先，我们推出内存优化的草稿模型，配备固定大小的键值缓存 (KV)。其次，为短训练数据设计新颖的位置索引，实现从短上下文训练到长上下文推理的无缝衔接。最后，创新性地提出注意力聚合方法，结合前缀计算的快速实现与标准注意力处理树状掩码，有效破解树形解码的延迟与内存瓶颈。我们的方案在仓库级代码补全、长上下文摘要及类 o1 长推理等任务中表现卓越，显著降低了延迟。代码已开源，欢迎访问 https://github.com/sail-sg/LongSpec 查看。


> Speculative decoding has become a promising technique to mitigate the high inference latency of autoregressive decoding in Large Language Models (LLMs). Despite its promise, the effective application of speculative decoding in LLMs still confronts three key challenges: the increasing memory demands of the draft model, the distribution shift between the short-training corpora and long-context inference, and inefficiencies in attention implementation. In this work, we enhance the performance of speculative decoding in long-context settings by addressing these challenges. First, we propose a memory-efficient draft model with a constant-sized Key-Value (KV) cache. Second, we introduce novel position indices for short-training data, enabling seamless adaptation from short-context training to long-context inference. Finally, we present an innovative attention aggregation method that combines fast implementations for prefix computation with standard attention for tree mask handling, effectively resolving the latency and memory inefficiencies of tree decoding. Our approach achieves strong results on various long-context tasks, including repository-level code completion, long-context summarization, and o1-like long reasoning tasks, demonstrating significant improvements in latency reduction. The code is available at https://github.com/sail-sg/LongSpec.

[Arxiv](https://arxiv.org/abs/2502.17421)