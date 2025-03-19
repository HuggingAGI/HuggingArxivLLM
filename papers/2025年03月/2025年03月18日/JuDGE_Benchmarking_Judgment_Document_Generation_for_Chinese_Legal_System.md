# # JuDGE：面向中国法律体系的判决文档生成基准测试

发布时间：2025年03月18日

`RAG`

> JuDGE: Benchmarking Judgment Document Generation for Chinese Legal System

# 摘要

> 本文提出了一种全新的基准测试方法JuDGE（Judgment Document Generation Evaluation），用于评估中文法律系统中判决文档生成的表现。我们将任务定义为：根据给定的案件事实描述，生成一份完整的法律判决文档。为了支持这一基准测试，我们构建了一个综合性的数据集，其中包括了真实法律案件的事实描述，并配以完整的判决文档作为参考，用于评估生成文档的质量。此外，我们还引入了两个外部法律语料库来增强任务的法律知识：一个包含法律法规，另一个则是一个大型的历史判决文档集合。与法律专业人士合作，我们建立了一个全面的自动化评估框架，从多个维度评估生成的判决文档质量。我们使用通用领域和法律领域的大型语言模型（LLMs），对包括少量样本上下文学习、微调以及多源检索增强生成（RAG）方法在内的多种基线方法进行了评估。实验结果表明，尽管RAG方法能够有效提升任务表现，但仍有较大的改进空间。所有代码和数据集均可在以下链接获取：https://github.com/oneal2000/JuDGE。


> This paper introduces JuDGE (Judgment Document Generation Evaluation), a novel benchmark for evaluating the performance of judgment document generation in the Chinese legal system. We define the task as generating a complete legal judgment document from the given factual description of the case. To facilitate this benchmark, we construct a comprehensive dataset consisting of factual descriptions from real legal cases, paired with their corresponding full judgment documents, which serve as the ground truth for evaluating the quality of generated documents. This dataset is further augmented by two external legal corpora that provide additional legal knowledge for the task: one comprising statutes and regulations, and the other consisting of a large collection of past judgment documents. In collaboration with legal professionals, we establish a comprehensive automated evaluation framework to assess the quality of generated judgment documents across various dimensions. We evaluate various baseline approaches, including few-shot in-context learning, fine-tuning, and a multi-source retrieval-augmented generation (RAG) approach, using both general and legal-domain LLMs. The experimental results demonstrate that, while RAG approaches can effectively improve performance in this task, there is still substantial room for further improvement. All the codes and datasets are available at: https://github.com/oneal2000/JuDGE.

[Arxiv](https://arxiv.org/abs/2503.14258)