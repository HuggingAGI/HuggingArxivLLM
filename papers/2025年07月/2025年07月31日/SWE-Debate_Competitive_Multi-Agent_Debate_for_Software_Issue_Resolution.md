# SWE-辩论：多智能体竞争性辩论在软件问题解决中的应用

发布时间：2025年07月31日

`Agent` `软件工程` `人工智能`

> SWE-Debate: Competitive Multi-Agent Debate for Software Issue Resolution

# 摘要

> 得益于大型语言模型（LLMs）强大的推理能力，问题解决领域取得了显著进展。近期，SWE-agent等基于智能体的框架进一步推动了这一领域的突破，使自主工具型智能体能够处理复杂的软件工程任务。然而，现有基于智能体的问题解决方法主要依赖于智能体的独立探索，常常陷入局部解决方案，难以识别跨越代码库不同部分的问题模式。为解决这一问题，我们提出了SWE-Debate——一个鼓励多样化推理路径并实现更集中化问题定位的竞争性多智能体辩论框架。SWE-Debate首先通过遍历代码依赖图创建多个故障传播路径作为定位提案。随后，它组织三个回合的辩论，由具备沿故障传播路径不同推理视角的专门化智能体参与。这种结构化的竞争使智能体能够协作收敛到一个更集中化的修复计划。最后，这个集中化的修复计划被整合到一个基于MCTS的代码修改智能体中，用于补丁生成。在SWE-bench基准上的实验表明，SWE-Debate在开源智能体框架中取得了全新的前沿成果，并显著超越了基线方法。

> Issue resolution has made remarkable progress thanks to the advanced reasoning capabilities of large language models (LLMs). Recently, agent-based frameworks such as SWE-agent have further advanced this progress by enabling autonomous, tool-using agents to tackle complex software engineering tasks. While existing agent-based issue resolution approaches are primarily based on agents' independent explorations, they often get stuck in local solutions and fail to identify issue patterns that span across different parts of the codebase. To address this limitation, we propose SWE-Debate, a competitive multi-agent debate framework that encourages diverse reasoning paths and achieves more consolidated issue localization. SWE-Debate first creates multiple fault propagation traces as localization proposals by traversing a code dependency graph. Then, it organizes a three-round debate among specialized agents, each embodying distinct reasoning perspectives along the fault propagation trace. This structured competition enables agents to collaboratively converge on a consolidated fix plan. Finally, this consolidated fix plan is integrated into an MCTS-based code modification agent for patch generation. Experiments on the SWE-bench benchmark show that SWE-Debate achieves new state-of-the-art results in open-source agent frameworks and outperforms baselines by a large margin.

[Arxiv](https://arxiv.org/abs/2507.23348)