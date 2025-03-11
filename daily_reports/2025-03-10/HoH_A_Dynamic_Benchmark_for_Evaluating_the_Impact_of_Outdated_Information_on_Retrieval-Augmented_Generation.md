# HoH：一个动态基准测试，用于评估过时信息对检索增强生成的影响
发布时间：2025年03月03日

`RAG`
> HoH: A Dynamic Benchmark for Evaluating the Impact of Outdated Information on Retrieval-Augmented Generation
>
> 检索增强生成（RAG）已被证明是解决大型语言模型（LLMs）知识过时问题的有效方法，但它面临一个关键挑战：知识库中过时信息的普遍存在。当前研究主要集中在整合最新信息上，但对检索源中同时存在的过时信息的影响仍研究不足。为解决这一问题，我们提出了HoH，这是首个专门设计用于评估过时信息对RAG影响的基准。我们的基准利用基于token的差异算法结合LLM流水线，高效地创建了一个大规模问答数据集，能够准确捕捉现实世界事实中的知识演变。通过全面实验，我们发现过时信息对RAG性能的严重影响主要体现在两个方面：（1）它通过分散模型注意力，大幅降低了响应的准确性；（2）即使当前信息可用，它也可能误导模型生成潜在有害的输出。现有RAG方法在处理过时信息时，在检索和生成两个环节都面临困难。这些发现凸显了开发创新解决方案以应对RAG中时间相关挑战的迫切需求。
>
> https://arxiv.org/abs/2503.04800

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.04800](https://arxiv.org/abs/2503.04800)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)