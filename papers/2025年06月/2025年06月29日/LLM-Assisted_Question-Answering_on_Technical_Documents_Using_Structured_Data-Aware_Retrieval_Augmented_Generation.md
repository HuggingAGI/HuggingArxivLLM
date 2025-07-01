# 基于LLM的结构化数据增强检索生成方法在技术文档问答系统中的应用

发布时间：2025年06月29日

`RAG` `技术文档处理` `问答系统`

> LLM-Assisted Question-Answering on Technical Documents Using Structured Data-Aware Retrieval Augmented Generation

# 摘要

> 大型语言模型（LLMs）虽然具备自然语言理解和生成能力，但存在幻觉和知识过时等问题。微调虽能解决部分问题，却因资源消耗大且需频繁更新而实用性受限。检索增强生成（RAG）提供了一种更高效的方式，让LLMs能够访问外部知识源。然而，传统RAG流水线在处理包含表格和图像等结构化数据的复杂技术文档时表现不佳。针对这一问题，我们提出了一种新型RAG流水线，专门处理支持扫描和可搜索格式的技术文档中的表格和图像。该流水线的检索机制融合了向量相似度搜索和基于Gemma-2-9b-it的微调重排序器。通过在专门设计的RAFT数据集上进行训练，重排序器显著提升了问答任务中的上下文识别能力。实验结果表明，我们的流水线在忠实度和相关性方面表现优异，分别达到了94%（RAGas）/96%（DeepEval）和87%（RAGas）/93%（DeepEval）的高分。与传统RAG流水线相比，我们的架构在处理基于表格的问题和上下文外问题时更具优势。
    

> Large Language Models (LLMs) are capable of natural language understanding and generation. But they face challenges such as hallucination and outdated knowledge. Fine-tuning is one possible solution, but it is resource-intensive and must be repeated with every data update. Retrieval-Augmented Generation (RAG) offers an efficient solution by allowing LLMs to access external knowledge sources. However, traditional RAG pipelines struggle with retrieving information from complex technical documents with structured data such as tables and images. In this work, we propose a RAG pipeline, capable of handling tables and images in documents, for technical documents that support both scanned and searchable formats. Its retrieval process combines vector similarity search with a fine-tuned reranker based on Gemma-2-9b-it. The reranker is trained using RAFT (Retrieval-Augmented Fine-Tuning) on a custom dataset designed to improve context identification for question answering. Our evaluation demonstrates that the proposed pipeline achieves a high faithfulness score of 94% (RAGas) and 96% (DeepEval), and an answer relevancy score of 87% (RAGas) and 93% (DeepEval). Comparative analysis demonstrates that the proposed architecture is superior to general RAG pipelines in terms of table-based questions and handling questions outside context.

[Arxiv](https://arxiv.org/abs/2506.23136)