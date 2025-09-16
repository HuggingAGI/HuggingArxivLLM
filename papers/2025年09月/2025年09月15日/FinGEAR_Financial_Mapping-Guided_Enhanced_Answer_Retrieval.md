# FinGEAR：金融映射导向的增强型答案检索

发布时间：2025年09月15日

`RAG` `金融科技`

> FinGEAR: Financial Mapping-Guided Enhanced Answer Retrieval

# 摘要

> 10-K文件等财务披露文件因篇幅冗长、监管章节层级复杂且语言具有领域特殊性，给检索带来了挑战，而标准的检索增强生成（RAG）模型未能充分利用这些特性。为此，我们提出了FinGEAR（财务映射引导的增强答案检索）——一个专为财务文件打造的检索框架。FinGEAR整合了用于条目级指导的财务词典（FLAM）、条目内搜索的双重层次索引（摘要树与问题树），以及两阶段交叉编码器重排序器。该设计让检索与披露文件的结构和术语相匹配，从而实现细粒度、查询感知的上下文筛选。在完整10-K文件上结合FinQA数据集的查询进行评估后发现，FinGEAR在精确率、召回率、F1值和相关性上均有稳定提升：F1值较平面RAG最高提升56.7%，较基于图的RAG提升12.5%，较以往基于树的系统更是提升217.6%；同时，在固定阅读器条件下，下游答案准确率也有所提高。通过联合建模章节层级与领域词典信号，FinGEAR不仅提高了检索保真度，更为高风险财务分析奠定了实用基础。

> Financial disclosures such as 10-K filings present challenging retrieval problems due to their length, regulatory section hierarchy, and domain-specific language, which standard retrieval-augmented generation (RAG) models underuse. We introduce FinGEAR (Financial Mapping-Guided Enhanced Answer Retrieval), a retrieval framework tailored to financial documents. FinGEAR combines a finance lexicon for Item-level guidance (FLAM), dual hierarchical indices for within-Item search (Summary Tree and Question Tree), and a two-stage cross-encoder reranker. This design aligns retrieval with disclosure structure and terminology, enabling fine-grained, query-aware context selection. Evaluated on full 10-Ks with queries aligned to the FinQA dataset, FinGEAR delivers consistent gains in precision, recall, F1, and relevancy, improving F1 by up to 56.7% over flat RAG, 12.5% over graph-based RAGs, and 217.6% over prior tree-based systems, while also increasing downstream answer accuracy with a fixed reader. By jointly modeling section hierarchy and domain lexicon signals, FinGEAR improves retrieval fidelity and provides a practical foundation for high-stakes financial analysis.

[Arxiv](https://arxiv.org/abs/2509.12042)