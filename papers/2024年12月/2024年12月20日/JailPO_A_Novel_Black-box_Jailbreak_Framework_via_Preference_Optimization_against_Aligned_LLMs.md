# JailPO：一种通过针对对齐的大型语言模型进行偏好优化的新型黑盒越狱框架

发布时间：2024年12月20日

`LLM应用` `语言模型` `安全防御`

> JailPO: A Novel Black-box Jailbreak Framework via Preference Optimization against Aligned LLMs

# 摘要

> 大型语言模型（LLMs）与人类反馈相适配，近来备受瞩目。然而，它易受越狱攻击，即敌手操控提示来诱导有害输出。对越狱攻击的探究能让我们探查LLMs的脆弱之处，并进一步指引我们增强其安全性。可惜的是，现有的技术主要依赖手工制作的模板或基于生成的优化，在可扩展性、效率和通用性上存在难题。为应对这些问题，我们推出了JailPO，这是一个全新的黑盒越狱框架，用于检验LLM的适配情况。为了达成可扩展性和通用性，JailPO精心训练攻击模型，自动生成隐秘的越狱提示。此外，我们引入了一种基于偏好优化的攻击方法，以增强越狱效果，进而提升效率。为分析模型的漏洞，我们提供了三种灵活的越狱模式。大量实验表明，JailPO不但在保持有效性的同时实现了攻击流程的自动化，而且在效率、通用性和抵御防御方面相较于基线表现更优。另外，我们对三种JailPO模式的分析显示，基于复杂模板的攻击具有更强的攻击力度，而隐蔽的问题转换会引发更危险的响应，且更易绕过防御机制。

> Large Language Models (LLMs) aligned with human feedback have recently garnered significant attention. However, it remains vulnerable to jailbreak attacks, where adversaries manipulate prompts to induce harmful outputs. Exploring jailbreak attacks enables us to investigate the vulnerabilities of LLMs and further guides us in enhancing their security. Unfortunately, existing techniques mainly rely on handcrafted templates or generated-based optimization, posing challenges in scalability, efficiency and universality. To address these issues, we present JailPO, a novel black-box jailbreak framework to examine LLM alignment. For scalability and universality, JailPO meticulously trains attack models to automatically generate covert jailbreak prompts. Furthermore, we introduce a preference optimization-based attack method to enhance the jailbreak effectiveness, thereby improving efficiency. To analyze model vulnerabilities, we provide three flexible jailbreak patterns. Extensive experiments demonstrate that JailPO not only automates the attack process while maintaining effectiveness but also exhibits superior performance in efficiency, universality, and robustness against defenses compared to baselines. Additionally, our analysis of the three JailPO patterns reveals that attacks based on complex templates exhibit higher attack strength, whereas covert question transformations elicit riskier responses and are more likely to bypass defense mechanisms.

[Arxiv](https://arxiv.org/abs/2412.15623)