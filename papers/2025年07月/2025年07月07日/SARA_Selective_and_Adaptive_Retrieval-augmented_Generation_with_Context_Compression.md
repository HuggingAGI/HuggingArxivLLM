# SARA：结合上下文压缩的选择性与自适应检索增强生成

发布时间：2025年07月07日

`RAG` `人工智能`

> SARA: Selective and Adaptive Retrieval-augmented Generation with Context Compression

# 摘要

> 检索增强生成（RAG）通过引入外部知识扩展了大型语言模型（LLMs），但在实际应用中面临两个主要挑战：有限的有效上下文长度和检索文档中的冗余信息。单纯基于压缩的方法虽然能够减小输入规模，但常常会舍弃对事实准确性至关重要的细节。我们提出了SARA，一个统一的RAG框架，在严格的上下文预算下平衡局部精度与全局知识覆盖。SARA结合自然语言文本片段与语义压缩向量，协同提升上下文效率和回答准确性。它从两个互补层次表示上下文：1）细粒度的自然语言片段，保留关键实体和数值；2）紧凑且可解释的向量，总结高层次语义。迭代证据选择模块利用压缩向量对上下文进行动态重排序。在涵盖3个模型家族（Mistral、Llama 和 Gemma）的9个数据集和5个开源LLM上，SARA持续提升了回答相关性（+17.71）、准确性（+13.72）和语义相似度（+15.53），证明了将文本表示与压缩表示相结合对于构建稳健且上下文高效的RAG系统的重要性。


> Retrieval-augmented Generation (RAG) extends large language models (LLMs) with external knowledge but faces key challenges: restricted effective context length and redundancy in retrieved documents. Pure compression-based approaches reduce input size but often discard fine-grained details essential for factual accuracy. We propose SARA, a unified RAG framework that balances local precision and global knowledge coverage under tight context budgets. SARA combines natural-language text snippets with semantic compression vectors to jointly enhance context efficiency and answer correctness. It represents contexts at two complementary levels: 1) fine-grained natural-language spans that preserve critical entities and numerical values, and 2) compact, interpretable vectors that summarize high-level semantics. An iterative evidence-selection module employs the compression vectors for dynamic reranking of contexts. Across 9 datasets and 5 open-source LLMs spanning 3 model families (Mistral, Llama, and Gemma), SARA consistently improves answer relevance (+17.71), answer correctness (+13.72), and semantic similarity (+15.53), demonstrating the importance of integrating textual and compressed representations for robust, context-efficient RAG.

[Arxiv](https://arxiv.org/abs/2507.05633)