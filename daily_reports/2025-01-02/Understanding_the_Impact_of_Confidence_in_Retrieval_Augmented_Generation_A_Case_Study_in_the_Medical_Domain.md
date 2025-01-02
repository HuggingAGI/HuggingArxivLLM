# 探究检索增强生成中置信度的影响：以医疗领域为例
发布时间：2024年12月28日

`RAG`
> Understanding the Impact of Confidence in Retrieval Augmented Generation: A Case Study in the Medical Domain
>
> 检索增强生成（RAG）借助外部信息来补充大型语言模型（LLMs）的知识，从而提升对查询的响应精准度。此方法因能注入最新信息，在多个领域广泛应用，研究人员正致力于理解并改进这一点，以在高风险应用中充分释放 RAG 的潜能。然而，尽管 RAG 有望满足这些需求，但即便信息的置信度在金融、医疗保健和医学等某些领域至关重要，其输出置信水平背后的机制仍未被充分探究。我们的研究聚焦于各种配置和模型下，RAG 对医疗领域置信度的影响。我们把模型的预测概率当作输出，依据概率和准确性计算预期校准误差（ECE）和自适应校准误差（ACE）分数来评估置信度。另外，我们分析提示中检索文档的顺序是否校准了置信度。我们的发现显示，置信度和准确性会因模型、设置以及输入提示的格式而有很大差异。这些结果凸显了根据特定模型和条件优化配置的必要性。
>
> https://arxiv.org/abs/2412.20309

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.20309](https://arxiv.org/abs/2412.20309)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)