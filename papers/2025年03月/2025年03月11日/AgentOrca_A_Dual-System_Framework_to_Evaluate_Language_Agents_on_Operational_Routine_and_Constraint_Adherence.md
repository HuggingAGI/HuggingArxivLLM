# AgentOrca: 一个双系统框架，用于评估语言智能体在操作规范和约束遵循方面的能力

发布时间：2025年03月11日

`Agent` `自动化`

> AgentOrca: A Dual-System Framework to Evaluate Language Agents on Operational Routine and Constraint Adherence

# 摘要

> 随着语言代理逐步在各领域实现关键任务的自动化，它们在操作规范和安全协议下运行的能力变得至关重要。尽管已有大量研究证明这些代理在完成下游任务方面的有效性，但它们在遵循操作流程和规范方面的可靠性仍未得到充分探索。为此，我们提出了AgentOrca——一个用于评估语言代理对操作约束和常规遵守情况的双系统框架。我们的框架通过自然语言提示为代理编码操作约束和常规，并通过相应的可执行代码作为自动验证的基准。通过涵盖五个现实领域、包含测试用例生成与评估的自动化流水线，我们对当前语言代理遵守操作约束的情况进行了定量评估。研究结果揭示了现有先进模型间显著的性能差距：大型推理模型如o1展现出更优的合规性，而其他模型表现明显较低，尤其是在面对复杂约束或用户劝说尝试时。

> As language agents progressively automate critical tasks across domains, their ability to operate within operational constraints and safety protocols becomes essential. While extensive research has demonstrated these agents' effectiveness in downstream task completion, their reliability in following operational procedures and constraints remains largely unexplored. To this end, we present AgentOrca, a dual-system framework for evaluating language agents' compliance with operational constraints and routines. Our framework encodes action constraints and routines through both natural language prompts for agents and corresponding executable code serving as ground truth for automated verification. Through an automated pipeline of test case generation and evaluation across five real-world domains, we quantitatively assess current language agents' adherence to operational constraints. Our findings reveal notable performance gaps among state-of-the-art models, with large reasoning models like o1 demonstrating superior compliance while others show significantly lower performance, particularly when encountering complex constraints or user persuasion attempts.

[Arxiv](https://arxiv.org/abs/2503.08669)