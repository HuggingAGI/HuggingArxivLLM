# # AutoPDL：LLM代理的自动提示调优

发布时间：2025年04月06日

`LLM应用` `自动化机器学习`

> AutoPDL: Automatic Prompt Optimization for LLM Agents

# 摘要

> 大型语言模型（LLMs）的表现深受提示方式的影响，这涉及高层提示模式（如零-shot、CoT、ReAct、ReWOO）和具体提示内容（指令与少样本演示）的选择。然而，手动调整这些组合不仅耗时费力，还容易出错，且难以跨模型或跨任务通用。为此，本研究推出AutoPDL，一种自动化的LLM代理配置发现方案。我们的方法将这一过程转化为一个结构化的AutoML问题，在代理与非代理提示模式及演示的组合空间中，借助逐步淘汰法实现高效探索。我们开发了一个基于PDL提示编程语言的库，用于实现常见提示模式。AutoPDL解决方案是以人类可读、可编辑且可执行的PDL程序形式呈现，充分利用该库功能。此方案还支持源到源优化，为人类在循环中的细化调整与复用提供了可能。实验结果表明，在三项任务和六种LLM（参数规模从8B到70B）上，AutoPDL实现了准确率的显著提升（$9.5\pm17.5$个百分点，最高达68.9pp），并揭示了不同模型与任务下所选提示策略的多样性。

> The performance of large language models (LLMs) depends on how they are prompted, with choices spanning both the high-level prompting pattern (e.g., Zero-Shot, CoT, ReAct, ReWOO) and the specific prompt content (instructions and few-shot demonstrations). Manually tuning this combination is tedious, error-prone, and non-transferable across LLMs or tasks. Therefore, this paper proposes AutoPDL, an automated approach to discover good LLM agent configurations. Our method frames this as a structured AutoML problem over a combinatorial space of agentic and non-agentic prompting patterns and demonstrations, using successive halving to efficiently navigate this space. We introduce a library implementing common prompting patterns using the PDL prompt programming language. AutoPDL solutions are human-readable, editable, and executable PDL programs that use this library. This approach also enables source-to-source optimization, allowing human-in-the-loop refinement and reuse. Evaluations across three tasks and six LLMs (ranging from 8B to 70B parameters) show consistent accuracy gains ($9.5\pm17.5$ percentage points), up to 68.9pp, and reveal that selected prompting strategies vary across models and tasks.

[Arxiv](https://arxiv.org/abs/2504.04365)