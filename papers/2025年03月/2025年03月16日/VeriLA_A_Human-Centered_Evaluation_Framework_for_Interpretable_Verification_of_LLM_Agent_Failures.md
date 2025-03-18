# VeriLA：一个以人类为中心的LLM代理失败可解释性验证评估框架

发布时间：2025年03月16日

`LLM应用` `人工智能` `人机交互`

> VeriLA: A Human-Centered Evaluation Framework for Interpretable Verification of LLM Agent Failures

# 摘要

> AI从业者在复合型AI系统中广泛应用大型语言模型（LLM）代理来应对复杂推理任务。然而，这些代理的执行结果常低于人类预期，导致系统整体性能下降。由于代理推理过程不透明、与人类预期不一致、依赖关系复杂以及人工检查成本高昂，人工干预解决这些问题面临诸多挑战。

为此，我们提出了一种以人类为中心的评估框架——VeriLA（Verifying LLM Agent failures），旨在系统性地分析代理失败情况，减少人工干预需求并使失败原因对人类可解释。该框架首先通过整理人类设计的代理标准，明确每个代理的预期。随后，它开发了一个与人类预期对齐的代理验证模块，通过人工设定的黄金标准进行训练，来评估每个代理的执行输出。

这种方法通过从人类标准的角度揭示失败原因，为修订提供明确指导，同时减少人类认知负担，从而实现对每个代理表现的精细评估。案例研究结果表明，VeriLA不仅具有高度可解释性，而且能有效帮助从业者与系统进行更高效的交互。通过在人机协作中强化问责制，VeriLA为构建更可信且与人类预期对齐的复合型AI系统奠定了基础。

> AI practitioners increasingly use large language model (LLM) agents in compound AI systems to solve complex reasoning tasks, these agent executions often fail to meet human standards, leading to errors that compromise the system's overall performance. Addressing these failures through human intervention is challenging due to the agents' opaque reasoning processes, misalignment with human expectations, the complexity of agent dependencies, and the high cost of manual inspection. This paper thus introduces a human-centered evaluation framework for Verifying LLM Agent failures (VeriLA), which systematically assesses agent failures to reduce human effort and make these agent failures interpretable to humans. The framework first defines clear expectations of each agent by curating human-designed agent criteria. Then, it develops a human-aligned agent verifier module, trained with human gold standards, to assess each agent's execution output. This approach enables granular evaluation of each agent's performance by revealing failures from a human standard, offering clear guidelines for revision, and reducing human cognitive load. Our case study results show that VeriLA is both interpretable and efficient in helping practitioners interact more effectively with the system. By upholding accountability in human-agent collaboration, VeriLA paves the way for more trustworthy and human-aligned compound AI systems.

[Arxiv](https://arxiv.org/abs/2503.12651)