# 多智能体设计：优化智能体，从提示到拓扑结构

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论了大型语言模型作为多个相互协作的智能体在解决复杂任务时的表现，并提出了多智能体系统搜索（MASS）框架来优化多智能体系统的设计。论文的核心内容围绕智能体的协作、提示编程和拓扑结构优化，这些都是多智能体系统（MAS）的关键要素。因此，这篇论文应归类为Agent。` `人工智能` `多智能体系统`

> Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies

# 摘要

> 大型语言模型作为多个相互协作的智能体，在解决复杂任务时表现出色。这些智能体通过提示编程，声明其功能并协调交互拓扑。设计多智能体系统（MAS）的提示和拓扑结构本身复杂。为自动化这一过程，我们深入分析了设计空间，旨在理解构建高效MAS的关键因素。我们发现，提示与拓扑结构在MAS设计中至关重要。基于此，我们提出了多智能体系统搜索（MASS），这是一个通过三个阶段交错优化（从局部到全局，从提示到拓扑）来高效探索复杂设计空间的框架：1）块级提示优化；2）工作流拓扑优化；3）工作流级提示优化，每个阶段都基于前阶段的优化结果。MASS优化的MAS在性能上远超现有方案。基于MASS的发现，我们提出了构建高效MAS的设计原则。

> Large language models, employed as multiple agents that interact and collaborate with each other, have excelled at solving complex tasks. The agents are programmed with prompts that declare their functionality, along with the topologies that orchestrate interactions across agents. Designing prompts and topologies for multi-agent systems (MAS) is inherently complex. To automate the entire design process, we first conduct an in-depth analysis of the design space aiming to understand the factors behind building effective MAS. We reveal that prompts together with topologies play critical roles in enabling more effective MAS design. Based on the insights, we propose Multi-Agent System Search (MASS), a MAS optimization framework that efficiently exploits the complex MAS design space by interleaving its optimization stages, from local to global, from prompts to topologies, over three stages: 1) block-level (local) prompt optimization; 2) workflow topology optimization; 3) workflow-level (global) prompt optimization, where each stage is conditioned on the iteratively optimized prompts/topologies from former stages. We show that MASS-optimized multi-agent systems outperform a spectrum of existing alternatives by a substantial margin. Based on the MASS-found systems, we finally propose design principles behind building effective multi-agent systems.

[Arxiv](https://arxiv.org/abs/2502.02533)