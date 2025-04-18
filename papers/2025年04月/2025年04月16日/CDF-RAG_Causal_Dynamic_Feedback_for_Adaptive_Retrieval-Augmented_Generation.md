# CDF-RAG：因果动态反馈实现自适应检索增强生成

发布时间：2025年04月16日

`RAG` `知识图谱` `因果推理`

> CDF-RAG: Causal Dynamic Feedback for Adaptive Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过整合外部知识检索，显著提升了大型语言模型（LLMs）在知识密集型任务中的表现。然而，现有的RAG框架主要依赖于语义相似性和相关性驱动的检索方式，限制了它们区分真实因果关系与虚假关联的能力。这导致生成的响应虽然可能基于事实，却未能建立因果机制，从而产生不完整或误导性的见解。为了解决这一问题，我们引入了因果动态反馈驱动的自适应检索增强生成框架（CDF-RAG），旨在提升生成推理中的因果一致性、事实准确性以及可解释性。CDF-RAG通过迭代优化查询、检索结构化因果图，并支持跨互联知识源的多跳因果推理。此外，它还通过验证响应与因果路径的一致性，确保输出的逻辑连贯性和事实依据性。我们在四个多样化的数据集上评估了CDF-RAG，结果表明其在提升响应准确性和因果正确性方面优于现有的基于RAG的方法。我们的代码可在https://github.com/elakhatibi/CDF-RAG公开获取。

> Retrieval-Augmented Generation (RAG) has significantly enhanced large language models (LLMs) in knowledge-intensive tasks by incorporating external knowledge retrieval. However, existing RAG frameworks primarily rely on semantic similarity and correlation-driven retrieval, limiting their ability to distinguish true causal relationships from spurious associations. This results in responses that may be factually grounded but fail to establish cause-and-effect mechanisms, leading to incomplete or misleading insights. To address this issue, we introduce Causal Dynamic Feedback for Adaptive Retrieval-Augmented Generation (CDF-RAG), a framework designed to improve causal consistency, factual accuracy, and explainability in generative reasoning. CDF-RAG iteratively refines queries, retrieves structured causal graphs, and enables multi-hop causal reasoning across interconnected knowledge sources. Additionally, it validates responses against causal pathways, ensuring logically coherent and factually grounded outputs. We evaluate CDF-RAG on four diverse datasets, demonstrating its ability to improve response accuracy and causal correctness over existing RAG-based methods. Our code is publicly available at https://github.com/ elakhatibi/CDF-RAG.

[Arxiv](https://arxiv.org/abs/2504.12560)