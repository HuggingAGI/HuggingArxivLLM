# UiS-IAI@LiveRAG：基于检索增强信息片段的响应生成

发布时间：2025年06月27日

`RAG` `信息检索` `问答系统`

> UiS-IAI@LiveRAG: Retrieval-Augmented Information Nugget-Based Generation of Responses

# 摘要

> 基于检索增强的生成（RAG）在事实准确性、来源归属和响应完整性方面面临诸多挑战。SIGIR'25大会举办的LiveRAG挑战赛旨在利用固定语料库和共享开源LLM推动RAG研究。我们提出了一种基于信息块（从检索文档中提取的最小相关信息单元）的模块化流水线。这一多阶段流水线包括查询改写、段落检索与重排序、信息块检测与聚类、聚类排序与摘要，以及响应流畅度提升。这种设计天然促进了对具体事实的依据，便于来源归属，并在长度限制内确保最大信息量的纳入。在本次挑战中，我们扩展了研究范围，同时关注RAG的检索组件，基于我们此前在多维度查询改写方面的研究。此外，在增强生成方面，我们专注于提升上下文整理能力，在保证流水线效率的同时，最大化响应中涵盖的信息广度。我们的结果显示，结合原始查询与少量子查询改写能提升召回率，而超过一定数量后，用于重排序和生成的文档数量增加会降低效果，同时不会改善响应质量。

> Retrieval-augmented generation (RAG) faces challenges related to factual correctness, source attribution, and response completeness. The LiveRAG Challenge hosted at SIGIR'25 aims to advance RAG research using a fixed corpus and a shared, open-source LLM. We propose a modular pipeline that operates on information nuggets-minimal, atomic units of relevant information extracted from retrieved documents. This multistage pipeline encompasses query rewriting, passage retrieval and reranking, nugget detection and clustering, cluster ranking and summarization, and response fluency enhancement. This design inherently promotes grounding in specific facts, facilitates source attribution, and ensures maximum information inclusion within length constraints. In this challenge, we extend our focus to also address the retrieval component of RAG, building upon our prior work on multi-faceted query rewriting. Furthermore, for augmented generation, we concentrate on improving context curation capabilities, maximizing the breadth of information covered in the response while ensuring pipeline efficiency. Our results show that combining original queries with a few sub-query rewrites boosts recall, while increasing the number of documents used for reranking and generation beyond a certain point reduces effectiveness, without improving response quality.

[Arxiv](https://arxiv.org/abs/2506.22210)