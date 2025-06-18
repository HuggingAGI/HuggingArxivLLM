# 为 RAG 模型打造的轻量级相关性评分器

发布时间：2025年06月16日

`RAG` `信息检索` `模型优化`

> Lightweight Relevance Grader in RAG

# 摘要

> 检索增强生成（RAG）通过向量数据库弥补大型语言模型（LLMs）的不足，提供更准确和最新的信息。用户提交查询时，RAG执行向量搜索，找到相关文档，生成响应。然而，确保文档与查询相关是巨大挑战。为此，引入相关性评分器辅助模型验证相关性。为减少计算需求，使用轻量级小语言模型更优。本研究将llama-3.2-1b微调为相关性评分器，精确度从0.1301提升至0.7750，与llama-3.1-70b相当。代码在GitHub上可获取。

> Retrieval-Augmented Generation (RAG) addresses limitations of large language models (LLMs) by leveraging a vector database to provide more accurate and up-to-date information. When a user submits a query, RAG executes a vector search to find relevant documents, which are then used to generate a response. However, ensuring the relevance of retrieved documents with a query would be a big challenge. To address this, a secondary model, known as a relevant grader, can be served to verify its relevance. To reduce computational requirements of a relevant grader, a lightweight small language model is preferred. In this work, we finetuned llama-3.2-1b as a relevant grader and achieved a significant increase in precision from 0.1301 to 0.7750. Its precision is comparable to that of llama-3.1-70b. Our code is available at https://github.com/taeheej/Lightweight-Relevance-Grader-in-RAG.

[Arxiv](https://arxiv.org/abs/2506.14084)