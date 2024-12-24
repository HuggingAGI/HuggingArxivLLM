# 利用动态知识图谱进行知识编辑以实现多跳问答
发布时间：2024年12月18日

`知识图谱`
> Knowledge Editing with Dynamic Knowledge Graphs for Multi-hop Question Answering
>
> 多跳问答（MHQA）因所需知识广泛，给大型语言模型（LLMs）带来了重大挑战。知识编辑旨在精准修改LLMs以融入特定知识，且不影响其他无关知识，为应对LLMs的MHQA难题提供了可能的解决办法。然而，现有的方案难以有效化解知识冲突问题。多数保留参数的编辑方法受不准确检索的阻碍，还忽视了二次编辑问题，这可能给LLMs的推理过程引入噪声。在本文中，我们推出了KEDKG，这是一种用于MHQA的新型知识编辑方法，借助动态知识图来保障答案的可靠性。KEDKG包含两个主要步骤：动态知识图构建和知识图增强生成。首先，KEDKG自主构建动态知识图来存储修订信息，并解决潜在的知识冲突。接着，它采用精细的检索策略以及实体和关系检测器，以提升LLM生成时的图检索准确性。在基准测试中的实验结果显示，KEDKG超越了以往的最先进模型，在动态信息环境中给出了更准确、更可靠的答案。
>
> https://arxiv.org/abs/2412.13782

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.13782](https://arxiv.org/abs/2412.13782)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)