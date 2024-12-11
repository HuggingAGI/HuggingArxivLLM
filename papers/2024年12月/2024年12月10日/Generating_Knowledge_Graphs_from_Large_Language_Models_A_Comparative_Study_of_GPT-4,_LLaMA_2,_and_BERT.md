# 关于从大型语言模型生成知识图谱：对 GPT-4、LLaMA 2 和 BERT 的比较研究

发布时间：2024年12月10日

`RAG` `知识图谱` `生成系统`

> Generating Knowledge Graphs from Large Language Models: A Comparative Study of GPT-4, LLaMA 2, and BERT

# 摘要

> 知识图谱（KGs）对 GraphRAGs 这种在需要结构化推理和语义理解的任务中表现出色的检索增强型生成系统（RAGs）的功能起着关键作用。然而，受传统方法在准确性和可扩展性上的限制，为 GraphRAGs 创建知识图谱仍是重大挑战。本文引入了一种新方法，借助 GPT-4、LLaMA 2（13B）和 BERT 等大型语言模型直接从未结构化数据生成知识图谱，避开了传统流程。通过精度、召回率、F1 分数、图编辑距离和语义相似度等指标，我们评估了模型生成高质量知识图谱的能力。结果显示，GPT-4 在语义保真度和结构准确性方面表现卓越，LLaMA 2 在轻量级、特定领域的图谱中表现出色，BERT 则为实体关系建模中的难题提供了见解。本研究凸显了大型语言模型在简化知识图谱创建、提升 GraphRAG 在实际应用中的可及性方面的潜力，同时为未来的进步奠定了基础。

> Knowledge Graphs (KGs) are essential for the functionality of GraphRAGs, a form of Retrieval-Augmented Generative Systems (RAGs) that excel in tasks requiring structured reasoning and semantic understanding. However, creating KGs for GraphRAGs remains a significant challenge due to accuracy and scalability limitations of traditional methods. This paper introduces a novel approach leveraging large language models (LLMs) like GPT-4, LLaMA 2 (13B), and BERT to generate KGs directly from unstructured data, bypassing traditional pipelines. Using metrics such as Precision, Recall, F1-Score, Graph Edit Distance, and Semantic Similarity, we evaluate the models' ability to generate high-quality KGs. Results demonstrate that GPT-4 achieves superior semantic fidelity and structural accuracy, LLaMA 2 excels in lightweight, domain-specific graphs, and BERT provides insights into challenges in entity-relationship modeling. This study underscores the potential of LLMs to streamline KG creation and enhance GraphRAG accessibility for real-world applications, while setting a foundation for future advancements.

[Arxiv](https://arxiv.org/abs/2412.07412)