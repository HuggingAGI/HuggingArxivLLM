# # 评估：检索增强生成在化学领域的性能

发布时间：2025年05月12日

`RAG`

> Benchmarking Retrieval-Augmented Generation for Chemistry

# 摘要

> 检索增强生成（RAG）作为提升大型语言模型（LLMs）能力的强效框架，在整合外部知识方面表现突出，尤其在需要专业动态信息的科学领域。尽管RAG潜力巨大，但其在化学领域的应用仍面临挑战，主要由于缺乏高质量领域特定语料库及完善评估基准。本研究推出ChemRAG-Bench——首个全面评估RAG在化学任务中表现的基准框架。配套的化学语料库整合了科学文献、PubChem数据库、PubMed摘要、教科书及维基百科等多源异构知识。此外，我们开发了ChemRAG-Toolkit——一个支持五种检索算法及八种LLMs的模块化、可扩展RAG工具包。实验结果显示，RAG相比直接推理方法带来显著性能提升，平均相对提升达17.4%。我们深入分析检索器架构、语料库选择及检索段落数量，最终提出实用建议，为未来化学领域RAG系统的研发与部署提供指导。项目资源已开源，详情请访问https://chemrag.github.io。


> Retrieval-augmented generation (RAG) has emerged as a powerful framework for enhancing large language models (LLMs) with external knowledge, particularly in scientific domains that demand specialized and dynamic information. Despite its promise, the application of RAG in the chemistry domain remains underexplored, primarily due to the lack of high-quality, domain-specific corpora and well-curated evaluation benchmarks. In this work, we introduce ChemRAG-Bench, a comprehensive benchmark designed to systematically assess the effectiveness of RAG across a diverse set of chemistry-related tasks. The accompanying chemistry corpus integrates heterogeneous knowledge sources, including scientific literature, the PubChem database, PubMed abstracts, textbooks, and Wikipedia entries. In addition, we present ChemRAG-Toolkit, a modular and extensible RAG toolkit that supports five retrieval algorithms and eight LLMs. Using ChemRAG-Toolkit, we demonstrate that RAG yields a substantial performance gain -- achieving an average relative improvement of 17.4% over direct inference methods. We further conduct in-depth analyses on retriever architectures, corpus selection, and the number of retrieved passages, culminating in practical recommendations to guide future research and deployment of RAG systems in the chemistry domain. The code and data is available at https://chemrag.github.io.

[Arxiv](https://arxiv.org/abs/2505.07671)