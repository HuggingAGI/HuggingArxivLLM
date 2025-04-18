# **HM-RAG：多模态分层多智能体增强生成**

发布时间：2025年04月13日

`RAG

理由：这篇论文主要探讨了检索增强生成（RAG）框架的改进，提出了一个层级多智能体多模态的RAG系统，专注于解决复杂查询和多模态推理的问题，属于RAG领域的研究。` `多模态` `知识合成`

> HM-RAG: Hierarchical Multi-Agent Multimodal Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）虽然增强了大型语言模型（LLMs）的知识储备，但传统的单智能体RAG在处理复杂查询时仍存在局限性，尤其在需要跨异构数据生态协同推理的情况下。为此，我们提出了HM-RAG——一个创新的层级多智能体多模态RAG框架，致力于实现跨结构化、非结构化和图基数据的动态知识合成协作智能。该框架由三层次架构组成，配备专用智能体：分解智能体通过语义感知的查询重写和模式引导的上下文增强，将复杂查询分解为语义连贯的子任务；多源检索智能体利用专为向量、图和网络数据库设计的即插即用模块，执行并行的模态特定检索；决策智能体则通过一致性投票整合多源答案，并借助专家模型精炼解决检索结果中的不一致。该架构通过整合文本、图关系和网络来源的证据，实现了对查询的全面理解。在ScienceQA和CrisisMMD基准测试中，相比基线RAG系统，HM-RAG在答案准确率上提升了12.95%，问题分类准确率提高了3.56%。值得注意的是，HM-RAG在零样本设置下于两个数据集均达到了最新技术水平。其模块化架构确保了新数据模态的无缝集成，同时严格遵守数据治理规范，标志着在解决RAG系统中多模态推理和知识合成关键挑战方面取得了重大进展。代码可在https://github.com/ocean-luna/HMRAG获取。

> While Retrieval-Augmented Generation (RAG) augments Large Language Models (LLMs) with external knowledge, conventional single-agent RAG remains fundamentally limited in resolving complex queries demanding coordinated reasoning across heterogeneous data ecosystems. We present HM-RAG, a novel Hierarchical Multi-agent Multimodal RAG framework that pioneers collaborative intelligence for dynamic knowledge synthesis across structured, unstructured, and graph-based data. The framework is composed of three-tiered architecture with specialized agents: a Decomposition Agent that dissects complex queries into contextually coherent sub-tasks via semantic-aware query rewriting and schema-guided context augmentation; Multi-source Retrieval Agents that carry out parallel, modality-specific retrieval using plug-and-play modules designed for vector, graph, and web-based databases; and a Decision Agent that uses consistency voting to integrate multi-source answers and resolve discrepancies in retrieval results through Expert Model Refinement. This architecture attains comprehensive query understanding by combining textual, graph-relational, and web-derived evidence, resulting in a remarkable 12.95% improvement in answer accuracy and a 3.56% boost in question classification accuracy over baseline RAG systems on the ScienceQA and CrisisMMD benchmarks. Notably, HM-RAG establishes state-of-the-art results in zero-shot settings on both datasets. Its modular architecture ensures seamless integration of new data modalities while maintaining strict data governance, marking a significant advancement in addressing the critical challenges of multimodal reasoning and knowledge synthesis in RAG systems. Code is available at https://github.com/ocean-luna/HMRAG.

[Arxiv](https://arxiv.org/abs/2504.12330)