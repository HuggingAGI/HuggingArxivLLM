# HiPerRAG：面向科学见解的高性能检索增强生成

发布时间：2025年05月07日

`RAG` `科学出版` `问答系统`

> HiPerRAG: High-Performance Retrieval Augmented Generation for Scientific Insights

# 摘要

> 科学文献呈指数级增长，导致大量发现被忽视、重复劳动和跨学科合作受限。RAG通过提升LLMs的事实准确性，为科学家提供了助力。然而，将RAG扩展到数百万篇文章面临解析文档和嵌入知识的高计算成本，以及语义对齐的复杂性。为此，我们推出HiPerRAG，一个基于HPC的RAG工作流，从360万篇科学文章中进行知识索引和检索。其核心是Oreo（多模态文档解析模型）和ColTrast（基于对比学习的检索优化算法）。HiPerRAG在SciQ和PubMedQA上分别达到90%和76%的准确率，超越了PubMedGPT和GPT-4。在超级计算机上扩展至数千个GPU，HiPerRAG实现了百万文档规模的RAG工作流，统一科学知识并促进跨学科创新。

> The volume of scientific literature is growing exponentially, leading to underutilized discoveries, duplicated efforts, and limited cross-disciplinary collaboration. Retrieval Augmented Generation (RAG) offers a way to assist scientists by improving the factuality of Large Language Models (LLMs) in processing this influx of information. However, scaling RAG to handle millions of articles introduces significant challenges, including the high computational costs associated with parsing documents and embedding scientific knowledge, as well as the algorithmic complexity of aligning these representations with the nuanced semantics of scientific content. To address these issues, we introduce HiPerRAG, a RAG workflow powered by high performance computing (HPC) to index and retrieve knowledge from more than 3.6 million scientific articles. At its core are Oreo, a high-throughput model for multimodal document parsing, and ColTrast, a query-aware encoder fine-tuning algorithm that enhances retrieval accuracy by using contrastive learning and late-interaction techniques. HiPerRAG delivers robust performance on existing scientific question answering benchmarks and two new benchmarks introduced in this work, achieving 90% accuracy on SciQ and 76% on PubMedQA-outperforming both domain-specific models like PubMedGPT and commercial LLMs such as GPT-4. Scaling to thousands of GPUs on the Polaris, Sunspot, and Frontier supercomputers, HiPerRAG delivers million document-scale RAG workflows for unifying scientific knowledge and fostering interdisciplinary innovation.

[Arxiv](https://arxiv.org/abs/2505.04846)