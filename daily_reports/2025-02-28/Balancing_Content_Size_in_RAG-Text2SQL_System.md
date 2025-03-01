# # 平衡 RAG-Text2SQL 系统中的内容规模问题
发布时间：2025年01月28日

`RAG`
> Balancing Content Size in RAG-Text2SQL System
>
> 大型语言模型（LLMs）为将自然语言查询转换为SQL命令提供了有前景的解决方案，实现了与数据库的无缝交互。然而，Text2SQL系统存在幻觉、知识过时和推理不可追踪等固有局限。为解决这些问题，将检索增强生成（RAG）与Text2SQL模型相结合的方法逐渐兴起。RAG作为检索机制，为查询生成提供表结构和元数据等关键上下文信息。尽管潜力巨大，但RAG+Text2SQL系统的性能受制于检索文档的质量和规模。更丰富的文档内容虽能提升模式相关性和检索准确性，但也可能引入噪音，随着Text2SQL模型提示规模的增加，幻觉风险上升，查询准确性下降。本研究深入探讨了文档规模与质量的权衡，寻求优化系统性能的平衡点。我们识别了性能下降的关键阈值，并提出了应对这些挑战的实用策略。此外，我们还研究了Text2SQL模型中的幻觉现象，强调精心编排的文档展示在减少错误中的关键作用。我们的研究成果为增强RAG+Text2SQL系统的稳健性提供了指导，为实际应用提供了宝贵的见解。
>
> https://arxiv.org/abs/2502.15723

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15723](https://arxiv.org/abs/2502.15723)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)