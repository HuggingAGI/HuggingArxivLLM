# 分解式智能体：分离上下文学习与记忆，实现稳固的工具使用能力

发布时间：2025年03月28日

`Agent` `智能体` `AI系统`

> Factored Agents: Decoupling In-Context Learning and Memorization for Robust Tool Use

# 摘要

> 本文提出了一种新颖的分层式代理架构，旨在克服传统单代理系统在智能体AI中的局限性。我们的方法将代理分解为两个专业化的组件：(1) 一个大型语言模型（LLM），作为高级规划器和上下文学习器，可能利用用户提示中动态可用的信息，(2) 一个较小的语言模型，充当工具格式和输出的记忆器。这种解耦解决了单体设计中普遍存在的问题，包括格式错误、缺失和幻觉API字段，以及动态环境中的次优规划。实证评估表明，我们的分层架构显著提高了规划准确性和错误恢复能力，同时阐明了上下文学习与静态记忆之间的固有权衡。这些发现表明，分层方法是开发更健壮和适应性更强的智能体AI系统的有希望的途径。

> In this paper, we propose a novel factored agent architecture designed to overcome the limitations of traditional single-agent systems in agentic AI. Our approach decomposes the agent into two specialized components: (1) a large language model (LLM) that serves as a high level planner and in-context learner, which may use dynamically available information in user prompts, (2) a smaller language model which acts as a memorizer of tool format and output. This decoupling addresses prevalent issues in monolithic designs, including malformed, missing, and hallucinated API fields, as well as suboptimal planning in dynamic environments. Empirical evaluations demonstrate that our factored architecture significantly improves planning accuracy and error resilience, while elucidating the inherent trade-off between in-context learning and static memorization. These findings suggest that a factored approach is a promising pathway for developing more robust and adaptable agentic AI systems.

[Arxiv](https://arxiv.org/abs/2503.22931)