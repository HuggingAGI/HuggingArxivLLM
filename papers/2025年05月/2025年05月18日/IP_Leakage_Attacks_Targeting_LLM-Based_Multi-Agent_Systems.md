# 针对基于LLM的多智能体系统的IP泄密攻击

发布时间：2025年05月18日

`Agent` `多智能体系统` `网络安全`

> IP Leakage Attacks Targeting LLM-Based Multi-Agent Systems

# 摘要

> 大型语言模型 (LLMs) 的快速发展催生了多智能体系统 (MAS)，通过协作方式执行复杂任务。然而，MAS 的复杂性，包括其架构和智能体交互方式，引发了关于知识产权 (IP) 保护的重大担忧。本文介绍 MASLEAK，一种新型攻击框架，旨在从 MAS 应用中提取敏感信息。MASLEAK 针对实际的黑盒场景，攻击者对 MAS 架构或智能体配置无任何先验知识，仅能通过 MAS 的公共 API 提交攻击查询 $q$，并观察最终智能体的输出。受计算机蠕虫传播并感染漏洞网络主机的启发，MASLEAK 精心设计对抗性查询 $q$，以诱取、传播并保留来自每个 MAS 智能体的响应，揭示完整的专有组件，包括智能体数量、系统拓扑、系统提示、任务指令和工具使用情况。我们构建了第一个包含 810 个应用的 MAS 应用合成数据集，并评估 MASLEAK 在 Coze 和 CrewAI 等真实世界 MAS 应用中的表现。MASLEAK 在提取 MAS IP 方面表现出色，系统提示和任务指令的平均攻击成功率高达 87%，系统架构的成功率在大多数情况下达到 92%。最后，我们探讨了研究发现的影响及潜在防御措施。

> The rapid advancement of Large Language Models (LLMs) has led to the emergence of Multi-Agent Systems (MAS) to perform complex tasks through collaboration. However, the intricate nature of MAS, including their architecture and agent interactions, raises significant concerns regarding intellectual property (IP) protection. In this paper, we introduce MASLEAK, a novel attack framework designed to extract sensitive information from MAS applications. MASLEAK targets a practical, black-box setting, where the adversary has no prior knowledge of the MAS architecture or agent configurations. The adversary can only interact with the MAS through its public API, submitting attack query $q$ and observing outputs from the final agent. Inspired by how computer worms propagate and infect vulnerable network hosts, MASLEAK carefully crafts adversarial query $q$ to elicit, propagate, and retain responses from each MAS agent that reveal a full set of proprietary components, including the number of agents, system topology, system prompts, task instructions, and tool usages. We construct the first synthetic dataset of MAS applications with 810 applications and also evaluate MASLEAK against real-world MAS applications, including Coze and CrewAI. MASLEAK achieves high accuracy in extracting MAS IP, with an average attack success rate of 87% for system prompts and task instructions, and 92% for system architecture in most cases. We conclude by discussing the implications of our findings and the potential defenses.

[Arxiv](https://arxiv.org/abs/2505.12442)