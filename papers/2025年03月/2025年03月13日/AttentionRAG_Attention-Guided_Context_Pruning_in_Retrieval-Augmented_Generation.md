# # AttentionRAG: 基于注意力的上下文剪枝助力增强生成

发布时间：2025年03月13日

`RAG` `问答系统`

> AttentionRAG: Attention-Guided Context Pruning in Retrieval-Augmented Generation

# 摘要

> RAG 在 LLM 应用中表现优异，但随着检索上下文长度的增加，其效果受到限制，面临信息冗余和计算开销过大的问题。现有方法如 LLMLingua 缺乏上下文感知能力，压缩率控制灵活性不足，常导致剪裁不足或信息过度丢失。本文提出 AttentionRAG，一种用于 RAG 系统的注意力引导上下文剪裁方法。其核心在于注意力聚焦机制，将 RAG 查询转化为下一个令牌预测范式，将查询语义焦点集中到单个令牌，实现精准高效的注意力计算。在 LongBench 和 Babilong 基准测试中，AttentionRAG 实现最高 6.3 倍的上下文压缩，关键指标上优于 LLMLingua 方法约 10%。

> While RAG demonstrates remarkable capabilities in LLM applications, its effectiveness is hindered by the ever-increasing length of retrieved contexts, which introduces information redundancy and substantial computational overhead. Existing context pruning methods, such as LLMLingua, lack contextual awareness and offer limited flexibility in controlling compression rates, often resulting in either insufficient pruning or excessive information loss. In this paper, we propose AttentionRAG, an attention-guided context pruning method for RAG systems. The core idea of AttentionRAG lies in its attention focus mechanism, which reformulates RAG queries into a next-token prediction paradigm. This mechanism isolates the query's semantic focus to a single token, enabling precise and efficient attention calculation between queries and retrieved contexts. Extensive experiments on LongBench and Babilong benchmarks show that AttentionRAG achieves up to 6.3$\times$ context compression while outperforming LLMLingua methods by around 10\% in key metrics.

[Arxiv](https://arxiv.org/abs/2503.10720)