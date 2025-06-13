# 在PyTerrier中构建和评估声明式RAG管道

发布时间：2025年06月12日

`RAG` `搜索引擎` `问答系统`

> Constructing and Evaluating Declarative RAG Pipelines in PyTerrier

# 摘要

> 搜索引擎通常采用管道架构，利用复杂但有效的重排序组件优化初始检索结果。检索增强生成（RAG）作为管道架构的激动人心的应用，其最终组件能够从检索到的文档中为用户生成连贯的答案。在本次演示论文中，我们展示了如何在声明式的PyTerrier架构中构建RAG管道，以及这样做的优势。我们的PyTerrier-RAG扩展为PyTerrier提供了对标准RAG数据集和评估指标的便捷访问，以及先进的LLM阅读器。借助PyTerrier独特的操作符符号，构建管道变得轻而易举。我们在标准数据集（包括自然问答数据集）上展示了索引和RAG管道的简洁性，以及如何利用最先进的稀疏、学习稀疏和密集检索器，以及其他神经排序器，构建更强大的PyTerrier生态系统。

> Search engines often follow a pipeline architecture, where complex but effective reranking components are used to refine the results of an initial retrieval. Retrieval augmented generation (RAG) is an exciting application of the pipeline architecture, where the final component generates a coherent answer for the users from the retrieved documents. In this demo paper, we describe how such RAG pipelines can be formulated in the declarative PyTerrier architecture, and the advantages of doing so. Our PyTerrier-RAG extension for PyTerrier provides easy access to standard RAG datasets and evaluation measures, state-of-the-art LLM readers, and using PyTerrier's unique operator notation, easy-to-build pipelines. We demonstrate the succinctness of indexing and RAG pipelines on standard datasets (including Natural Questions) and how to build on the larger PyTerrier ecosystem with state-of-the-art sparse, learned-sparse, and dense retrievers, and other neural rankers.

[Arxiv](https://arxiv.org/abs/2506.10802)