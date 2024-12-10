# 对随机多智能体系统中战略能力的推理

发布时间：2024年12月09日

`Agent` `人工智能` `博弈论`

> Reasoning about Strategic Abilities in Stochastic Multi-agent Systems

# 摘要

> 对于包含多个智能体的人工智能系统而言，有关战略能力的推理是关键所在，它为在博弈论、社会选择理论等中规范各类问题提供了统一框架。在本研究中，我们提出了交替时间$μ$-演算（AMC）的概率扩展——PAMC，用于推理随机多智能体系统中智能体的战略能力。我们指出，PAMC涵盖了现有的两种逻辑AMC和P$μ$TL（模态$μ$-演算的概率扩展），但与概率交替时间时态逻辑（PATL）无可比性。我们对PAMC的模型检查和可满足性检查问题展开了研究。首先，借助用于解决标准形式博弈和AMC模型检查的算法，给出了一个模型检查算法。我们证实，PAMC的模型检查问题仍处于UP$\cap$co-UP中，与AMC和P$μ$TL的模型检查问题属于相同的复杂度类别。此外，我们通过将PAMC的可满足性问题新归约为解决奇偶博弈，得到了一个EXPTIME决策过程，以及能让我们为每个可满足的PAMC公式构建模型的小模型属性。与PCTL和PATL的可满足性检查问题尚未解决不同，PAMC中的可满足性具有与模态$μ$-演算相同的复杂度。我们已将模型检查和可满足性检查算法实现为开源工具，并报告了实验结果，展现了我们方法的实际应用和有效性。

> Reasoning about strategic abilities is key to AI systems comprising multiple agents, which provide a unified framework for formalizing various problems in game theory, social choice theory, etc. In this work, we propose a probabilistic extension of the alternating-time $μ$-calculus (AMC), named PAMC, for reasoning about the strategic abilities of agents in stochastic multi-agent systems. We show that PAMC subsumes two existing logics AMC and P$μ$TL (a probabilistic extension of the modal $μ$-calculus), but is incomparable with the probabilistic alternating-time temporal logic (PATL). We study the problems of model checking and satisfiability checking for PAMC. We first give a model checking algorithm by leveraging algorithms for solving normal-form games and AMC model checking. We establish that the model checking problem of PAMC remains in UP$\cap$co-UP, the same complexity class as the model checking problem for AMC and P$μ$TL. We also provide a new reduction from the satisfiability problem of PAMC to solving parity games, by which we obtain an EXPTIME decision procedure, as well as the small model property which allows us to construct a model for each satisfiable PAMC formula. Satisfiability in PAMC has the same complexity as in the modal $μ$-calculus, unlike PCTL and PATL whose satisfiability checking problems remain open. We have implemented both the model checking and satisfiability checking algorithms as open-source tools. Experimental results are reported, showcasing the practical applications and effectiveness of our approaches.

[Arxiv](https://arxiv.org/abs/2412.06509)