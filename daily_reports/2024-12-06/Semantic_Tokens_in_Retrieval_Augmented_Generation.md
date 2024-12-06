# 检索增强生成中的语义标记
发布时间：2024年12月03日

`RAG`
> Semantic Tokens in Retrieval Augmented Generation
>
> 检索增强生成（RAG）架构近来因其能提升自然语言处理任务中的事实依据和连贯性而备受瞩目。然而，随着 RAG 系统访问数据量的增多，其生成准确答案的可靠性会降低。即便是较小的数据集，这些系统有时也难以应对简单的查询。此问题源于其对先进大型语言模型（LLMs）的依赖，这可能给系统输出带来不确定性。在本研究中，我提出了一种新颖的比较 RAG 系统，引入评估器模块来填补概率 RAG 系统与确定性可验证响应之间的鸿沟。评估器会将外部建议与检索到的文档块进行对比，增添决策层以增强系统的可靠性。这种方式能确保检索到的块在语义上相关且在逻辑上与确定性见解一致，进而提高 RAG 系统的准确性和整体效率。该框架为在需要高精度和可验证性的领域中更可靠且可扩展的问答应用铺平了道路。
>
> https://arxiv.org/abs/2412.02563

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.02563](https://arxiv.org/abs/2412.02563)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)