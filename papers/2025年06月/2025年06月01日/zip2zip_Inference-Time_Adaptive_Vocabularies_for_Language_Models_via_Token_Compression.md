# zip2zip: 借助分词压缩技术，构建语言模型推理过程中的自适应词汇表

发布时间：2025年06月01日

`LLM理论` `机器学习`

> zip2zip: Inference-Time Adaptive Vocabularies for Language Models via Token Compression

# 摘要

> 分词效率对大型语言模型 (LLMs) 的性能和成本至关重要。然而，大多数模型依赖于针对通用语料库优化的静态分词器，这些分词器的固定词汇表通常无法适应特定领域或语言的输入，导致更长的分词序列和更高的计算成本。我们引入了 zip2zip 框架，它允许 LLM 在推理时动态调整分词词汇表，从而减少生成的分词数量，实现更快的推理速度。

zip2zip 框架由三个关键组件构成：(1) 基于 Lempel-Ziv-Welch (LZW) 压缩算法的分词器，能够在推理过程中逐步将分词压缩为可重复使用的“超级分词”；(2) 一个嵌入层，用于在运行时为新生成的超级分词计算嵌入向量；(3) 一种因果语言模型变体，用于训练模型处理经过超级分词压缩的序列。

我们展示了通过参数高效的微调，现有 LLM 可以在 10 个 GPU 小时内被转换为 zip2zip 模型。经过转换的 zip2zip LLM 能够有效学习在推理时使用超级分词，将输入和输出序列长度减少 20-60%，同时显著提升推理延迟表现。


> Tokenization efficiency plays a critical role in the performance and cost of large language models (LLMs), yet most models rely on static tokenizers optimized for general-purpose corpora. These tokenizers' fixed vocabularies often fail to adapt to domain- or language-specific inputs, leading to longer token sequences and higher computational costs. We introduce zip2zip, a framework that enables LLMs to dynamically adjust token vocabulary at inference time, allowing for fewer generated tokens and thus faster inference. zip2zip consists of three key components: (1) a tokenizer based on Lempel-Ziv-Welch (LZW) compression that incrementally compresses tokens into reusable "hypertokens" on the fly; (2) an embedding layer that computes embeddings for newly formed hypertokens at runtime; and (3) a causal language modeling variant that trains the model to operate on hypertokenized, compressed sequences. We show that an existing LLM can be zip2zip-fied in 10 GPU-hours via parameter-efficient finetuning. The resulting zip2zip LLMs effectively learn to use hypertokens at inference time, reducing input and output sequence length by 20-60\%, with significant improvements in inference latency.

[Arxiv](https://arxiv.org/abs/2506.01084)