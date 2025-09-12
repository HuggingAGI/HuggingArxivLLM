# 理解议价博弈中人类与AI智能体的经济权衡

发布时间：2025年09月10日

`Agent` `基础理论`

> Understanding Economic Tradeoffs Between Human and AI Agents in Bargaining Games

# 摘要

> 传统上由人类负责的协调任务，如今正越来越多地交由自主智能体处理。随着这一趋势的推进，评估不仅要关注智能体的性能，还需考察它们在动态多智能体环境中的协商过程，这一点至关重要。此外，不同智能体各有优势：传统统计智能体（如贝叶斯模型）在条件明确的场景中可能表现突出，而大型语言模型（LLMs）则能实现跨上下文泛化。本研究比较了人类（N = 216）、LLMs（GPT-4o、Gemini 1.5 Pro）与贝叶斯智能体在动态协商场景中的表现，通过相同条件下的直接对比，捕捉其结果与行为动态。贝叶斯智能体凭借激进优化获得最高盈余，但频繁遭遇交易被拒；人类与LLMs的总体盈余水平相近，但行为模式截然不同：LLMs偏好保守、让步的交易，几乎不会被拒绝；人类则表现出更具策略性、冒险精神且注重公平的行为。因此，我们发现，性能对等（智能体评估中常用的基准）可能掩盖过程与对齐上的根本差异，而这些差异对于现实世界协调任务的实际部署至关重要。

> Coordination tasks traditionally performed by humans are increasingly being delegated to autonomous agents. As this pattern progresses, it becomes critical to evaluate not only these agents' performance but also the processes through which they negotiate in dynamic, multi-agent environments. Furthermore, different agents exhibit distinct advantages: traditional statistical agents, such as Bayesian models, may excel under well-specified conditions, whereas large language models (LLMs) can generalize across contexts. In this work, we compare humans (N = 216), LLMs (GPT-4o, Gemini 1.5 Pro), and Bayesian agents in a dynamic negotiation setting that enables direct, identical-condition comparisons across populations, capturing both outcomes and behavioral dynamics. Bayesian agents extract the highest surplus through aggressive optimization, at the cost of frequent trade rejections. Humans and LLMs can achieve similar overall surplus, but through distinct behaviors: LLMs favor conservative, concessionary trades with few rejections, while humans employ more strategic, risk-taking, and fairness-oriented behaviors. Thus, we find that performance parity -- a common benchmark in agent evaluation -- can conceal fundamental differences in process and alignment, which are critical for practical deployment in real-world coordination tasks.

[Arxiv](https://arxiv.org/abs/2509.09071)