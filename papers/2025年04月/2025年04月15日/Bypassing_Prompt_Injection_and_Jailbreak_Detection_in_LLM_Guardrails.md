# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月15日

`LLM理论` `网络安全` `人工智能`

> Bypassing Prompt Injection and Jailbreak Detection in LLM Guardrails

# 摘要

> 大型语言模型 (LLMs) 的护栏系统旨在防范提示注入和越狱攻击，但仍然存在被规避的风险。我们通过传统字符注入技术和算法对抗机器学习 (AML) 规避技术，展示了绕过 LLM 提示注入和越狱检测系统的方法。测试结果表明，这两种方法均可成功规避检测，甚至在某些情况下实现 100% 的规避成功率。此外，我们发现攻击者可以通过利用离线白盒模型计算的词重要性排名，提升针对黑盒目标的攻击成功率。我们的研究揭示了当前 LLM 保护机制中的漏洞，并强调了构建更加稳健的护栏系统的必要性。


> Large Language Models (LLMs) guardrail systems are designed to protect against prompt injection and jailbreak attacks. However, they remain vulnerable to evasion techniques. We demonstrate two approaches for bypassing LLM prompt injection and jailbreak detection systems via traditional character injection methods and algorithmic Adversarial Machine Learning (AML) evasion techniques. Through testing against six prominent protection systems, including Microsoft's Azure Prompt Shield and Meta's Prompt Guard, we show that both methods can be used to evade detection while maintaining adversarial utility achieving in some instances up to 100% evasion success. Furthermore, we demonstrate that adversaries can enhance Attack Success Rates (ASR) against black-box targets by leveraging word importance ranking computed by offline white-box models. Our findings reveal vulnerabilities within current LLM protection mechanisms and highlight the need for more robust guardrail systems.

[Arxiv](https://arxiv.org/abs/2504.11168)