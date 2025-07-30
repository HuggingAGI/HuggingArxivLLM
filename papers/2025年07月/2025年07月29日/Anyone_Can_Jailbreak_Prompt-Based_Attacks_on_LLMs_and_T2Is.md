# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年07月29日

`LLM应用

摘要讨论了大型语言模型和文本到图像模型在实际应用中的安全问题，特别是越狱攻击及其防御策略，属于模型应用层面的研究。` `内容安全` `人工智能`

> Anyone Can Jailbreak: Prompt-Based Attacks on LLMs and T2Is

# 摘要

> 尽管在对齐和内容审核方面取得了显著进展，大型语言模型 (LLMs) 和文本到图像 (T2I) 系统仍然容易受到提示攻击，即所谓的“越狱攻击”。与传统对抗样本不同，当今许多越狱攻击是由普通用户通过巧妙编写的提示词轻松实现的。本文采用系统研究方法，探讨非专家如何通过多轮叙事升级、词汇伪装、隐含链式推理、虚构冒充和微妙语义编辑等技术可靠地绕过安全机制。我们提出了一种涵盖文本输出和 T2I 模型的统一提示级越狱策略分类法，该分类法基于流行 API 的实证案例研究。我们的分析揭示，从输入过滤到输出验证的审核流程每个阶段都可以通过简单易行的策略绕过。最后，我们强调需要上下文感知的防御措施，以应对这些越狱攻击在现实环境中被轻易复制的紧迫性。

> Despite significant advancements in alignment and content moderation, large language models (LLMs) and text-to-image (T2I) systems remain vulnerable to prompt-based attacks known as jailbreaks. Unlike traditional adversarial examples requiring expert knowledge, many of today's jailbreaks are low-effort, high-impact crafted by everyday users with nothing more than cleverly worded prompts. This paper presents a systems-style investigation into how non-experts reliably circumvent safety mechanisms through techniques such as multi-turn narrative escalation, lexical camouflage, implication chaining, fictional impersonation, and subtle semantic edits. We propose a unified taxonomy of prompt-level jailbreak strategies spanning both text-output and T2I models, grounded in empirical case studies across popular APIs. Our analysis reveals that every stage of the moderation pipeline, from input filtering to output validation, can be bypassed with accessible strategies. We conclude by highlighting the urgent need for context-aware defenses that reflect the ease with which these jailbreaks can be reproduced in real-world settings.

[Arxiv](https://arxiv.org/abs/2507.21820)