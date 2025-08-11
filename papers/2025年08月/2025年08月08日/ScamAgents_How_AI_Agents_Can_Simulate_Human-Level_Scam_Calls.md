# ScamAgents：AI代理如何模拟人类级别的诈骗电话

发布时间：2025年08月08日

`Agent

理由：这篇论文主要讨论了基于大型语言模型的对话代理ScamAgent的设计和应用，特别是其在生成诈骗脚本方面的能力。虽然它涉及LLM的应用，但核心内容集中在对话代理的功能、安全问题以及其滥用可能性，因此更符合Agent分类。` `金融安全`

> ScamAgents: How AI Agents Can Simulate Human-Level Scam Calls

# 摘要

> 大型语言模型 (LLMs) 虽然表现出色，但其潜在滥用风险日益引发关注。本文介绍的 ScamAgent 是一个基于 LLMs 的自主多轮对话代理，能够生成高度逼真的诈骗电话脚本，模拟真实欺诈场景。与以往专注于单一提示滥用的研究不同，ScamAgent 具备对话记忆功能，能动态适应模拟用户回应，并在对话过程中运用欺骗性说服策略。我们发现，现有 LLM 的安全防护措施，包括拒绝机制和内容过滤器，对这类基于代理的威胁毫无招架之力。即使是在具备强大提示级别防护措施的模型中，当提示被分解、伪装或在代理框架内逐步呈现时，这些防护措施也会被轻易绕过。我们还展示了如何利用现代文本转语音系统将诈骗脚本转化为逼真的语音通话，从而完成一个全自动化的诈骗流程。我们的研究结果强调了对多轮安全审计、代理级别控制框架以及检测和破坏由生成式 AI 驱动的对话欺骗的新方法的迫切需求。

> Large Language Models (LLMs) have demonstrated impressive fluency and reasoning capabilities, but their potential for misuse has raised growing concern. In this paper, we present ScamAgent, an autonomous multi-turn agent built on top of LLMs, capable of generating highly realistic scam call scripts that simulate real-world fraud scenarios. Unlike prior work focused on single-shot prompt misuse, ScamAgent maintains dialogue memory, adapts dynamically to simulated user responses, and employs deceptive persuasion strategies across conversational turns. We show that current LLM safety guardrails, including refusal mechanisms and content filters, are ineffective against such agent-based threats. Even models with strong prompt-level safeguards can be bypassed when prompts are decomposed, disguised, or delivered incrementally within an agent framework. We further demonstrate the transformation of scam scripts into lifelike voice calls using modern text-to-speech systems, completing a fully automated scam pipeline. Our findings highlight an urgent need for multi-turn safety auditing, agent-level control frameworks, and new methods to detect and disrupt conversational deception powered by generative AI.

[Arxiv](https://arxiv.org/abs/2508.06457)