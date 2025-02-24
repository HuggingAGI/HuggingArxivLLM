# DReSD：基于密集检索的推测性解码方法

发布时间：2025年02月21日

`LLM应用` `生成模型`

> DReSD: Dense Retrieval for Speculative Decoding

# 摘要

> 推测解码（SD）通过高效草稿模型提出接下来的几个tokens，并由LLM在一次前向调用中验证，从而加速大型语言模型（LLM）生成，同时降低延迟并保持输出质量。我们专注于基于检索的SD，其中草稿模型从非参数化数据集中检索接下来的tokens。目前，基于字符串表面形式的稀疏检索（REST）是主流范式，因其简单性和可扩展性而占据主导地位。然而，由于使用了短上下文和精确字符串匹配，其有效性受到限制。因此，我们引入了Dense Retrieval for Speculative Decoding（DReSD），这是一个新颖的框架，通过上下文化token嵌入的近邻搜索，检索出最语义相关的token序列用于SD。大量实验表明，与稀疏检索（REST）相比，DReSD实现了平均87%更高的接受率、65%更长的接受token长度以及19%更快的生成速度。

> Speculative decoding (SD) accelerates Large Language Model (LLM) generation by using an efficient draft model to propose the next few tokens, which are verified by the LLM in a single forward call, reducing latency while preserving its outputs. We focus on retrieval-based SD where the draft model retrieves the next tokens from a non-parametric datastore. Sparse retrieval (REST), which operates on the surface form of strings, is currently the dominant paradigm due to its simplicity and scalability. However, its effectiveness is limited due to the usage of short contexts and exact string matching. Instead, we introduce Dense Retrieval for Speculative Decoding (DReSD), a novel framework that uses approximate nearest neighbour search with contextualised token embeddings to retrieve the most semantically relevant token sequences for SD. Extensive experiments show that DReSD achieves (on average) 87% higher acceptance rates, 65% longer accepted tokens and 19% faster generation speeds compared to sparse retrieval (REST).

[Arxiv](https://arxiv.org/abs/2502.15572)