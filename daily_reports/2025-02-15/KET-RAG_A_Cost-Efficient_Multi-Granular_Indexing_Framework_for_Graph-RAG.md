# KET-RAG：一种成本高效的图式RAG多粒度索引框架
发布时间：2025年02月13日

`RAG`
> KET-RAG: A Cost-Efficient Multi-Granular Indexing Framework for Graph-RAG
>
> Graph-RAG 通过构建知识图谱提升 LLM 问答系统检索效果，尤其适用于需要多跳推理的生物医学、法律和政治科学领域。现有 Graph-RAG 系统基于文本块相关性构建 KNN 图，但无法捕捉实体关系，导致质量不佳。近期解决方案利用 LLM 提取实体和关系构建三元组知识图谱，但索引成本高昂。

为此，我们提出 KET-RAG 多粒度索引框架。它首先识别关键文本块并构建知识图谱骨架，然后构建文本-关键词二分图作为轻量替代。检索时，它结合骨架的局部搜索和二分图的模拟搜索提升质量。在两个真实数据集上，KET-RAG 在索引成本、检索效果和生成质量上均优于其他方案。与微软 Graph-RAG 相比，它检索质量相当或更优，索引成本降低超一个数量级，生成质量提升最高 32.4%，索引成本降低约 20%。
>
> https://arxiv.org/abs/2502.09304

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.09304](https://arxiv.org/abs/2502.09304)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)