# 照我们做的做，而不是照你想的做：大型语言模型的从众性

发布时间：2025年01月22日

`Agent

理由：这篇论文主要研究的是大型语言模型（LLMs）驱动的多智能体系统中的从众现象，涉及智能体在协作中的行为、影响因素及缓解策略。论文的核心关注点是智能体系统的集体决策能力和伦理影响，属于多智能体系统的研究范畴，因此应归类为Agent。` `人工智能` `协作系统`

> Do as We Do, Not as You Think: the Conformity of Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）的最新进展彻底革新了智能体领域，推动了能够解决跨领域复杂问题的协作多智能体系统的发展。然而，这些系统中潜在的从众现象，类似于人类群体中的从众偏见和群体思维，仍未被充分研究，引发了对其集体决策能力和伦理影响的担忧。本文全面研究了LLM驱动的多智能体系统中的从众现象，聚焦于三个方面：从众的存在、影响因素及缓解策略。我们提出了BenchForm，一个专注于从众的新基准，包含推理密集型任务和五种交互协议，旨在探究LLMs在协作中的行为。通过从众率和独立率等指标，我们评估了几种代表性LLMs的表现，并深入分析了交互时间、多数群体规模等因素对从众的影响，以及智能体如何合理化其从众行为。此外，我们探索了两种缓解从众的策略：增强角色设计和反思机制。基于实证结果和案例研究，我们得出了关于LLMs从众现象的几项有趣发现，希望这些见解能为构建更强大且符合伦理的协作AI系统提供参考。BenchForm基准和代码已公开。

> Recent advancements in large language models (LLMs) revolutionize the field of intelligent agents, enabling collaborative multi-agent systems capable of tackling complex problems across various domains. However, the potential of conformity within these systems, analogous to phenomena like conformity bias and groupthink in human group dynamics, remains largely unexplored, raising concerns about their collective problem-solving capabilities and possible ethical implications. This paper presents a comprehensive study on conformity in LLM-driven multi-agent systems, focusing on three aspects: the existence of conformity, the factors influencing conformity, and potential mitigation strategies. In particular, we introduce BenchForm, a new conformity-oriented benchmark, featuring reasoning-intensive tasks and five distinct interaction protocols designed to probe LLMs' behavior in collaborative scenarios. Several representative LLMs are evaluated on BenchForm, using metrics such as conformity rate and independence rate to quantify conformity's impact. Our analysis delves into factors influencing conformity, including interaction time and majority size, and examines how the subject agent rationalizes its conforming behavior. Furthermore, we explore two strategies to mitigate conformity effects, i.e., developing enhanced personas and implementing a reflection mechanism. Several interesting findings regarding LLMs' conformity are derived from empirical results and case studies. We hope that these insights can pave the way for more robust and ethically-aligned collaborative AI systems. Our benchmark and code are available at BenchForm.

[Arxiv](https://arxiv.org/abs/2501.13381)