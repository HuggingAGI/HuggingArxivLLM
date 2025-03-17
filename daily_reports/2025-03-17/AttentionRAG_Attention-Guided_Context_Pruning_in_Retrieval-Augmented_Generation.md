# # AttentionRAG: 基于注意力的上下文剪枝助力增强生成
发布时间：2025年03月13日

`RAG`
> AttentionRAG: Attention-Guided Context Pruning in Retrieval-Augmented Generation
>
> RAG 在 LLM 应用中表现优异，但随着检索上下文长度的增加，其效果受到限制，面临信息冗余和计算开销过大的问题。现有方法如 LLMLingua 缺乏上下文感知能力，压缩率控制灵活性不足，常导致剪裁不足或信息过度丢失。本文提出 AttentionRAG，一种用于 RAG 系统的注意力引导上下文剪裁方法。其核心在于注意力聚焦机制，将 RAG 查询转化为下一个令牌预测范式，将查询语义焦点集中到单个令牌，实现精准高效的注意力计算。在 LongBench 和 Babilong 基准测试中，AttentionRAG 实现最高 6.3 倍的上下文压缩，关键指标上优于 LLMLingua 方法约 10%。
>
> https://arxiv.org/abs/2503.10720

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.10720](https://arxiv.org/abs/2503.10720)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)