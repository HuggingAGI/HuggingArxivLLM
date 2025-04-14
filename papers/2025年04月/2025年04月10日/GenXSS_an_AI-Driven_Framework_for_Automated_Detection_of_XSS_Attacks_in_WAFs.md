# # GenXSS: 专为 Web 应用防火墙设计的 AI 驱动 XSS 攻击自动化检测框架

发布时间：2025年04月10日

`LLM应用

摘要中讨论了大型语言模型在生成XSS载荷和自动化防御机制中的应用，属于LLM的实际应用案例。` `网络安全` `Web应用安全`

> GenXSS: an AI-Driven Framework for Automated Detection of XSS Attacks in WAFs

# 摘要

> 随着对网络服务依赖的加深，网络安全威胁日益严峻，尤其是针对Web应用客户端层的跨站脚本（XSS）攻击。传统Web应用防火墙（WAF）因规则需手动更新，难以应对高度混淆和复杂的攻击。本文提出一种基于大型语言模型（LLMs）的创新生成式AI框架，旨在提升XSS防护能力。该框架两大核心目标：(1) 利用上下文学习生成复杂且语法严谨的XSS载荷；(2) 通过自动化防御机制，测试攻击、分类绕过行为并生成有效安全规则。实验中，GPT-4o成功生成264个XSS载荷，83%通过验证，80%绕过了OWASP标准规则集保护的ModSecurity WAF。仅15条新规则便拦截了86%的攻击。相比之下，Google Gemini Pro的63%绕过率凸显了不同LLMs的性能差异。

> The increasing reliance on web services has led to a rise in cybersecurity threats, particularly Cross-Site Scripting (XSS) attacks, which target client-side layers of web applications by injecting malicious scripts. Traditional Web Application Firewalls (WAFs) struggle to detect highly obfuscated and complex attacks, as their rules require manual updates. This paper presents a novel generative AI framework that leverages Large Language Models (LLMs) to enhance XSS mitigation. The framework achieves two primary objectives: (1) generating sophisticated and syntactically validated XSS payloads using in-context learning, and (2) automating defense mechanisms by testing these attacks against a vulnerable application secured by a WAF, classifying bypassing attacks, and generating effective WAF security rules. Experimental results using GPT-4o demonstrate the framework's effectiveness generating 264 XSS payloads, 83% of which were validated, with 80% bypassing ModSecurity WAF equipped with an industry standard security rule set developed by the Open Web Application Security Project (OWASP) to protect against web vulnerabilities. Through rule generation, 86% of previously successful attacks were blocked using only 15 new rules. In comparison, Google Gemini Pro achieved a lower bypass rate of 63%, highlighting performance differences across LLMs.

[Arxiv](https://arxiv.org/abs/2504.08176)