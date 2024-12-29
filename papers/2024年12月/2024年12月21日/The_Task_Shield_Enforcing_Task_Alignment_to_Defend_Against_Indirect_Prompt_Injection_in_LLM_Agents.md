# 《任务护盾：通过强制任务对齐来抵御 LLM 代理中的间接提示注入》

发布时间：2024年12月21日

`Agent` `语言模型`

> The Task Shield: Enforcing Task Alignment to Defend Against Indirect Prompt Injection in LLM Agents

# 摘要

> 大型语言模型（LLM）代理正日益被用作能够通过工具集成来执行复杂现实任务的对话助手。这种与外部系统交互和处理各类数据源的强大能力，却带来了显著的安全漏洞。尤其是间接提示注入攻击构成重大威胁，外部数据源中嵌入的恶意指令能操纵代理偏离用户意图。虽然基于规则约束、源聚焦和认证协议的现有防御措施展现出一定前景，但它们难以在保障强大安全性的同时保留任务功能。我们提出了一个新颖且独特的观点，将代理安全从防止有害行为转变为确保任务对齐，要求每个代理行为都服务于用户目标。基于此，我们开发了 Task Shield 这一测试时防御机制，它能系统地验证每个指令和工具调用是否有助于用户指定的目标。通过在 AgentDojo 基准上的实验，我们表明 Task Shield 使 GPT-4o 的攻击成功率降低（2.07％），同时保持了较高的任务效用（69.79％）。

> Large Language Model (LLM) agents are increasingly being deployed as conversational assistants capable of performing complex real-world tasks through tool integration. This enhanced ability to interact with external systems and process various data sources, while powerful, introduces significant security vulnerabilities. In particular, indirect prompt injection attacks pose a critical threat, where malicious instructions embedded within external data sources can manipulate agents to deviate from user intentions. While existing defenses based on rule constraints, source spotlighting, and authentication protocols show promise, they struggle to maintain robust security while preserving task functionality. We propose a novel and orthogonal perspective that reframes agent security from preventing harmful actions to ensuring task alignment, requiring every agent action to serve user objectives. Based on this insight, we develop Task Shield, a test-time defense mechanism that systematically verifies whether each instruction and tool call contributes to user-specified goals. Through experiments on the AgentDojo benchmark, we demonstrate that Task Shield reduces attack success rates (2.07\%) while maintaining high task utility (69.79\%) on GPT-4o.

[Arxiv](https://arxiv.org/abs/2412.16682)