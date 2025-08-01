# SWE-Exp: 基于经验的软件问题解决

发布时间：2025年07月31日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLM）在软件问题解决中的应用，特别是在多智能体协作和蒙特卡洛树搜索（MCTS）框架下。它提出了一种经验增强方法（SWE-Exp），旨在提升LLM代理的记忆和经验复用能力，从而提高问题解决的效率和效果。因此，这篇论文属于LLM应用类别。` `软件工程` `自动化修复`

> SWE-Exp: Experience-Driven Software Issue Resolution

# 摘要

> 大型语言模型（LLM）代理在软件问题解决领域取得了显著进展，借助了多智能体协作和蒙特卡洛树搜索（MCTS）等先进技术。然而，现有的代理缺乏记忆能力，无法保留或复用以往的修复经验，导致对失败路径的重复探索，并错失将成功方法应用到类似问题的机会。为解决这一问题，我们提出了SWE-Exp，一种经验增强方法，通过从以往的代理轨迹中提炼出简洁且可操作的经验，实现跨问题的持续学习。我们的方法引入了一个多维度的经验库，记录了成功和失败的修复尝试。具体来说，它从高层次的问题理解到具体的代码更改，提取了不同层面的可重用问题解决知识。实验结果表明，在开源代理框架下的SWE-bench-Verified基准测试中，SWE-Exp达到了41.6%的通过率（Pass@1），处于行业领先水平。我们的方法开创了一种新范式，使自动化软件工程代理能够系统地积累和利用修复专业知识，将传统的试错探索转变为基于经验的战略性问题解决。

> Recent advances in large language model (LLM) agents have shown remarkable progress in software issue resolution, leveraging advanced techniques such as multi-agent collaboration and Monte Carlo Tree Search (MCTS). However, current agents act as memoryless explorers - treating each problem separately without retaining or reusing knowledge from previous repair experiences. This leads to redundant exploration of failed trajectories and missed chances to adapt successful issue resolution methods to similar problems. To address this problem, we introduce SWE-Exp, an experience - enhanced approach that distills concise and actionable experience from prior agent trajectories, enabling continuous learning across issues. Our method introduces a multi-faceted experience bank that captures both successful and failed repair attempts. Specifically, it extracts reusable issue resolution knowledge at different levels - from high-level problem comprehension to specific code changes. Experiments show that SWE-Exp achieves state-of-the-art resolution rate (41.6% Pass@1) on SWE-bench-Verified under open-source agent frameworks. Our approach establishes a new paradigm in which automated software engineering agents systematically accumulate and leverage repair expertise, fundamentally shifting from trial-and-error exploration to strategic, experience-driven issue resolution.

[Arxiv](https://arxiv.org/abs/2507.23361)