# # **mRAKL：多语言检索增强的知识图谱构建方法，助力低资源语言的发展**

发布时间：2025年07月21日

`RAG` `知识图谱`

> mRAKL: Multilingual Retrieval-Augmented Knowledge Graph Construction for Low-Resourced Languages

# 摘要

> 知识图谱用于表示现实世界中的实体及其之间的关系。多语言知识图谱构建（mKGC）是在多语言环境下自动构建或预测知识图谱中缺失实体和链接的任务。在本研究中，我们将mKGC任务重新定义为问答（QA）任务，并提出了基于检索增强生成（RAG）的系统mRAKL来执行mKGC。我们通过在问题中使用头实体和链接关系，并让模型预测尾实体作为答案来实现这一目标。我们的实验主要集中在提格里尼亚语和阿姆哈拉语这两种资源较少的语言上，并尝试使用资源丰富的阿拉伯语和英语进行跨语言迁移。使用BM25检索器，我们发现基于RAG的方法相较于无上下文设置提升了性能。此外，我们的消融研究表明，使用理想的检索系统，mRAKL分别将提格里尼亚语和阿姆哈拉语的准确率提高了4.92和8.79个百分点。

> Knowledge Graphs represent real-world entities and the relationships between them. Multilingual Knowledge Graph Construction (mKGC) refers to the task of automatically constructing or predicting missing entities and links for knowledge graphs in a multilingual setting. In this work, we reformulate the mKGC task as a Question Answering (QA) task and introduce mRAKL: a Retrieval-Augmented Generation (RAG) based system to perform mKGC. We achieve this by using the head entity and linking relation in a question, and having our model predict the tail entity as an answer. Our experiments focus primarily on two low-resourced languages: Tigrinya and Amharic. We experiment with using higher-resourced languages Arabic and English for cross-lingual transfer. With a BM25 retriever, we find that the RAG-based approach improves performance over a no-context setting. Further, our ablation studies show that with an idealized retrieval system, mRAKL improves accuracy by 4.92 and 8.79 percentage points for Tigrinya and Amharic, respectively.

[Arxiv](https://arxiv.org/abs/2507.16011)