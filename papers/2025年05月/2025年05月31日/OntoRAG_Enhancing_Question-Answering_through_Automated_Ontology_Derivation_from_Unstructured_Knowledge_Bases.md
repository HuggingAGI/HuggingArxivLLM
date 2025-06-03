# OntoRAG：从非结构化知识库自动推导本体，提升问答能力

发布时间：2025年05月31日

`RAG` `电气工程` `知识库`

> OntoRAG: Enhancing Question-Answering through Automated Ontology Derivation from Unstructured Knowledge Bases

# 摘要

> 本体论在构建知识库中发挥着关键作用，有助于提升大型语言模型（LLMs）驱动的问题回答（QA）系统的性能。然而，传统本体论的创建依赖于领域专家的手动努力，这一过程耗时费力，容易出错，且难以应对大规模动态知识领域。本文提出了一种名为OntoRAG的自动化管道，旨在从非结构化知识库中提取本体论，特别关注于电气继电器文档。OntoRAG集成了多种先进技术，包括网络抓取、PDF解析、混合分块、信息提取、知识图谱构建和本体论创建，将非结构化数据转化为可查询的本体论。通过结合LLMs和基于图的方法，OntoRAG显著提升了全局语义理解能力，在全面性和多样性方面超越了传统的检索增强生成（RAG）和GraphRAG方法。实验结果表明，OntoRAG在与基于向量的RAG对比中，全面性胜率达到了85%，而在与GraphRAG的最佳配置对比中，胜率达到了75%。这项研究成功解决了自动化本体论创建的关键挑战，为实现语义网络的愿景迈出了重要一步。

> Ontologies are pivotal for structuring knowledge bases to enhance question answering (QA) systems powered by Large Language Models (LLMs). However, traditional ontology creation relies on manual efforts by domain experts, a process that is time intensive, error prone, and impractical for large, dynamic knowledge domains. This paper introduces OntoRAG, an automated pipeline designed to derive ontologies from unstructured knowledge bases, with a focus on electrical relay documents. OntoRAG integrates advanced techniques, including web scraping, PDF parsing, hybrid chunking, information extraction, knowledge graph construction, and ontology creation, to transform unstructured data into a queryable ontology. By leveraging LLMs and graph based methods, OntoRAG enhances global sensemaking capabilities, outperforming conventional Retrieval Augmented Generation (RAG) and GraphRAG approaches in comprehensiveness and diversity. Experimental results demonstrate OntoRAGs effectiveness, achieving a comprehensiveness win rate of 85% against vector RAG and 75% against GraphRAGs best configuration. This work addresses the critical challenge of automating ontology creation, advancing the vision of the semantic web.

[Arxiv](https://arxiv.org/abs/2506.00664)