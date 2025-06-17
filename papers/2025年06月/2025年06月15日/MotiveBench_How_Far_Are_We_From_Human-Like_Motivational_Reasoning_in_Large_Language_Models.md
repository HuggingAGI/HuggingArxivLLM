# # 动机基准测试
大型语言模型的动机推理能力离人类还有多远？

发布时间：2025年06月15日

`LLM应用` `社交模拟` `AI伴侣`

> MotiveBench: How Far Are We From Human-Like Motivational Reasoning in Large Language Models?

# 摘要

> 大型语言模型（LLMs）作为代理框架的核心，在社交模拟和AI伴侣等场景中得到了广泛应用。然而，它们能否以及在多大程度上能够模拟人类动机，仍是一个未被充分探索的问题。现有的基准测试由于场景过于简单且缺乏角色身份，导致与现实情况存在信息不对称。为解决这一问题，我们提出了MotiveBench，包含200个丰富的情境场景和600个推理任务，涵盖多个动机水平。通过MotiveBench，我们对七个流行的模型家族进行了广泛实验，比较了每个家族内的不同规模和版本。实验结果显示，即使是当前最先进的LLMs在实现人类动机推理方面仍显不足。我们的分析揭示了几个关键发现：LLMs在推理“爱与归属”动机方面存在困难，且容易走向过度理性化和理想化。这些发现为未来研究如何赋予LLMs更人性化的方向提供了重要指引。数据集、基准测试和代码可在https://aka.ms/motivebench获取。

> Large language models (LLMs) have been widely adopted as the core of agent frameworks in various scenarios, such as social simulations and AI companions. However, the extent to which they can replicate human-like motivations remains an underexplored question. Existing benchmarks are constrained by simplistic scenarios and the absence of character identities, resulting in an information asymmetry with real-world situations. To address this gap, we propose MotiveBench, which consists of 200 rich contextual scenarios and 600 reasoning tasks covering multiple levels of motivation. Using MotiveBench, we conduct extensive experiments on seven popular model families, comparing different scales and versions within each family. The results show that even the most advanced LLMs still fall short in achieving human-like motivational reasoning. Our analysis reveals key findings, including the difficulty LLMs face in reasoning about "love & belonging" motivations and their tendency toward excessive rationality and idealism. These insights highlight a promising direction for future research on the humanization of LLMs. The dataset, benchmark, and code are available at https://aka.ms/motivebench.

[Arxiv](https://arxiv.org/abs/2506.13065)