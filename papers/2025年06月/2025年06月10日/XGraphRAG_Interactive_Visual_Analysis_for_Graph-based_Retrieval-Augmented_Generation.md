# XGraphRAG：交互式图结构检索增强生成的可视化分析工具

发布时间：2025年06月10日

`RAG` `大型语言模型` `可视化分析`

> XGraphRAG: Interactive Visual Analysis for Graph-based Retrieval-Augmented Generation

# 摘要

> 基于图的检索增强生成（GraphRAG）在提升大型语言模型（LLM）回答能力方面表现出色，尤其在利用外部知识库方面。与传统RAG相比，GraphRAG通过引入图结构作为中间表示形式，能够更有效地捕捉语料库中的结构化关联知识，从而显著提升生成结果的准确性和全面性。然而，GraphRAG复杂的信息处理流程以及在图构建和查询过程中涉及的大量LLM调用，使得开发人员在分析其在自身数据集上的效果时面临诸多挑战，这也限制了GraphRAG的可解释性和可访问性。为解决这一问题，我们提出了一种可视化分析框架，帮助RAG开发者识别GraphRAG的关键召回点，并通过GraphRAG管道进行追踪。基于此框架，我们开发了XGraphRAG，这是一个集成了多种交互式可视化的原型系统，旨在提升用户的分析效率，促进失败案例的收集和改进机会的识别。我们的评估结果证明了该方法的有效性和实用性。我们的工作已开源，可在https://github.com/Gk0Wk/XGraphRAG获取。

> Graph-based Retrieval-Augmented Generation (RAG) has shown great capability in enhancing Large Language Model (LLM)'s answer with an external knowledge base. Compared to traditional RAG, it introduces a graph as an intermediate representation to capture better structured relational knowledge in the corpus, elevating the precision and comprehensiveness of generation results. However, developers usually face challenges in analyzing the effectiveness of GraphRAG on their dataset due to GraphRAG's complex information processing pipeline and the overwhelming amount of LLM invocations involved during graph construction and query, which limits GraphRAG interpretability and accessibility. This research proposes a visual analysis framework that helps RAG developers identify critical recalls of GraphRAG and trace these recalls through the GraphRAG pipeline. Based on this framework, we develop XGraphRAG, a prototype system incorporating a set of interactive visualizations to facilitate users' analysis process, boosting failure cases collection and improvement opportunities identification. Our evaluation demonstrates the effectiveness and usability of our approach. Our work is open-sourced and available at https://github.com/Gk0Wk/XGraphRAG.

[Arxiv](https://arxiv.org/abs/2506.13782)