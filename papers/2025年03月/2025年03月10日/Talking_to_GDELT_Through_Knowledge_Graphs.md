# # 用知识图谱对话 GDELT

发布时间：2025年03月10日

`RAG` `全球事件分析` `问答系统`

> Talking to GDELT Through Knowledge Graphs

# 摘要

> 本研究深入探讨了多种检索增强生成（RAG）方法，旨在揭示它们在问答分析中的独特优缺点。我们采用全球事件、语言与语调数据库（GDELT）的案例子集，并结合从在线新闻中提取的原始文本语料库，作为研究基础。在信息检索方面，我们不仅实现了传统的向量存储RAG方法，还引入了基于大型语言模型（LLM）的最新技术，用于自动构建知识图谱（KG）和提取相关子图。除此之外，我们还创新性地开发了一种基于本体的框架，直接从GDELT构建知识图谱，利用其底层架构生成全球事件的结构化表示。在从基于本体的知识图谱中检索信息时，我们采用了直接图查询和最新的图检索方法。通过问答任务的性能对比，我们发现：尽管基于本体的知识图谱在问答中展现出巨大价值，但相关子图的自动化提取仍具挑战性；而LLM生成的知识图谱虽能捕捉事件摘要，却常因缺乏一致性和可解释性而受限。研究结果表明，本体与LLM知识图谱构建的协同方法具有显著潜力，为此我们提出了切实可行的实现路径。

> In this work we study various Retrieval Augmented Regeneration (RAG) approaches to gain an understanding of the strengths and weaknesses of each approach in a question-answering analysis. To gain this understanding we use a case-study subset of the Global Database of Events, Language, and Tone (GDELT) dataset as well as a corpus of raw text scraped from the online news articles. To retrieve information from the text corpus we implement a traditional vector store RAG as well as state-of-the-art large language model (LLM) based approaches for automatically constructing KGs and retrieving the relevant subgraphs. In addition to these corpus approaches, we develop a novel ontology-based framework for constructing knowledge graphs (KGs) from GDELT directly which leverages the underlying schema of GDELT to create structured representations of global events. For retrieving relevant information from the ontology-based KGs we implement both direct graph queries and state-of-the-art graph retrieval approaches. We compare the performance of each method in a question-answering task. We find that while our ontology-based KGs are valuable for question-answering, automated extraction of the relevant subgraphs is challenging. Conversely, LLM-generated KGs, while capturing event summaries, often lack consistency and interpretability. Our findings suggest benefits of a synergistic approach between ontology and LLM-based KG construction, with proposed avenues toward that end.

[Arxiv](https://arxiv.org/abs/2503.07584)