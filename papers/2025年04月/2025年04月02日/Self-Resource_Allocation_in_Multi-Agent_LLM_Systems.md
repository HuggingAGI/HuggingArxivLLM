# 多智能体LLM系统的自资源分配

发布时间：2025年04月02日

`LLM应用` `智能体系统` `任务管理`

> Self-Resource Allocation in Multi-Agent LLM Systems

# 摘要

> 随着 LLMs 作为智能体的发展，研究者们开始关注将多个智能体连接成多智能体系统，以并发解决任务，重点关注它们在任务分配和协调中的作用。本文探讨了 LLMs 如何有效在多个智能体之间分配计算任务，考虑成本、效率和性能等因素。在本研究中，我们解答了关键问题，包括 LLMs 作为编排器和规划器的有效性，以及它们在任务分配和协调中的表现。实验结果表明，LLMs 在资源分配任务中能够实现高有效性和准确性。我们发现，规划器方法在处理并发动作方面优于编排器方法，从而提高了效率并更好地利用了智能体。此外，提供关于工人能力的显式信息可以提升规划器的分配策略，特别是在处理次优工人时。

> With the development of LLMs as agents, there is a growing interest in connecting multiple agents into multi-agent systems to solve tasks concurrently, focusing on their role in task assignment and coordination. This paper explores how LLMs can effectively allocate computational tasks among multiple agents, considering factors such as cost, efficiency, and performance. In this work, we address key questions, including the effectiveness of LLMs as orchestrators and planners, comparing their effectiveness in task assignment and coordination. Our experiments demonstrate that LLMs can achieve high validity and accuracy in resource allocation tasks. We find that the planner method outperforms the orchestrator method in handling concurrent actions, resulting in improved efficiency and better utilization of agents. Additionally, we show that providing explicit information about worker capabilities enhances the allocation strategies of planners, particularly when dealing with suboptimal workers.

[Arxiv](https://arxiv.org/abs/2504.02051)