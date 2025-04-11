# ConceptFormer：迈向大型语言模型中知识图谱嵌入的高效应用

发布时间：2025年04月10日

`RAG

理由：该论文专注于检索增强生成（RAG）方法，提出了一种新的技术来改进现有的RAG方法，通过直接利用知识图谱中的结构化知识，显著提升了模型的事实召回能力。因此，这篇论文属于RAG分类。` `知识图谱`

> ConceptFormer: Towards Efficient Use of Knowledge-Graph Embeddings in Large Language Models

# 摘要

> 检索增强生成（RAG）近年来备受关注，大型语言模型（LLMs）的最新进展凸显了将世界知识融入系统的重要性。现有的RAG方法通常通过修改预训练语言模型（PLMs）的架构或依赖知识图谱（KGs）的文本化处理来实现，这种方式在token使用效率上存在明显不足。本文提出了一种名为ConceptFormer的新方法，它能够直接利用知识图谱（如Wikidata）中的结构化知识增强LLMs，无需修改模型结构或依赖KGs的文本输入。ConceptFormer在LLMs的嵌入向量空间中运行，通过创建并注入\emph{概念向量}，直接封装KG节点的信息。与冻结的LLM联合训练，ConceptFormer生成一个全面的查找表，将KG节点映射到各自的概念向量。这种方法通过使LLMs能够原生处理概念向量，显著提升了模型的事实召回能力，以高效且可扩展的方式将结构化知识注入模型。实验结果显示，将概念向量加入GPT-2 0.1B后，在维基百科句子上，其事实召回能力（Hit@10）提升了272%，在合成生成的句子上更是提升了348%。即使仅在提示中注入一个概念向量，也能使维基百科句子的事实召回能力提升213%，显著超越了基于图文本化的RAG方法，同时仅消耗了1/130的输入token数量。

> Retrieval Augmented Generation (RAG) has enjoyed increased attention in the recent past and recent advancements in Large Language Models (LLMs) have highlighted the importance of integrating world knowledge into these systems. Current RAG methodologies often modify the internal architecture of pre-trained language models (PLMs) or rely on textifying knowledge graphs (KGs), which is inefficient in terms of token usage. This paper introduces ConceptFormer, a new approach to augment LLMs with structured knowledge from KGs, such as Wikidata, without altering their internal structure or relying on textual input of KGs. ConceptFormer operates in the LLM embedding vector space, creating and injecting \emph{concept vectors} that encapsulate the information of the KG nodes directly. Trained in conjunction with a frozen LLM, ConceptFormer generates a comprehensive lookup table that maps KG nodes to their respective concept vectors. The approach aims to enhance the factual recall capabilities of LLMs by enabling them to process these concept vectors natively, thus enriching them with structured world knowledge in an efficient and scalable manner. Our experiments demonstrate that the addition of concept vectors to GPT-2 0.1B substantially increases its factual recall ability (Hit@10) by up to 272\% when tested on sentences from Wikipedia and up to 348\% on synthetically generated sentences. Even injecting only a single concept vector into the prompt increases factual recall ability (Hit@10) by up to 213\% on Wikipedia sentences, significantly outperforming RAG with graph textification while consuming 130x fewer input tokens.

[Arxiv](https://arxiv.org/abs/2504.07624)