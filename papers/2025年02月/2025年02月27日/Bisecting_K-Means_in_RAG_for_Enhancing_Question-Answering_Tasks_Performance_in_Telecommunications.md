# Bisecting K-Means 在 RAG 中的应用：提升电信领域问答任务性能

发布时间：2025年02月27日

`RAG` `问答系统`

> Bisecting K-Means in RAG for Enhancing Question-Answering Tasks Performance in Telecommunications

# 摘要

> 电信领域的问答任务在文献中仍尚待探索，这主要归因于该领域快速的变化和不断演变的标准。本研究提出了一种专为电信领域设计的新型检索增强生成框架，专注于由3GPP文档组成的语料库。该框架引入了Bisecting K-Means聚类技术，通过内容组织嵌入向量，从而实现更高效的信息检索。通过利用这一聚类技术，系统预先选择与用户查询最相似的一组簇，从而提高检索信息的相关性。为了降低模型推理的计算成本，本框架采用Small Language Models进行测试，结果显示在phi-2和phi-3微调模型上分别达到了66.12%和72.13%的准确率，并且缩短了训练时间。

> Question-answering tasks in the telecom domain are still reasonably unexplored in the literature, primarily due to the field's rapid changes and evolving standards. This work presents a novel Retrieval-Augmented Generation framework explicitly designed for the telecommunication domain, focusing on datasets composed of 3GPP documents. The framework introduces the use of the Bisecting K-Means clustering technique to organize the embedding vectors by contents, facilitating more efficient information retrieval. By leveraging this clustering technique, the system pre-selects a subset of clusters that are most similar to the user's query, enhancing the relevance of the retrieved information. Aiming for models with lower computational cost for inference, the framework was tested using Small Language Models, demonstrating improved performance with an accuracy of 66.12% on phi-2 and 72.13% on phi-3 fine-tuned models, and reduced training time.

[Arxiv](https://arxiv.org/abs/2502.20188)