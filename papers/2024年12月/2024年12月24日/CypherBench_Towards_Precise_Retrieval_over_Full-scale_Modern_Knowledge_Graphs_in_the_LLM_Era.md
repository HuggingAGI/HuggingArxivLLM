# CypherBench：LLM时代下全规模现代知识图谱的精准检索

发布时间：2024年12月24日

`RAG

理由：这篇论文主要讨论了如何通过构建属性图视图和使用Cypher查询来增强LLM对现代百科全书式知识图谱（如Wikidata）的检索能力。这涉及到图数据检索和知识图谱的应用，属于RAG（Retrieval-Augmented Generation）的范畴，因为RAG的核心思想是通过检索外部知识来增强生成模型的能力。论文中提到的GraphRAG系统也进一步支持了这一分类。` `知识图谱` `数据检索`

> CypherBench: Towards Precise Retrieval over Full-scale Modern Knowledge Graphs in the LLM Era

# 摘要

> # 摘要
图数据检索对于增强LLM的开放领域知识和私有企业数据至关重要，也是GraphRAG系统（edge等人，2024）的核心组件。尽管知识图谱和知识库问答研究已有数十年，但主流LLM框架（如Langchain和LlamaIndex）对现代百科全书式知识图谱（如Wikidata）的检索支持有限。本文分析了这一现象的根本原因，指出现代RDF知识图谱（如Wikidata、Freebase）因模式过大、资源标识符使用、关系类型重叠及缺乏规范化，导致对LLM效率低下。为此，我们提出在RDF图之上构建属性图视图，并通过Cypher实现高效查询。我们在Wikidata上实现了这一方案，并推出了CypherBench，这是首个包含11个大规模、多领域属性图的基准，涵盖780万个实体和超过10,000个问题。为实现这一目标，我们攻克了多个关键挑战，包括开发RDF到属性图的转换引擎、构建文本到Cypher任务的系统化生成管道，以及设计新的评估指标。

> Retrieval from graph data is crucial for augmenting large language models (LLM) with both open-domain knowledge and private enterprise data, and it is also a key component in the recent GraphRAG system (edge et al., 2024). Despite decades of research on knowledge graphs and knowledge base question answering, leading LLM frameworks (e.g. Langchain and LlamaIndex) have only minimal support for retrieval from modern encyclopedic knowledge graphs like Wikidata. In this paper, we analyze the root cause and suggest that modern RDF knowledge graphs (e.g. Wikidata, Freebase) are less efficient for LLMs due to overly large schemas that far exceed the typical LLM context window, use of resource identifiers, overlapping relation types and lack of normalization. As a solution, we propose property graph views on top of the underlying RDF graph that can be efficiently queried by LLMs using Cypher. We instantiated this idea on Wikidata and introduced CypherBench, the first benchmark with 11 large-scale, multi-domain property graphs with 7.8 million entities and over 10,000 questions. To achieve this, we tackled several key challenges, including developing an RDF-to-property graph conversion engine, creating a systematic pipeline for text-to-Cypher task generation, and designing new evaluation metrics.

[Arxiv](https://arxiv.org/abs/2412.18702)