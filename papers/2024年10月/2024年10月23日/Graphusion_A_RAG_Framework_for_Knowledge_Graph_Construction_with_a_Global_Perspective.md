# Graphusion: 全局视角下的知识图谱构建 RAG 框架

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）进行知识图谱构建（KGC），并提出了一个名为Graphusion的框架。该框架通过LLMs从自由文本中提取知识三元组，并进行全局知识融合。论文还展示了Graphusion在自然语言处理（NLP）领域的应用潜力，特别是在教育场景中的应用。因此，这篇论文属于LLM应用类别，因为它主要关注如何将LLMs应用于具体的任务（知识图谱构建和问答系统）。`

> Graphusion: A RAG Framework for Knowledge Graph Construction with a Global Perspective

# 摘要

> # 摘要
知识图谱（KGs）在人工智能领域扮演着关键角色，尤其在问答（QA）等下游任务中广泛应用。传统上，KGs的构建依赖领域专家的深度参与。近年来，大型语言模型（LLMs）被引入知识图谱构建（KGC），但现有方法多局限于从单一句子或文档中提取知识三元组，缺乏全局视角的知识融合。为此，我们提出了Graphusion，一个从自由文本中进行零-shot KGC的框架。该框架分为三步：首先，通过主题建模提取种子实体，确保最终KG涵盖最相关的实体；其次，利用LLMs提取候选三元组；最后，设计了一个创新的融合模块，提供全局知识视图，涵盖实体合并、冲突解决和新三元组发现。实验表明，Graphusion在实体提取和关系识别上分别获得了2.92和2.37分（满分3分）。此外，我们展示了Graphusion在自然语言处理（NLP）领域的应用潜力，并在教育场景中进行了验证。我们推出了TutorQA，一个包含1,200个QA对的专家验证基准，涵盖六个任务。基于Graphusion构建的KG，我们在基准测试中取得了显著提升，例如子图完成任务的准确率提高了9.2%。

> Knowledge Graphs (KGs) are crucial in the field of artificial intelligence and are widely used in downstream tasks, such as question-answering (QA). The construction of KGs typically requires significant effort from domain experts. Large Language Models (LLMs) have recently been used for Knowledge Graph Construction (KGC). However, most existing approaches focus on a local perspective, extracting knowledge triplets from individual sentences or documents, missing a fusion process to combine the knowledge in a global KG. This work introduces Graphusion, a zero-shot KGC framework from free text. It contains three steps: in Step 1, we extract a list of seed entities using topic modeling to guide the final KG includes the most relevant entities; in Step 2, we conduct candidate triplet extraction using LLMs; in Step 3, we design the novel fusion module that provides a global view of the extracted knowledge, incorporating entity merging, conflict resolution, and novel triplet discovery. Results show that Graphusion achieves scores of 2.92 and 2.37 out of 3 for entity extraction and relation recognition, respectively. Moreover, we showcase how Graphusion could be applied to the Natural Language Processing (NLP) domain and validate it in an educational scenario. Specifically, we introduce TutorQA, a new expert-verified benchmark for QA, comprising six tasks and a total of 1,200 QA pairs. Using the Graphusion-constructed KG, we achieve a significant improvement on the benchmark, for example, a 9.2% accuracy improvement on sub-graph completion.

[Arxiv](https://arxiv.org/abs/2410.17600)