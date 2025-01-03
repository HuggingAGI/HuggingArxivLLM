# SynthCypher: 知识图谱中文本到Cypher查询的全合成数据生成框架

发布时间：2024年12月17日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLM）来生成和验证Cypher查询，并通过微调开源LLM来提升Text2Cypher任务的性能。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `图数据库`

> SynthCypher: A Fully Synthetic Data Generation Framework for Text-to-Cypher Querying in Knowledge Graphs

# 摘要

> Cypher作为Neo4j图数据库的查询语言，在图分析和数据探索中至关重要。尽管自然语言到SQL查询生成（Text2SQL）已有大量研究，但图数据库的Text2Cypher问题仍待深入探索。本研究推出SynthCypher，一个全合成自动化数据生成管道，填补了这一空白。SynthCypher采用创新的LLMSupervised生成-验证框架，确保跨领域和复杂度的Cypher查询在语法和语义上的准确性。通过这一管道，我们构建了包含29.8k个Text2Cypher实例的SynthCypher数据集。在SynthCypher上微调开源大型语言模型（如LLaMa-3.1-8B、Mistral-7B和QWEN-7B），在Text2Cypher测试集上实现了高达40%的性能提升，并在适配图数据库的SPIDER基准上提升了30%。这项研究表明，高质量合成数据能有效推动Text2Cypher任务的前沿发展。

> Cypher, the query language for Neo4j graph databases, plays a critical role in enabling graph-based analytics and data exploration. While substantial research has been dedicated to natural language to SQL query generation (Text2SQL), the analogous problem for graph databases referred to as Text2Cypher remains underexplored. In this work, we introduce SynthCypher, a fully synthetic and automated data generation pipeline designed to address this gap. SynthCypher employs a novel LLMSupervised Generation-Verification framework, ensuring syntactically and semantically correct Cypher queries across diverse domains and query complexities. Using this pipeline, we create SynthCypher Dataset, a large-scale benchmark containing 29.8k Text2Cypher instances. Fine-tuning open-source large language models (LLMs), including LLaMa-3.1- 8B, Mistral-7B, and QWEN-7B, on SynthCypher yields significant performance improvements of up to 40% on the Text2Cypher test set and 30% on the SPIDER benchmark adapted for graph databases. This work demonstrates that high-quality synthetic data can effectively advance the state-of-the-art in Text2Cypher tasks.

[Arxiv](https://arxiv.org/abs/2412.12612)