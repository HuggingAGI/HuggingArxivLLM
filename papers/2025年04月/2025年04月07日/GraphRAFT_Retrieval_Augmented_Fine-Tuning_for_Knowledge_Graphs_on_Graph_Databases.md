# GraphRAFT：图数据库上的知识图谱检索增强微调方法

发布时间：2025年04月07日

`RAG` `知识图谱` `问答系统`

> GraphRAFT: Retrieval Augmented Fine-Tuning for Knowledge Graphs on Graph Databases

# 摘要

> 大型语言模型在语言处理和推理方面表现出色，但面对私人数据时容易出错。检索增强生成（RAG）通过从大型语言模型（LLM）的上下文窗口中检索相关数据，并提示LLM生成答案。GraphRAG将此方法扩展至结构化知识图谱（KGs），并能处理涉及多个跳转实体的问题。然而，目前大多数GraphRAG方法要么忽视了检索步骤，要么采用了抽象或低效的检索过程，这使得它们难以应用于存储在支持图查询语言的图数据库中的KGs。在此工作中，我们提出了GraphRAFT，一个检索与推理框架，它微调了LLMs以生成可证明正确的Cypher查询，从而检索高质量的子图上下文并生成准确的答案。我们的方法是首个可直接应用于存储在原生图数据库中的KGs的解决方案。基准测试表明，我们的方法在训练数据可用性方面具有样本效率和可扩展性。在两个具有挑战性的大型文本属性KGs的问答任务上，我们的方法在四个标准指标上均显著优于所有现有最先进模型。


> Large language models have shown remarkable language processing and reasoning ability but are prone to hallucinate when asked about private data. Retrieval-augmented generation (RAG) retrieves relevant data that fit into an LLM's context window and prompts the LLM for an answer. GraphRAG extends this approach to structured Knowledge Graphs (KGs) and questions regarding entities multiple hops away. The majority of recent GraphRAG methods either overlook the retrieval step or have ad hoc retrieval processes that are abstract or inefficient. This prevents them from being adopted when the KGs are stored in graph databases supporting graph query languages. In this work, we present GraphRAFT, a retrieve-and-reason framework that finetunes LLMs to generate provably correct Cypher queries to retrieve high-quality subgraph contexts and produce accurate answers. Our method is the first such solution that can be taken off-the-shelf and used on KGs stored in native graph DBs. Benchmarks suggest that our method is sample-efficient and scales with the availability of training data. Our method achieves significantly better results than all state-of-the-art models across all four standard metrics on two challenging Q\&As on large text-attributed KGs.

[Arxiv](https://arxiv.org/abs/2504.05478)