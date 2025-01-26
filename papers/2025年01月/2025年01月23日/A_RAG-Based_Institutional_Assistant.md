# 基于RAG的机构助手

发布时间：2025年01月23日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）模型的设计和评估，特别是针对圣保罗大学开发的RAG虚拟助手。论文的核心内容围绕如何通过检索器和生成模型的结合来提升大型语言模型（LLMs）在知识密集型任务中的表现。因此，这篇论文应归类为RAG。` `虚拟助手`

> A RAG-Based Institutional Assistant

# 摘要

> 尽管大型语言模型（LLMs）在文本生成方面表现出色，但在需要访问结构化知识库或特定文档的场景中，它们却显得力不从心，这限制了其在知识密集型任务中的表现。为了突破这一瓶颈，检索增强生成（RAG）模型应运而生，它让生成模型能够将相关文档片段融入输入中。本文中，我们设计并评估了一款专为圣保罗大学打造的RAG虚拟助手。系统架构由两大核心模块构成：检索器与生成模型。我们对不同模型进行了实验，并调整了块大小和检索文档数量等超参数。最终，我们的最佳检索器模型在Top-5准确率上斩获30%，而生成模型在与真实答案对比时得分22.04%。特别值得一提的是，当LLMs获得正确的文档块时，准确率飙升至54.02%，提升了超过30个百分点。反之，若缺乏上下文输入，性能则骤降至13.68%。这些发现不仅凸显了数据库访问对提升LLM性能的重要性，也揭示了当前语义搜索方法在精准识别相关文档上的不足，以及LLMs在生成精确响应方面所面临的持续挑战。

> Although large language models (LLMs) demonstrate strong text generation capabilities, they struggle in scenarios requiring access to structured knowledge bases or specific documents, limiting their effectiveness in knowledge-intensive tasks. To address this limitation, retrieval-augmented generation (RAG) models have been developed, enabling generative models to incorporate relevant document fragments into their inputs. In this paper, we design and evaluate a RAG-based virtual assistant specifically tailored for the University of São Paulo. Our system architecture comprises two key modules: a retriever and a generative model. We experiment with different types of models for both components, adjusting hyperparameters such as chunk size and the number of retrieved documents. Our optimal retriever model achieves a Top-5 accuracy of 30%, while our most effective generative model scores 22.04\% against ground truth answers. Notably, when the correct document chunks are supplied to the LLMs, accuracy significantly improves to 54.02%, an increase of over 30 percentage points. Conversely, without contextual input, performance declines to 13.68%. These findings highlight the critical role of database access in enhancing LLM performance. They also reveal the limitations of current semantic search methods in accurately identifying relevant documents and underscore the ongoing challenges LLMs face in generating precise responses.

[Arxiv](https://arxiv.org/abs/2501.13880)