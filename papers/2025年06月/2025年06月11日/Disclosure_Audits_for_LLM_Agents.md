# # 大型语言模型（LLM）代理的披露审核

发布时间：2025年06月11日

`LLM应用

摘要讨论了大型语言模型（LLM）作为代理在不同场景中的应用，并提出了一种用于审计对话隐私风险的框架。这属于LLM在实际应用中的具体使用和改进，因此归类为LLM应用。` `人工智能` `隐私保护`

> Disclosure Audits for LLM Agents

# 摘要

> # 摘要
大型语言模型（LLM）代理正逐步成为个人助理、客服机器人和临床助手。它们不仅带来了显著的运营优势，也因持续访问敏感数据而增加了隐私泄露风险。本研究提出了一种对话隐私审计框架，旨在量化并审计这些风险。我们设计的对话隐私泄露操控（CMPL）框架是一种迭代探测策略，专为测试执行严格隐私指令的代理而开发。与传统方法仅关注单一披露事件不同，CMPL 通过模拟现实的多轮交互，系统地揭示潜在漏洞。我们的评估表明，该框架能够揭示现有单轮防御无法阻止的隐私风险。本文不仅介绍了 CMPL 作为诊断工具，还提供了（1）基于可量化风险指标的审计流程，以及（2）用于评估代理实现中对话隐私的开放基准。


> Large Language Model agents have begun to appear as personal assistants, customer service bots, and clinical aides. While these applications deliver substantial operational benefits, they also require continuous access to sensitive data, which increases the likelihood of unauthorized disclosures. This study proposes an auditing framework for conversational privacy that quantifies and audits these risks. The proposed Conversational Manipulation for Privacy Leakage (CMPL) framework, is an iterative probing strategy designed to stress-test agents that enforce strict privacy directives. Rather than focusing solely on a single disclosure event, CMPL simulates realistic multi-turn interactions to systematically uncover latent vulnerabilities. Our evaluation on diverse domains, data modalities, and safety configurations demonstrate the auditing framework's ability to reveal privacy risks that are not deterred by existing single-turn defenses. In addition to introducing CMPL as a diagnostic tool, the paper delivers (1) an auditing procedure grounded in quantifiable risk metrics and (2) an open benchmark for evaluation of conversational privacy across agent implementations.

[Arxiv](https://arxiv.org/abs/2506.10171)