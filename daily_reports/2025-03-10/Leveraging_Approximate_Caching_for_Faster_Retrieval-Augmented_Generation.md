# # 借助近似缓存加速检索增强生成
发布时间：2025年03月07日

`RAG`
> Leveraging Approximate Caching for Faster Retrieval-Augmented Generation
>
> 检索增强生成（RAG）通过整合外部知识显著提升了大型语言模型（LLM）答案的可靠性。然而，由于从大型向量数据库中查找相关文档是一项计算成本高昂的任务，RAG增加了端到端推理时间。为了解决这一问题，我们提出了名为Proximity的近似键值缓存机制，旨在通过利用用户查询之间的相似性来优化RAG工作流。与传统的独立处理每个查询的方式不同，Proximity在遇到相似查询时会复用之前检索到的文档，从而减少了对昂贵的向量数据库查找的依赖。我们在MMLU和MedRAG基准测试中对Proximity进行了评估，结果表明它在保持响应准确性的同时，显著提升了检索效率。Proximity将检索延迟降低了高达59%，同时保持了准确性，并降低了向量数据库的计算负担。我们还实验了不同的相似度阈值，并量化了速度与召回率之间的权衡。我们的研究表明，近似缓存是一种既可行又有效的优化RAG系统的方法。
>
> https://arxiv.org/abs/2503.05530

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.05530](https://arxiv.org/abs/2503.05530)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)