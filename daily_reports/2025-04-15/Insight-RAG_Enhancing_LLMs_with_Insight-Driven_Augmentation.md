# Insight-RAG: 基于洞察力的增强提升大型语言模型（LLMs）
发布时间：2025年03月31日

`RAG`
> Insight-RAG: Enhancing LLMs with Insight-Driven Augmentation
>
> 检索增强生成（RAG）框架在提升大型语言模型（LLMs）性能方面潜力巨大。然而，传统RAG方法仅基于表面相关性检索文档，存在三大问题：可能忽略文档中深埋的关键信息，错过跨多源的相关见解，且难以胜任问答以外的任务。本文提出全新框架——Insight-RAG，专为解决这些问题而设计。

在Insight-RAG的初始阶段，我们不使用传统检索方法，而是借助LLM分析输入查询和任务，提取潜在信息需求。随后，我们查询一个经过文档数据库训练的专用LLM，以挖掘直接针对这些见解的内容。最后，通过结合原始查询与检索到的见解，采用一个最终的LLM生成语境丰富且准确的响应。

基于两个科学论文数据集，我们创建了针对每个问题的评估基准，并将Insight-RAG与传统RAG管道进行了对比评估。实验结果表明，Insight-RAG管道成功解决了这些挑战，在大多数情况下显著超越现有方法。这些发现表明，将基于见解的检索整合到RAG框架中不仅提升了性能，还扩展了其在问答以外任务中的适用性。
>
> https://arxiv.org/abs/2504.00187

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.00187](https://arxiv.org/abs/2504.00187)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)