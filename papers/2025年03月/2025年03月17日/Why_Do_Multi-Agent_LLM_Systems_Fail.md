# 为什么多智能体 LLM 系统会失败？

发布时间：2025年03月17日

`Agent` `人工智能` `多智能体系统`

> Why Do Multi-Agent LLM Systems Fail?

# 摘要

> 尽管人们对多智能体系统 (MAS) 的热情日益高涨，但与单智能体框架相比，MAS 在 popular benchmarks 上的性能提升仍然有限。这一差距凸显了分析阻碍 MAS 有效性的挑战的必要性。

在这篇论文中，我们首次全面研究 MAS 的挑战。我们分析了五个流行的 MAS 框架，跨越了 150 多个任务，涉及六位专家人工标注者。我们识别出 14 种独特的失败模式，并提出了一种适用于各种 MAS 框架的全面分类法。这一分类法通过每项研究中三位专家标注者的一致性逐步形成，实现了 0.88 的 Cohen's Kappa 一致性评分。这些细致的失败模式被组织成 3 个类别：(i) 规范和系统设计故障，(ii) 代理间对齐问题，以及 (iii) 任务验证与终止。为了支持可扩展的评估，我们将 MASFT 与 LLM-as-a-Judge 整合。我们还探讨了是否可以通过两种干预措施轻松预防已识别的故障：改进代理角色的规范和增强编排策略。我们的研究发现，这些故障需要更复杂的解决方案，凸显了未来研究的明确路线图。我们开源了我们的数据集和 LLM 标注工具。

> Despite growing enthusiasm for Multi-Agent Systems (MAS), where multiple LLM agents collaborate to accomplish tasks, their performance gains across popular benchmarks remain minimal compared to single-agent frameworks. This gap highlights the need to analyze the challenges hindering MAS effectiveness.
  In this paper, we present the first comprehensive study of MAS challenges. We analyze five popular MAS frameworks across over 150 tasks, involving six expert human annotators. We identify 14 unique failure modes and propose a comprehensive taxonomy applicable to various MAS frameworks. This taxonomy emerges iteratively from agreements among three expert annotators per study, achieving a Cohen's Kappa score of 0.88. These fine-grained failure modes are organized into 3 categories, (i) specification and system design failures, (ii) inter-agent misalignment, and (iii) task verification and termination. To support scalable evaluation, we integrate MASFT with LLM-as-a-Judge. We also explore if identified failures could be easily prevented by proposing two interventions: improved specification of agent roles and enhanced orchestration strategies. Our findings reveal that identified failures require more complex solutions, highlighting a clear roadmap for future research. We open-source our dataset and LLM annotator.

[Arxiv](https://arxiv.org/abs/2503.13657)