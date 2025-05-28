# 更少上下文，性能相同：一个资源高效的LLM临床自然语言处理RAG框架

发布时间：2025年05月23日

`RAG` `临床文档分类`

> Less Context, Same Performance: A RAG Framework for Resource-Efficient LLM-Based Clinical NLP

# 摘要

> 长文本分类对大型语言模型（LLMs）而言面临两大挑战：token限制和高昂的计算成本。本研究旨在探索仅利用最相关文本片段的检索增强生成（RAG）方法，能否达到使用大上下文LLMs处理完整临床记录的性能水平。我们的研究流程包括：将临床文档分割成小块、转换为向量嵌入并存储于FAISS索引中。随后，检索与分类任务最相关的前4000个单词，并将其整合后输入LLM。我们在GPT4o、LLaMA和Mistral三个模型上进行手术并发症识别任务的评估。通过AUC ROC、精确度、召回率和F1等指标，我们发现RAG方法与全文本处理在统计学上无显著差异（p > 0.05）。这表明，RAG不仅能够大幅减少token使用量，还能保持分类准确性，为处理冗长的临床文档提供了一种高效且经济的解决方案。

> Long text classification is challenging for Large Language Models (LLMs) due to token limits and high computational costs. This study explores whether a Retrieval Augmented Generation (RAG) approach using only the most relevant text segments can match the performance of processing entire clinical notes with large context LLMs. We begin by splitting clinical documents into smaller chunks, converting them into vector embeddings, and storing these in a FAISS index. We then retrieve the top 4,000 words most pertinent to the classification query and feed these consolidated segments into an LLM. We evaluated three LLMs (GPT4o, LLaMA, and Mistral) on a surgical complication identification task. Metrics such as AUC ROC, precision, recall, and F1 showed no statistically significant differences between the RAG based approach and whole-text processing (p > 0.05p > 0.05). These findings indicate that RAG can significantly reduce token usage without sacrificing classification accuracy, providing a scalable and cost effective solution for analyzing lengthy clinical documents.

[Arxiv](https://arxiv.org/abs/2505.20320)