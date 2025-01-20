# OpenCity: 一个可扩展的平台，用于模拟大规模LLM代理的城市活动
发布时间：2024年10月11日

`Agent应用`
> OpenCity: A Scalable Platform to Simulate Urban Activities with Massive LLM Agents
>
> # 摘要
基于代理的模型（ABMs）长期以来用于研究个体行为如何在城市空间中形成复杂的社会现象。与黑箱预测模型不同，ABMs 擅长揭示驱动这些涌现行为的微观-宏观联系。随着大型语言模型（LLMs）的崛起，LLM 代理能够以前所未有的真实感模拟城市活动。然而，LLMs 的高计算成本对扩展模拟提出了巨大挑战。为此，我们提出了 OpenCity，一个为系统和提示效率优化的可扩展模拟平台。我们设计了 LLM 请求调度器，通过 IO 多路复用并行化请求以减少通信开销，并采用“分组-蒸馏”提示优化策略，通过聚类具有相似静态属性的代理来最小化冗余。在六个全球城市的实验中，OpenCity 实现了每个代理模拟时间 600 倍的加速，LLM 请求减少 70%，令牌使用减少 50%。这些改进使得在普通硬件上 1 小时内模拟 10,000 个代理的日常活动成为可能。此外，OpenCity 的显著加速使我们首次为 LLM 代理建立了城市模拟基准，将模拟的城市活动与全球六个主要城市的真实数据进行比较。我们相信 OpenCity 平台为利用 LLMs 进行城市空间的跨学科研究提供了关键基础设施，推动了更广泛研究社区的集体努力。代码仓库可在 https://anonymous.4open.science/r/Anonymous-OpenCity-42BD 获取。
>
> https://arxiv.org/abs/2410.21286

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.21286](https://arxiv.org/abs/2410.21286)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)