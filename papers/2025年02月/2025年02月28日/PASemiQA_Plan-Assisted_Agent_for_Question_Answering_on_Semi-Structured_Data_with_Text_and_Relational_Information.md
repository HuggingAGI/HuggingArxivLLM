# PASemiQA: 基于计划的辅助智能体，用于处理包含文本和关系信息的半结构化数据的问答任务

发布时间：2025年02月28日

`RAG` `信息检索` `问答系统`

> PASemiQA: Plan-Assisted Agent for Question Answering on Semi-Structured Data with Text and Relational Information

# 摘要

> 大型语言模型 (LLMs) 在跨领域问答任务中表现出令人印象深刻的 abilities，但它们在处理需要专业且最新知识的问题时，常常会遇到 hallucination 问题。为了解决这一局限性，检索增强生成 (RAG) 技术被提出，这些技术从外部来源检索相关信息来 inform 它们的回答。然而，现有的 RAG 方法通常只关注一种类型的外部数据，如向量化文本数据库或知识图谱，无法很好地处理包含文本和关系信息的半结构化数据中的现实问题。为了弥补这一差距，我们引入了 PASemiQA，这是一种新颖的方法，能够联合利用半结构化数据中的文本和关系信息来回答问题。PASemiQA 首先生成一个计划，以识别半结构化数据中与回答问题相关的文本和关系信息，然后使用一个 LLM 代理遍历半结构化数据并提取必要的信息。我们的实证结果展示了 PASemiQA 在不同领域半结构化数据集上的有效性，突显了其在提高基于半结构化数据的问答系统准确性和可靠性方面的潜力。

> Large language models (LLMs) have shown impressive abilities in answering questions across various domains, but they often encounter hallucination issues on questions that require professional and up-to-date knowledge. To address this limitation, retrieval-augmented generation (RAG) techniques have been proposed, which retrieve relevant information from external sources to inform their responses. However, existing RAG methods typically focus on a single type of external data, such as vectorized text database or knowledge graphs, and cannot well handle real-world questions on semi-structured data containing both text and relational information. To bridge this gap, we introduce PASemiQA, a novel approach that jointly leverages text and relational information in semi-structured data to answer questions. PASemiQA first generates a plan to identify relevant text and relational information to answer the question in semi-structured data, and then uses an LLM agent to traverse the semi-structured data and extract necessary information. Our empirical results demonstrate the effectiveness of PASemiQA across different semi-structured datasets from various domains, showcasing its potential to improve the accuracy and reliability of question answering systems on semi-structured data.

[Arxiv](https://arxiv.org/abs/2502.21087)