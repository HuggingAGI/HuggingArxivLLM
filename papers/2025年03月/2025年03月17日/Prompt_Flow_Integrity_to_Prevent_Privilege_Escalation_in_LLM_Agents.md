# 确保 LLM 智能体的提示流完整性，防止权限提升

发布时间：2025年03月17日

`LLM应用` `软件开发` `系统安全`

> Prompt Flow Integrity to Prevent Privilege Escalation in LLM Agents

# 摘要

> 大型语言模型（LLMs）与插件的融合，能够打造功能强大的LLM代理，提供多样化的服务。与传统软件不同，LLM代理的行为由用户或插件数据提供的自然语言提示在运行时动态决定。这种灵活性不仅开创了一种全新计算范式，带来无限的能力和可编程性，但也引入了新的安全风险，特别是容易遭受权限提升攻击。此外，用户的提示内容可能被LLM代理解读为不安全的操作，产生非确定性行为，这可能被攻击者利用。为应对这些安全挑战，我们提出了Prompt Flow Integrity（PFI），这是一种面向系统安全的解决方案，旨在防止LLM代理中的权限提升问题。通过深入分析LLM代理的架构特性，PFI采用了三大核心缓解技术：识别不受信任的数据、对LLM代理实施最小权限原则，以及验证不安全的数据流。我们的评估结果表明，PFI不仅能够有效缓解权限提升攻击，还能成功保留LLM代理的实用功能。

> Large Language Models (LLMs) are combined with plugins to create powerful LLM agents that provide a wide range of services. Unlike traditional software, LLM agent's behavior is determined at runtime by natural language prompts from either user or plugin's data. This flexibility enables a new computing paradigm with unlimited capabilities and programmability, but also introduces new security risks, vulnerable to privilege escalation attacks. Moreover, user prompt is prone to be interpreted in an insecure way by LLM agents, creating non-deterministic behaviors that can be exploited by attackers. To address these security risks, we propose Prompt Flow Integrity (PFI), a system security-oriented solution to prevent privilege escalation in LLM agents. Analyzing the architectural characteristics of LLM agents, PFI features three mitigation techniques -- i.e., untrusted data identification, enforcing least privilege on LLM agents, and validating unsafe data flows. Our evaluation result shows that PFI effectively mitigates privilege escalation attacks while successfully preserving the utility of LLM agents.

[Arxiv](https://arxiv.org/abs/2503.15547)