# 从盟友到对手：利用对抗性注入操控LLM工具调用

发布时间：2024年12月13日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLM）在工具调用系统中的安全问题，特别是通过对抗性工具注入来攻击LLM工具调用系统的漏洞。虽然涉及安全风险，但其核心关注点仍然是LLM在实际应用中的工具调用机制及其潜在的安全问题，因此应归类为LLM应用。` `网络安全` `人工智能`

> From Allies to Adversaries: Manipulating LLM Tool-Calling through Adversarial Injection

# 摘要

> # 摘要
工具调用通过集成外部工具，显著提升了大型语言模型（LLM）在多任务中的功能。然而，这种集成也带来了新的安全风险，尤其是在LLM的工具调度机制中，这些风险尚未被深入研究。为此，我们提出了ToolCommander，一个通过对抗性工具注入来攻击LLM工具调用系统漏洞的创新框架。该框架采用了两阶段攻击策略：首先注入恶意工具收集用户查询，随后根据窃取的信息动态更新工具以增强攻击效果。ToolCommander不仅能窃取隐私、发起拒绝服务攻击，还能通过触发未计划的工具调用来操纵商业竞争。在某些情况下，隐私窃取的攻击成功率（ASR）高达91.67%，而拒绝服务和未计划工具调用的ASR更是达到100%。我们的研究表明，这些漏洞可能带来比工具调用系统滥用更严重的后果，亟需强有力的防御策略来保障LLM工具调用系统的安全。

> Tool-calling has changed Large Language Model (LLM) applications by integrating external tools, significantly enhancing their functionality across diverse tasks. However, this integration also introduces new security vulnerabilities, particularly in the tool scheduling mechanisms of LLM, which have not been extensively studied. To fill this gap, we present ToolCommander, a novel framework designed to exploit vulnerabilities in LLM tool-calling systems through adversarial tool injection. Our framework employs a well-designed two-stage attack strategy. Firstly, it injects malicious tools to collect user queries, then dynamically updates the injected tools based on the stolen information to enhance subsequent attacks. These stages enable ToolCommander to execute privacy theft, launch denial-of-service attacks, and even manipulate business competition by triggering unscheduled tool-calling. Notably, the ASR reaches 91.67% for privacy theft and hits 100% for denial-of-service and unscheduled tool calling in certain cases. Our work demonstrates that these vulnerabilities can lead to severe consequences beyond simple misuse of tool-calling systems, underscoring the urgent need for robust defensive strategies to secure LLM Tool-calling systems.

[Arxiv](https://arxiv.org/abs/2412.10198)