# # 树状结构文本检索：RAG框架中的层次聚类应用——以台湾法规为例
本文提出了一种基于树状结构的文本检索方法，通过在RAG框架中应用层次聚类技术，成功实现了对台湾法规的高效检索与分析。

发布时间：2025年06月16日

`RAG` `信息检索`

> Tree-Based Text Retrieval via Hierarchical Clustering in RAGFrameworks: Application on Taiwanese Regulations

# 摘要

> 传统的检索增强生成（RAG）系统通过暴力内积搜索找到最相关的k篇文档，结合用户查询后传递给语言模型，以此帮助模型访问外部知识并减少幻觉。然而，实际应用中选择合适的k值是个难题：k值太小可能信息不足，太大又可能引入冗余无关内容。为解决这一问题，我们提出了一种无需预设k值的层次聚类检索方法。该方法不仅保持了系统响应的准确性和相关性，还能自适应地选择语义相关的相关内容。实验中，我们将该方法应用于台湾法律数据集，采用专家评分查询进行测试。结果显示，该方法在专家评估中表现优异，同时保持高精度，无需预设k值，显著提升了法律文本检索的准确性和可解释性。我们的框架简单易行，可轻松集成到现有RAG流水线中，为资源有限的实际场景提供了一个实用的解决方案。

> Traditional Retrieval-Augmented Generation (RAG) systems employ brute-force inner product search to retrieve the top-k most similar documents, then combined with the user query and passed to a language model. This allows the model to access external knowledge and reduce hallucinations. However, selecting an appropriate k value remains a significant challenge in practical applications: a small k may fail to retrieve sufficient information, while a large k can introduce excessive and irrelevant content. To address this, we propose a hierarchical clustering-based retrieval method that eliminates the need to predefine k. Our approach maintains the accuracy and relevance of system responses while adaptively selecting semantically relevant content. In the experiment stage, we applied our method to a Taiwanese legal dataset with expert-graded queries. The results show that our approach achieves superior performance in expert evaluations and maintains high precision while eliminating the need to predefine k, demonstrating improved accuracy and interpretability in legal text retrieval tasks. Our framework is simple to implement and easily integrates with existing RAG pipelines, making it a practical solution for real-world applications under limited resources.

[Arxiv](https://arxiv.org/abs/2506.13607)