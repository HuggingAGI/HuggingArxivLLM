# C-3PO：紧凑型即插即用代理优化实现类人检索增强生成
发布时间：2025年02月10日

`RAG`
> C-3PO: Compact Plug-and-Play Proxy Optimization to Achieve Human-like Retrieval-Augmented Generation
>
> 检索增强生成（RAG）系统在协调独立开发的检索器和大型语言模型（LLMs）时面临根本性挑战。现有方法通常涉及修改组件或引入简单的中间模块，导致实际限制和次优性能。受人类搜索行为启发——通常涉及提出搜索查询和审查文档的来回过程，我们提出了C-3PO，一个以代理为中心的框架，通过轻量级多智能体系统促进检索器和LLMs之间的通信。我们的框架实现了三个专门的智能体，协同优化整个RAG管道，无需更改检索器和LLMs。这些智能体共同评估检索需求，生成有效查询，并选择适合LLMs的信息。为实现有效的多智能体协调，我们在强化学习中开发了一种树结构展开方法用于奖励信用分配。在域内和域外场景的大量实验表明，C-3PO显著提升了RAG性能，同时保持了即插即用的灵活性和卓越的泛化能力。
>
> https://arxiv.org/abs/2502.06205

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.06205](https://arxiv.org/abs/2502.06205)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)