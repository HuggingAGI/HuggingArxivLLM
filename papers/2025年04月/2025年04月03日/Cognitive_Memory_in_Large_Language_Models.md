# 大型语言模型中的认知记忆

发布时间：2025年04月03日

`LLM理论` `大型语言模型`

> Cognitive Memory in Large Language Models

# 摘要

> 本文深入探讨了大型语言模型（LLMs）中的记忆机制，强调其在生成上下文丰富、幻觉减少且高效回答中的关键作用。文章将记忆体系划分为感觉记忆、短期记忆和长期记忆三类，分别对应输入提示、即时上下文处理和基于外部数据库的长期存储。在文本记忆方面，文章详细阐述了获取（包括选择与摘要）、管理（涵盖更新、访问、存储及冲突解决）和利用（如全文检索、SQL查询和语义搜索）三个核心维度。基于KV缓存的记忆机制部分，则深入分析了选择方法（包括基于规律的摘要、基于评分的方法和特殊标记嵌入）以及压缩技术（如低秩压缩、KV合并和多模态压缩），并探讨了卸载和共享注意力机制等管理策略。此外，基于参数的记忆方法（如LoRA、TTT和MoE）通过将记忆转化为模型参数，显著提升了模型效率；而基于隐藏状态的记忆方法（如分块机制、循环Transformer和Mamba模型）则通过结合RNN隐藏状态与现有技术，进一步增强了长文本处理能力。总体而言，本文为LLM记忆机制提供了全面深入的分析，不仅凸显了其重要性，更为未来的研究指明了方向。

> This paper examines memory mechanisms in Large Language Models (LLMs), emphasizing their importance for context-rich responses, reduced hallucinations, and improved efficiency. It categorizes memory into sensory, short-term, and long-term, with sensory memory corresponding to input prompts, short-term memory processing immediate context, and long-term memory implemented via external databases or structures. The text-based memory section covers acquisition (selection and summarization), management (updating, accessing, storing, and resolving conflicts), and utilization (full-text search, SQL queries, semantic search). The KV cache-based memory section discusses selection methods (regularity-based summarization, score-based approaches, special token embeddings) and compression techniques (low-rank compression, KV merging, multimodal compression), along with management strategies like offloading and shared attention mechanisms. Parameter-based memory methods (LoRA, TTT, MoE) transform memories into model parameters to enhance efficiency, while hidden-state-based memory approaches (chunk mechanisms, recurrent transformers, Mamba model) improve long-text processing by combining RNN hidden states with current methods. Overall, the paper offers a comprehensive analysis of LLM memory mechanisms, highlighting their significance and future research directions.

[Arxiv](https://arxiv.org/abs/2504.02441)