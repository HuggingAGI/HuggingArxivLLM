# 超越 RAG：任务感知 KV 缓存压缩实现全面知识推理

发布时间：2025年03月06日

`RAG` `知识管理`

> Beyond RAG: Task-Aware KV Cache Compression for Comprehensive Knowledge Reasoning

# 摘要

> 将外部知识融入大型语言模型（LLMs）能够提升其在多种应用中的实用性，但现有方法各有优劣。检索增强生成（RAG）通过相似性搜索获取证据，但关键信息可能不在 top ranked 结果中。长上下文模型可以处理多个文档，但计算成本高昂且受限于上下文窗口大小。受学生为开卷考试浓缩学习材料的启发，我们提出了一种任务感知的键值（KV）缓存压缩方法，能够在零样本或少样本设置下压缩外部知识。这使 LLMs 能够高效地对所有相关信息的紧致表示进行推理。实验表明，我们的方法在性能上优于 RAG 和任务不可知的压缩方法。在 LongBench v2 上，与 RAG 相比，压缩率提升 30 倍的同时，准确率提高了 7 个绝对点，推理延迟从 0.43 秒降至 0.16 秒。合成数据集的实验结果表明，当稀疏证据足以解决问题时，RAG 表现良好，但对于需要广泛知识的任务，任务感知压缩方法更胜一筹。

> Incorporating external knowledge in large language models (LLMs) enhances their utility across diverse applications, but existing methods have trade-offs. Retrieval-Augmented Generation (RAG) fetches evidence via similarity search, but key information may fall outside top ranked results. Long-context models can process multiple documents but are computationally expensive and limited by context window size. Inspired by students condensing study material for open-book exams, we propose task-aware key-value (KV) cache compression, which compresses external knowledge in a zero- or few-shot setup. This enables LLMs to reason efficiently over a compacted representation of all relevant information. Experiments show our approach outperforms both RAG and task-agnostic compression methods. On LongBench v2, it improves accuracy by up to 7 absolute points over RAG with a 30x compression rate, while reducing inference latency from 0.43s to 0.16s. A synthetic dataset highlights that RAG performs well when sparse evidence suffices, whereas task-aware compression is superior for broad knowledge tasks.

[Arxiv](https://arxiv.org/abs/2503.04973)