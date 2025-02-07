# Speak Easy: 用简单交互轻松诱导LLMs产生有害越狱

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在安全对齐方面的漏洞，特别是越狱攻击的问题。论文提出了一个衡量LLM响应促成有害行为有效性的方法（HarmScore）和一个简单的多步骤、多语言攻击框架（Speak Easy），并通过实验验证了这些方法的有效性。这些内容主要涉及LLM在实际应用中的安全性和漏洞问题，因此应归类为LLM应用。` `人工智能安全`

> Speak Easy: Eliciting Harmful Jailbreaks from LLMs with Simple Interactions

# 摘要

> 尽管进行了大量安全对齐工作，大型语言模型（LLMs）仍易受越狱攻击，导致有害行为。现有研究多聚焦于需要技术专长的攻击方法，但两个关键问题尚未深入探讨：（1）越狱响应是否真能帮助普通用户实施有害行为？（2）在常见、简单的人与LLM交互中是否存在安全漏洞？本文表明，当LLM响应兼具可操作性和信息性时，最易促成有害行为——这两个特性在多步骤、多语言交互中极易触发。基于此，我们提出了HarmScore，用于衡量LLM响应促成有害行为的有效性，以及Speak Easy，一种简单的多步骤、多语言攻击框架。通过将Speak Easy集成到直接请求和越狱基线中，我们在四个安全基准测试中观察到，开源和专有LLM的攻击成功率平均提升了0.319，HarmScore平均提升了0.426。我们的研究揭示了一个关键但常被忽视的漏洞：恶意用户可轻松利用常见交互模式实现有害意图。

> Despite extensive safety alignment efforts, large language models (LLMs) remain vulnerable to jailbreak attacks that elicit harmful behavior. While existing studies predominantly focus on attack methods that require technical expertise, two critical questions remain underexplored: (1) Are jailbroken responses truly useful in enabling average users to carry out harmful actions? (2) Do safety vulnerabilities exist in more common, simple human-LLM interactions? In this paper, we demonstrate that LLM responses most effectively facilitate harmful actions when they are both actionable and informative--two attributes easily elicited in multi-step, multilingual interactions. Using this insight, we propose HarmScore, a jailbreak metric that measures how effectively an LLM response enables harmful actions, and Speak Easy, a simple multi-step, multilingual attack framework. Notably, by incorporating Speak Easy into direct request and jailbreak baselines, we see an average absolute increase of 0.319 in Attack Success Rate and 0.426 in HarmScore in both open-source and proprietary LLMs across four safety benchmarks. Our work reveals a critical yet often overlooked vulnerability: Malicious users can easily exploit common interaction patterns for harmful intentions.

[Arxiv](https://arxiv.org/abs/2502.04322)