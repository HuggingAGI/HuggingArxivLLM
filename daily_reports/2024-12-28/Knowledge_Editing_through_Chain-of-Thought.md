# 通过思维链进行知识编辑
发布时间：2024年12月23日


> Knowledge Editing through Chain-of-Thought
>
> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务中展现出卓越能力。然而，因频繁重训成本高昂，让这些模型跟上不断演进的世界知识成了重大难题。为应对此难题，知识编辑技术出现了，能在不重新构建模型的情况下用新信息更新 LLMs。其中，上下文编辑范式因能在融入新知识时保留模型原有能力而表现出色。尽管潜力巨大，但现有的上下文知识编辑方法往往针对特定任务，主要聚焦于使用结构化知识三元组的多跳问答任务。而且，它们依赖少样本提示进行任务分解，导致在不同任务中的泛化不稳定且效果欠佳。
  鉴于这些局限，我们提出了 EditCoT，这是一个新颖的知识编辑框架，无需重训就能灵活高效地在各种任务中更新 LLMs。EditCoT 先为给定输入生成思维链（CoT），然后用基于更新知识的 CoT 编辑器对这个 CoT 过程进行迭代优化。我们在多种基准上对 EditCoT 进行评估，涵盖多种语言和任务。结果显示，与现有方法相比，我们的方法达到了最先进的性能，在泛化、有效性和稳定性方面表现出色，是知识更新领域的重大进步。代码和数据可在：https://github.com/bebr2/EditCoT 获取。
>
> https://arxiv.org/abs/2412.17727

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.17727](https://arxiv.org/abs/2412.17727)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)