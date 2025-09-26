# SKILL-RAG：自我知识诱导学习与过滤——面向检索增强生成

发布时间：2025年09月20日

`RAG` `基础理论`

> SKILL-RAG: Self-Knowledge Induced Learning and Filtering for Retrieval-Augmented Generation

# 摘要

> 近年来，检索增强生成（RAG）大幅提升了大型语言模型（LLMs）在知识密集型任务中的表现。但检索系统可能返回无关内容，将这类信息融入模型常会引发幻觉问题。因此，如何识别并过滤无用检索内容，成为提升RAG性能的核心难题。为了更好融合模型内部知识与检索到的外部知识，理解模型“已知”与“未知”（即“自我知识”）至关重要。基于此，我们提出SKILL-RAG（自我知识诱导学习与过滤的RAG）——一种借助模型自我知识来判断哪些检索文档有助于回答特定查询的新方法。我们设计了基于强化学习的训练框架，可明确从模型中提取自我知识，并通过句子级粒度过滤无关内容、保留有用知识。我们在多个问答基准上，采用Llama2-7B与Qwen3-8B模型对SKILL-RAG展开评估。实验结果显示，SKILL-RAG不仅提升了生成质量，还大幅减少了输入文档量，印证了自我知识在指导高质量检索选择中的关键作用。

> Retrieval-Augmented Generation (RAG) has significantly improved the performance of large language models (LLMs) on knowledge-intensive tasks in recent years. However, since retrieval systems may return irrelevant content, incorporating such information into the model often leads to hallucinations. Thus, identifying and filtering out unhelpful retrieved content is a key challenge for improving RAG performance.To better integrate the internal knowledge of the model with external knowledge from retrieval, it is essential to understand what the model "knows" and "does not know" (which is also called "self-knowledge"). Based on this insight, we propose SKILL-RAG (Self-Knowledge Induced Learning and Filtering for RAG), a novel method that leverages the model's self-knowledge to determine which retrieved documents are beneficial for answering a given query. We design a reinforcement learning-based training framework to explicitly elicit self-knowledge from the model and employs sentence-level granularity to filter out irrelevant content while preserving useful knowledge.We evaluate SKILL-RAG using Llama2-7B and Qwen3-8B on several question answering benchmarks. Experimental results demonstrate that SKILL-RAG not only improves generation quality but also significantly reduces the number of input documents, validating the importance of self-knowledge in guiding the selection of high-quality retrievals.

[Arxiv](https://arxiv.org/abs/2509.20377)