# DAT：检索增强生成中混合检索的动态Alpha调优
发布时间：2025年03月29日

`RAG`
> DAT: Dynamic Alpha Tuning for Hybrid Retrieval in Retrieval-Augmented Generation
>
> 在检索增强生成（RAG）系统中，混合检索技术通过结合密集和稀疏（如基于BM25）检索方法，显著提升了信息检索能力。然而，现有方法在适应性方面存在局限，固定权重方案难以根据不同查询进行调整。为了解决这一挑战，我们提出了一种名为DAT（动态Alpha调谐）的新型混合检索框架。DAT能够根据每个查询动态平衡密集检索和BM25之间的权重，实现更加自适应的检索效果。具体而言，DAT利用大型语言模型（LLM）评估两种检索方法的前1结果的有效性，并为每种方法分配一个有效性评分。通过有效性评分的标准化，DAT能够校准最优的加权因子，确保两种方法之间的加权更加灵活和查询感知。实证结果表明，与固定权重的混合检索方法相比，DAT在各种评估指标上都表现出了显著且一致的优越性。即使在较小规模的模型上，DAT也表现出色，凸显了其高效性和适应性。
>
> https://arxiv.org/abs/2503.23013

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23013](https://arxiv.org/abs/2503.23013)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)