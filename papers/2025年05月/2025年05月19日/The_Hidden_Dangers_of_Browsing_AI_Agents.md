# 浏览AI助手暗藏的危机

发布时间：2025年05月19日

`LLM应用` `网络安全` `信息安全`

> The Hidden Dangers of Browsing AI Agents

# 摘要

> 基于大型语言模型（LLMs）的自主浏览代理正被越来越多地用于自动化网络任务。然而，它们对动态内容、工具执行和用户提供的数据的依赖使其暴露于广泛的攻击面。本文对这类代理进行了全面的安全评估，重点关注多架构层中的系统性漏洞。我们的工作概述了首个针对浏览代理的端到端威胁模型，并为在现实环境中安全部署它们提供了可操作的指导。为应对发现的威胁，我们提出了一种多层次防御策略，涵盖输入清理、规划器执行隔离、形式化分析器和会话保护措施。这些措施防范了初始访问和后利用阶段的攻击向量。通过对一个流行的开源项目——Browser Use的白盒分析，我们展示了不受信任的网络内容如何劫持代理行为并导致严重的安全漏洞。我们的研究发现包括提示注入、绕过域名验证和凭证窃取，这些均通过披露的CVE和有效的概念验证漏洞得到了证实。

> Autonomous browsing agents powered by large language models (LLMs) are increasingly used to automate web-based tasks. However, their reliance on dynamic content, tool execution, and user-provided data exposes them to a broad attack surface. This paper presents a comprehensive security evaluation of such agents, focusing on systemic vulnerabilities across multiple architectural layers. Our work outlines the first end-to-end threat model for browsing agents and provides actionable guidance for securing their deployment in real-world environments. To address discovered threats, we propose a defense in depth strategy incorporating input sanitization, planner executor isolation, formal analyzers, and session safeguards. These measures protect against both initial access and post exploitation attack vectors. Through a white box analysis of a popular open source project, Browser Use, we demonstrate how untrusted web content can hijack agent behavior and lead to critical security breaches. Our findings include prompt injection, domain validation bypass, and credential exfiltration, evidenced by a disclosed CVE and a working proof of concept exploit.

[Arxiv](https://arxiv.org/abs/2505.13076)