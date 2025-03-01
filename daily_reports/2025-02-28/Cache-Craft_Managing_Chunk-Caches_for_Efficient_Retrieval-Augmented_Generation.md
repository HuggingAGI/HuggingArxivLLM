# Cache-Craft：高效检索增强生成的块缓存管理方法
发布时间：2025年02月05日

`RAG`
> Cache-Craft: Managing Chunk-Caches for Efficient Retrieval-Augmented Generation
>
> 检索增强生成（RAG）常与大型语言模型（LLMs）结合使用，以融合领域知识或用户个性化信息。在RAG中，针对用户查询，检索器从知识库提取相关文本片段，并将其作为输入提示的一部分传递给LLM。通常，文本片段会在多个用户查询中被重复检索。然而，当前LLMs的注意力层在处理每个问题时都会对输入片段重复计算键值（KVs），因为现有方法无法在任意上下文中重用KV缓存。简单复用会导致输出质量下降，进而造成GPU上的冗余计算和延迟增加。为此，我们提出了Cache-Craft系统，用于管理和重用RAG系统中文本片段对应的预计算键值（块缓存）。Cache-Craft通过识别可重用缓存、优化少量重新计算以保持输出质量，并高效存储和淘汰硬件中的块缓存，从而最大化重用并隐藏开销。实验结果表明，Cache-Craft相比最先进的前缀缓存，冗余计算减少51%，相比完全重新计算减少75%。在真实工作负载中，Cache-Craft持续批处理可使LLaMA-3-8B和LLaMA-3-70B模型的吞吐量提升1.6倍，端到端延迟减少2倍，同时保持输出质量。
>
> https://arxiv.org/abs/2502.15734

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15734](https://arxiv.org/abs/2502.15734)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)