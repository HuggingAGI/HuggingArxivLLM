# 安全多维度RAG企业方案：融合安全过滤的混合知识检索
发布时间：2025年04月17日

`RAG`
> Secure Multifaceted-RAG for Enterprise: Hybrid Knowledge Retrieval with Security Filtering
>
> 现有的 RAG 系统在企业环境中面临检索范围有限和数据安全风险的挑战。当内部文档不可用时，系统难以生成准确且完整的响应。此外，使用闭源 LLM 可能导致专有信息泄露。为了解决这些问题，我们提出了 Secure Multifaceted-RAG（SecMulti-RAG）框架，该框架不仅从内部文档中检索，还从两个补充来源中检索：针对预期查询预先生成的专家知识和按需外部 LLM 生成的知识。为了降低安全风险，我们采用本地开源生成器，并仅在过滤机制认为提示安全时选择性地使用外部 LLM。这种方法提高了完整性，防止了数据泄露，并降低了成本。在我们对汽车行业的报告生成任务的评估中，SecMulti-RAG 显著优于传统 RAG - 在基于 LLM 的评估中，正确性、丰富性和有用性方面实现了 79.3% 到 91.9% 的胜率，在人工评估中为 56.3% 到 70.4%。这凸显了 SecMulti-RAG 作为企业 RAG 实用且安全的解决方案。
>
> https://arxiv.org/abs/2504.13425

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.13425](https://arxiv.org/abs/2504.13425)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)