# VulnBot: 多智能体协作框架的自动化渗透测试

发布时间：2025年01月23日

`Agent

理由：这篇论文提出了一个基于LLM的多代理系统框架VulnBot，用于自动化渗透测试。该系统通过模拟人类渗透测试团队的协作流程，将复杂任务拆分为多个阶段，并通过角色分工、路径规划、代理通信等机制来实现任务的逻辑执行。这些特征表明该论文主要关注的是多代理系统的设计和应用，因此应归类为Agent。` `网络安全` `渗透测试`

> VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework

# 摘要

> 渗透测试是识别和修复网络安全漏洞的关键手段，但手动操作耗时耗力。现有的LLM辅助或自动化渗透测试方法常因缺乏上下文理解和生成过多杂乱数据而效率低下。本文提出VulnBot，一个基于LLM的多代理系统框架，模拟人类渗透测试团队的协作流程。为克服传统方法的低效性和对人工的依赖，VulnBot将复杂任务拆分为侦察、扫描和利用三个阶段，并通过渗透任务图（PTG）确保逻辑执行。其核心设计包括角色分工、路径规划、代理通信和生成性行为。实验显示，VulnBot在自动化渗透测试中表现优于GPT-4和Llama3，尤其在真实环境中的全自主测试中展现了强大潜力。

> Penetration testing is a vital practice for identifying and mitigating vulnerabilities in cybersecurity systems, but its manual execution is labor-intensive and time-consuming. Existing large language model (LLM)-assisted or automated penetration testing approaches often suffer from inefficiencies, such as a lack of contextual understanding and excessive, unstructured data generation. This paper presents VulnBot, an automated penetration testing framework that leverages LLMs to simulate the collaborative workflow of human penetration testing teams through a multi-agent system. To address the inefficiencies and reliance on manual intervention in traditional penetration testing methods, VulnBot decomposes complex tasks into three specialized phases: reconnaissance, scanning, and exploitation. These phases are guided by a penetration task graph (PTG) to ensure logical task execution. Key design features include role specialization, penetration path planning, inter-agent communication, and generative penetration behavior. Experimental results demonstrate that VulnBot outperforms baseline models such as GPT-4 and Llama3 in automated penetration testing tasks, particularly showcasing its potential in fully autonomous testing on real-world machines.

[Arxiv](https://arxiv.org/abs/2501.13411)