# 从助手到对手：移动大型语言模型代理的安全风险探索

发布时间：2025年05月19日

`LLM应用` `移动计算`

> From Assistants to Adversaries: Exploring the Security Risks of Mobile LLM Agents

# 摘要

> 大型语言模型（LLMs）的广泛应用正在引领移动计算领域进入一个全新范式——由LLM驱动的移动AI代理，这些代理能够直接在智能手机上分解和自动化复杂的任务。然而，这些代理的安全影响仍未得到充分研究。本文首次对移动LLM代理进行了全面的安全分析，涵盖了三个具有代表性的类别：设备制造商开发的系统级AI代理（例如YOYO Assistant）、第三方通用代理（例如Zhipu AI AutoGLM），以及新兴的代理框架（例如阿里巴巴移动代理）。我们首先分析了移动代理的一般工作流程，并从三个核心能力维度——基于语言的推理、基于GUI的交互以及系统级执行——识别了潜在的安全威胁。我们的分析揭示了11个独特的攻击面，这些攻击面均源于移动LLM代理的独特能力和交互模式，并贯穿其整个生命周期。为了在实际中探究这些威胁，我们引入了AgentScan，这是一个半自动化的安全分析框架，能够系统性地评估移动LLM代理在全部11种攻击场景下的表现。通过将AgentScan应用于广泛部署的九种代理，我们发现了一个令人担忧的趋势：每一种代理都易受定向攻击。在最严重的情况下，代理在八个不同的攻击向量上均存在漏洞。这些攻击可能导致行为偏差、隐私泄露，甚至完全的执行劫持。基于这些发现，我们提出了一套防御性设计原则和实践建议，以构建更安全的移动LLM代理。我们的披露已获得两大设备供应商的积极反馈。总体而言，这项研究凸显了在快速发展的LLM驱动移动自动化领域，建立标准化安全实践的紧迫性。


> The growing adoption of large language models (LLMs) has led to a new paradigm in mobile computing--LLM-powered mobile AI agents--capable of decomposing and automating complex tasks directly on smartphones. However, the security implications of these agents remain largely unexplored. In this paper, we present the first comprehensive security analysis of mobile LLM agents, encompassing three representative categories: System-level AI Agents developed by original equipment manufacturers (e.g., YOYO Assistant), Third-party Universal Agents (e.g., Zhipu AI AutoGLM), and Emerging Agent Frameworks (e.g., Alibaba Mobile Agent). We begin by analyzing the general workflow of mobile agents and identifying security threats across three core capability dimensions: language-based reasoning, GUI-based interaction, and system-level execution. Our analysis reveals 11 distinct attack surfaces, all rooted in the unique capabilities and interaction patterns of mobile LLM agents, and spanning their entire operational lifecycle. To investigate these threats in practice, we introduce AgentScan, a semi-automated security analysis framework that systematically evaluates mobile LLM agents across all 11 attack scenarios. Applying AgentScan to nine widely deployed agents, we uncover a concerning trend: every agent is vulnerable to targeted attacks. In the most severe cases, agents exhibit vulnerabilities across eight distinct attack vectors. These attacks can cause behavioral deviations, privacy leakage, or even full execution hijacking. Based on these findings, we propose a set of defensive design principles and practical recommendations for building secure mobile LLM agents. Our disclosures have received positive feedback from two major device vendors. Overall, this work highlights the urgent need for standardized security practices in the fast-evolving landscape of LLM-driven mobile automation.

[Arxiv](https://arxiv.org/abs/2505.12981)