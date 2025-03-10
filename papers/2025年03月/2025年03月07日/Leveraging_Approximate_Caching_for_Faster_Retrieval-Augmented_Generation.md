# # 借助近似缓存加速检索增强生成

发布时间：2025年03月07日

`RAG` `计算机系统`

> Leveraging Approximate Caching for Faster Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识显著提升了大型语言模型（LLM）答案的可靠性。然而，由于从大型向量数据库中查找相关文档是一项计算成本高昂的任务，RAG增加了端到端推理时间。为了解决这一问题，我们提出了名为Proximity的近似键值缓存机制，旨在通过利用用户查询之间的相似性来优化RAG工作流。与传统的独立处理每个查询的方式不同，Proximity在遇到相似查询时会复用之前检索到的文档，从而减少了对昂贵的向量数据库查找的依赖。我们在MMLU和MedRAG基准测试中对Proximity进行了评估，结果表明它在保持响应准确性的同时，显著提升了检索效率。Proximity将检索延迟降低了高达59%，同时保持了准确性，并降低了向量数据库的计算负担。我们还实验了不同的相似度阈值，并量化了速度与召回率之间的权衡。我们的研究表明，近似缓存是一种既可行又有效的优化RAG系统的方法。

> Retrieval-augmented generation (RAG) enhances the reliability of large language model (LLM) answers by integrating external knowledge. However, RAG increases the end-to-end inference time since looking for relevant documents from large vector databases is computationally expensive. To address this, we introduce Proximity, an approximate key-value cache that optimizes the RAG workflow by leveraging similarities in user queries. Instead of treating each query independently, Proximity reuses previously retrieved documents when similar queries appear, reducing reliance on expensive vector database lookups. We evaluate Proximity on the MMLU and MedRAG benchmarks, demonstrating that it significantly improves retrieval efficiency while maintaining response accuracy. Proximity reduces retrieval latency by up to 59% while maintaining accuracy and lowers the computational burden on the vector database. We also experiment with different similarity thresholds and quantify the trade-off between speed and recall. Our work shows that approximate caching is a viable and effective strategy for optimizing RAG-based systems.

[Arxiv](https://arxiv.org/abs/2503.05530)