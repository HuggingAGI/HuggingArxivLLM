# COSMosFL: 小型语言模型集成助力故障定位

发布时间：2025年02月05日

`LLM应用

理由：这篇论文讨论了如何利用小型语言模型（SLMs）和大型语言模型（LLMs）的集成技术（COSMos）来构建高效的软件工程工具，特别是通过实例化一个基于LLM的故障定位技术（AutoFL）。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `软件工程` `故障定位`

> COSMosFL: Ensemble of Small Language Models for Fault Localisation

# 摘要

> LLMs 正迅速成为构建强大软件工程工具和代理的首选，但大多数工具依赖庞大的闭源模型，这带来了安全、成本和环境方面的挑战。最近，开源的小型语言模型（SLMs）崭露头角，虽然它们更小、更节能，易于本地部署，但性能通常不如大型闭源 LLMs。为此，我们提出了 COSMos，一种基于投票机制的任务级 LLM 集成技术，为 SLMs 和 LLMs 提供了更灵活的选择。我们通过基于 LLM 的故障定位技术 AutoFL 实例化 COSMos，并分析了 LLM 准确性与能耗、推理时间和 token 使用量之间的成本效益。Defects4J 的实证评估表明，COSMos 能够构建高效的集成，在故障定位准确性和推理成本上实现帕累托最优，优于单一模型。

> LLMs are rapidly being adopted to build powerful tools and agents for software engineering, but most of them rely heavily on extremely large closed-source models. This, in turn, can hinder wider adoption due to security issues as well as financial cost and environmental impact. Recently, a number of open source Small Language Models (SLMs) are being released and gaining traction. While SLMs are smaller, more energy-efficient, and therefore easier to locally deploy, they tend to show worse performance when compared to larger closed LLMs. We present COSMos, a task-level LLM ensemble technique that uses voting mechanism, to provide a broader range of choice between SLMs and LLMs. We instantiate COSMos with an LLM-based Fault Localisation technique, AutoFL, and report the cost-benefit trade-off between LLM accuracy and various costs such as energy consumption, inference time, and the number of tokens used. An empirical evaluation using Defects4J shows that COSMos can build effective ensembles that can achieve Pareto-optimality in terms of FL accuracy and inference cost, when compared to individual models.

[Arxiv](https://arxiv.org/abs/2502.02908)