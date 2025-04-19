# 检索增强生成：面对矛盾证据的挑战
发布时间：2025年04月17日

`RAG`
> Retrieval-Augmented Generation with Conflicting Evidence
>
> 大型语言模型（LLM）代理越来越多地采用检索增强生成（RAG）来提升回答的事实准确性。然而，在实际应用中，这些系统需要处理用户提出的模糊查询，同时整合来自多个来源的潜在冲突信息，并且抑制来自噪声或不相关文档中的不准确信息。先前的研究通常孤立地研究和解决这些问题，每次只考虑一个方面，比如处理模糊性或对噪声和错误信息的鲁棒性。我们则同时考虑多个因素，提出了（i）RAMDocs（带有文档中的模糊性和错误信息的检索），一个新的数据集，模拟了用户查询中存在复杂且现实的冲突证据场景，包括模糊性、错误信息和噪声；以及（ii）MADAM-RAG，一种多智能体方法，其中LLM代理在多轮讨论中辩论某个答案的优点，使聚合器能够整理与消歧实体对应的响应，同时丢弃错误信息和噪声，从而共同处理多种冲突来源。我们在需要呈现所有有效答案的 AmbigDocs 数据集上，使用闭源和开源模型展示了 MADAM-RAG 的有效性，相比强大的 RAG 基线模型，其性能提升了 11.40%。在需要抑制错误信息的 FaithEval 数据集上，使用 Llama3.3-70B-Instruct 模型，我们的改进幅度更是达到了 15.80%（绝对值）。此外，我们发现 RAMDocs 对现有的 RAG 基线模型提出了挑战（Llama3.3-70B-Instruct 在精确匹配评分上仅获得 32.60 分）。虽然 MADAM-RAG 开始解决这些冲突因素，但我们的分析表明，仍然存在显著差距，尤其是在增加支持证据和错误信息的不平衡程度时。
>
> https://arxiv.org/abs/2504.13079

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.13079](https://arxiv.org/abs/2504.13079)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)