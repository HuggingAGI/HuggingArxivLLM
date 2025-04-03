# Bhakti：为大型语言模型赋予语义搜索和记忆功能的轻量级向量数据库

发布时间：2025年04月02日

`LLM应用` `数据库` `问答系统`

> Bhakti: A Lightweight Vector Database Management System for Endowing Large Language Models with Semantic Search Capabilities and Memory

# 摘要

> 在大数据和人工智能技术飞速发展的推动下，向量数据的高效处理和检索需求日益增长。为此，我开发了Bhakti向量数据库，致力于为中小规模数据集提供一个轻量级、易于部署的解决方案，满足其存储和语义搜索需求。Bhakti不仅支持多种相似度计算方法，还提供特定领域语言（DSL），助力基于文档的模式匹配预过滤，凭借其可移植的数据文件、灵活的数据管理和与Python3的无缝集成，轻松实现数据迁移。此外，我提出了一种基于Bhakti数据库的内存增强型大语言模型对话解决方案，能够为对话历史中的问题和答案赋予不同权重，从而实现对单个对话历史中各段落语义重要性的精细控制。实验结果表明，该方法在语义搜索和问答系统中表现优异。尽管Bhakti目前不支持HNSW等近似计算方法，在处理大规模数据集时存在局限性，但其轻量化设计使其在中小规模数据集场景中具有显著优势。

> With the rapid development of big data and artificial intelligence technologies, the demand for effective processing and retrieval of vector data is growing. Against this backdrop, I have developed the Bhakti vector database, aiming to provide a lightweight and easy-to-deploy solution to meet the storage and semantic search needs of small and medium-sized datasets. Bhakti supports a variety of similarity calculation methods and a domain-specific language (DSL) for document-based pattern matching pre-filtering, facilitating migration of data with its portable data files, flexible data management and seamless integration with Python3. Furthermore, I propose a memory-enhanced large language model dialogue solution based on the Bhakti database, which can assign different weights to the question and answer in dialogue history, achieving fine-grained control over the semantic importance of each segment in a single dialogue history. Through experimental validation, my method shows significant performance in the application of semantic search and question-answering systems. Although there are limitations in processing large datasets, such as not supporting approximate calculation methods like HNSW, the lightweight nature of Bhakti gives it a clear advantage in scenarios involving small and medium-sized datasets.

[Arxiv](https://arxiv.org/abs/2504.01553)