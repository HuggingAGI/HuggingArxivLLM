# RAKG：基于文档的检索增强知识图谱构建

发布时间：2025年04月13日

`RAG` `知识图谱` `知识图谱构建`

> RAKG:Document-level Retrieval Augmented Knowledge Graph Construction

# 摘要

> 随着GraphRAG和Pike-RAG等基于知识图谱的检索增强生成（RAG）技术的兴起，知识图谱在提升大型语言模型（LLMs）推理能力方面的重要性日益凸显。然而，传统的知识图谱构建（KGC）方法在实体消歧、模式定义 rigid以及跨文档知识整合方面仍面临诸多挑战。本文致力于解决自动文档级知识图谱构建问题，提出了一种名为文档级检索增强知识图谱构建（RAKG）的创新框架。RAKG通过从文本片段中提取预实体，并将其作为RAG的查询，有效缓解了LLMs的长上下文遗忘问题，同时降低了共指消解的复杂性。与传统KGC方法相比，RAKG能够更有效地捕捉全局信息和不同节点间的相互关联，从而显著提升了模型的整体性能。此外，我们将RAG的评估框架成功迁移至KGC领域，通过对生成知识图谱的过滤和评估，有效避免了由LLMs幻觉效应导致的错误实体和关系生成。为验证RAKG的性能，我们构建了MINE数据集，其中为每篇文章配备了标准知识图谱，并通过实验验证了RAKG的优越性。结果显示，RAKG在MINE数据集上达到了95.91%的准确率，比当前最佳基线GraphRAG（89.71%）提升了6.2个百分点。相关代码已开源，可在https://github.com/LMMApplication/RAKG获取。

> With the rise of knowledge graph based retrieval-augmented generation (RAG) techniques such as GraphRAG and Pike-RAG, the role of knowledge graphs in enhancing the reasoning capabilities of large language models (LLMs) has become increasingly prominent. However, traditional Knowledge Graph Construction (KGC) methods face challenges like complex entity disambiguation, rigid schema definition, and insufficient cross-document knowledge integration. This paper focuses on the task of automatic document-level knowledge graph construction. It proposes the Document-level Retrieval Augmented Knowledge Graph Construction (RAKG) framework. RAKG extracts pre-entities from text chunks and utilizes these pre-entities as queries for RAG, effectively addressing the issue of long-context forgetting in LLMs and reducing the complexity of Coreference Resolution. In contrast to conventional KGC methods, RAKG more effectively captures global information and the interconnections among disparate nodes, thereby enhancing the overall performance of the model. Additionally, we transfer the RAG evaluation framework to the KGC field and filter and evaluate the generated knowledge graphs, thereby avoiding incorrectly generated entities and relationships caused by hallucinations in LLMs. We further developed the MINE dataset by constructing standard knowledge graphs for each article and experimentally validated the performance of RAKG. The results show that RAKG achieves an accuracy of 95.91 % on the MINE dataset, a 6.2 % point improvement over the current best baseline, GraphRAG (89.71 %). The code is available at https://github.com/LMMApplication/RAKG.

[Arxiv](https://arxiv.org/abs/2504.09823)