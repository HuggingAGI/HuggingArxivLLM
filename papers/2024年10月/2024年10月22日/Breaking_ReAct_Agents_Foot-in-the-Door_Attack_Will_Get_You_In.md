# 破解ReAct智能体：Foot-in-the-Door攻击助你轻松入侵

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了基于大型语言模型（LLM）的自主代理（ReAct代理）的安全漏洞，并提出了一种攻击方法和相应的防御机制。研究的核心是代理的行为和安全性，因此应归类为Agent。` `人工智能` `网络安全`

> Breaking ReAct Agents: Foot-in-the-Door Attack Will Get You In

# 摘要

> 随着大型语言模型（LLMs）的快速发展，基于LLM的自主代理日益普及，理解其安全漏洞变得至关重要。我们研究了一种简单而有效的“foot-in-the-door攻击”方法，用于利用ReAct代理。实验表明，由无害且无关的请求（如基本计算）引发的间接提示注入攻击，会显著增加代理执行后续恶意操作的可能性。一旦ReAct代理的思维中包含特定工具或操作，后续步骤中执行该工具的概率大幅上升，因为代理很少重新评估其操作。因此，即使是随机的、无害的请求也能为攻击者打开“foot-in-the-door”，使其能够将恶意指令嵌入代理的思维过程，增加其受有害指令影响的风险。为缓解这一漏洞，我们建议引入一种简单的反思机制，在执行过程中提示代理重新评估其操作的安全性，从而降低此类攻击的成功率。

> Following the advancement of large language models (LLMs), the development of LLM-based autonomous agents has become increasingly prevalent. As a result, the need to understand the security vulnerabilities of these agents has become a critical task. We examine how ReAct agents can be exploited using a straightforward yet effective method we refer to as the foot-in-the-door attack. Our experiments show that indirect prompt injection attacks, prompted by harmless and unrelated requests (such as basic calculations) can significantly increase the likelihood of the agent performing subsequent malicious actions. Our results show that once a ReAct agents thought includes a specific tool or action, the likelihood of executing this tool in the subsequent steps increases significantly, as the agent seldom re-evaluates its actions. Consequently, even random, harmless requests can establish a foot-in-the-door, allowing an attacker to embed malicious instructions into the agents thought process, making it more susceptible to harmful directives. To mitigate this vulnerability, we propose implementing a simple reflection mechanism that prompts the agent to reassess the safety of its actions during execution, which can help reduce the success of such attacks.

[Arxiv](https://arxiv.org/abs/2410.16950)