# 医疗AI代理面临的新兴网络攻击风险

发布时间：2025年04月02日

`Agent

这篇论文主要讨论了AI代理在医疗和健康领域的应用及其面临的网络安全风险，因此属于Agent类别。` `网络安全`

> Emerging Cyber Attack Risks of Medical AI Agents

# 摘要

> 大型语言模型（LLMs）驱动的AI代理在医疗和健康领域展现出高度自主性，能够通过多种工具在开放环境中运作。然而，随着能力的提升，网络安全风险也随之增加。本研究聚焦于医疗AI代理的网络安全漏洞，揭示了通过网页嵌入的对抗性提示，网络攻击者可以实现以下攻击：i) 在代理响应中注入虚假信息；ii) 强制代理操纵推荐内容（如医疗产品和服务）；iii) 窃取用户与代理的历史对话，导致敏感医疗信息泄露；iv) 通过恶意URL引发计算机系统劫持。测试结果显示，此类攻击在大多数主流LLMs驱动的代理中均能成功，其中DeepSeek-R1等推理模型最为脆弱。

> Large language models (LLMs)-powered AI agents exhibit a high level of autonomy in addressing medical and healthcare challenges. With the ability to access various tools, they can operate within an open-ended action space. However, with the increase in autonomy and ability, unforeseen risks also arise. In this work, we investigated one particular risk, i.e., cyber attack vulnerability of medical AI agents, as agents have access to the Internet through web browsing tools. We revealed that through adversarial prompts embedded on webpages, cyberattackers can: i) inject false information into the agent's response; ii) they can force the agent to manipulate recommendation (e.g., healthcare products and services); iii) the attacker can also steal historical conversations between the user and agent, resulting in the leak of sensitive/private medical information; iv) furthermore, the targeted agent can also cause a computer system hijack by returning a malicious URL in its response. Different backbone LLMs were examined, and we found such cyber attacks can succeed in agents powered by most mainstream LLMs, with the reasoning models such as DeepSeek-R1 being the most vulnerable.

[Arxiv](https://arxiv.org/abs/2504.03759)