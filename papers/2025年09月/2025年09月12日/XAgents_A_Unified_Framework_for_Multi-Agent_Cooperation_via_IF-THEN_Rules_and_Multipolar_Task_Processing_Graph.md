# XAgents：一种基于IF-THEN规则与多极任务处理图的多智能体协作统一框架

发布时间：2025年09月12日

`Agent` `基础理论`

> XAgents: A Unified Framework for Multi-Agent Cooperation via IF-THEN Rules and Multipolar Task Processing Graph

# 摘要

> 大型语言模型（LLMs）的飞速发展极大增强了多智能体系统（MAS）支持人类处理复杂现实任务的能力。然而，在处理具有不确定性的高度复杂任务时，MAS在有效任务规划上仍存在挑战，常导致误导性或错误输出，进而阻碍任务执行。为此，我们提出XAgents——一个基于多极任务处理图和IF-THEN规则构建的统一多智能体协作框架。XAgents借助多极任务处理图实现动态任务规划，同时应对任务不确定性；在子任务处理阶段，整合特定领域的IF-THEN规则约束智能体行为，全局规则则加强智能体间协作。我们在三个不同数据集上对XAgents进行了性能评估，结果显示，在知识型和逻辑型问答任务中，其性能均持续优于当前最先进的单智能体和多智能体方法。XAgents的代码已开源，地址为：https://github.com/AGI-FHBC/XAgents。

> The rapid advancement of Large Language Models (LLMs) has significantly enhanced the capabilities of Multi-Agent Systems (MAS) in supporting humans with complex, real-world tasks. However, MAS still face challenges in effective task planning when handling highly complex tasks with uncertainty, often resulting in misleading or incorrect outputs that hinder task execution. To address this, we propose XAgents, a unified multi-agent cooperative framework built on a multipolar task processing graph and IF-THEN rules. XAgents uses the multipolar task processing graph to enable dynamic task planning and handle task uncertainty. During subtask processing, it integrates domain-specific IF-THEN rules to constrain agent behaviors, while global rules enhance inter-agent collaboration. We evaluate the performance of XAgents across three distinct datasets, demonstrating that it consistently surpasses state-of-the-art single-agent and multi-agent approaches in both knowledge-typed and logic-typed question-answering tasks. The codes for XAgents are available at: https://github.com/AGI-FHBC/XAgents.

[Arxiv](https://arxiv.org/abs/2509.10054)