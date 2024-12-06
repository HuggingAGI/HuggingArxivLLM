# 借助 LLM 实现自动的本体提取与知识图谱生成
发布时间：2024年12月03日

`知识图谱`
> Leveraging LLM for Automated Ontology Extraction and Knowledge Graph Generation
>
> 在可靠性和可维护性（RAM）领域，从大型、复杂的技术文档中提取相关且结构化的知识，既费力又容易出错。我们的工作通过推出 OntoKGen 来应对此挑战，它是一个用于本体提取和知识图谱（KG）生成的有效途径。OntoKGen 借助由我们的自适应迭代思维链（CoT）算法引导的交互式用户界面，利用大型语言模型（LLMs），确保本体提取过程以及相应的 KG 生成符合用户的特定需求。虽然 KG 生成依据已确认的本体遵循清晰、结构化的路径，但由于其本质基于用户偏好，所以不存在普遍正确的本体。OntoKGen 推荐基于最佳实践的本体，最大程度减少用户的工作量，并提供可能被忽略的有价值见解，同时让用户完全掌控最终的本体。基于确认的本体生成 KG 后，OntoKGen 能够无缝集成到像 Neo4j 这样的无模式、非关系型数据库中。这种集成便于从各种非结构化来源灵活地存储和检索知识，有助于高级查询、分析和决策。此外，生成的 KG 为未来融入检索增强生成（RAG）系统提供了坚实基础，为开发特定领域的智能应用增强了能力。
>
> https://arxiv.org/abs/2412.00608

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.00608](https://arxiv.org/abs/2412.00608)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)