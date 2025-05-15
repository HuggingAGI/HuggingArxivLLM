# 对抗性后缀过滤：LLMs的防御流程

发布时间：2025年05月14日

`LLM应用` `人工智能安全` `人工智能`

> Adversarial Suffix Filtering: a Defense Pipeline for LLMs

# 摘要

> 大语言模型（LLMs）正被越来越多地应用于自主系统和公开环境，但这些模型仍易受 jailbreak 漏洞威胁，可能影响其安全性和可信度。对抗后缀被视为当前最先进的 jailbreak 技术，不仅优于传统方法，甚至在黑盒环境下也屡屡得逞。现有防御手段要么受限于模型内部架构访问，限制了多样化部署，要么大幅增加资源消耗，甚至可能被简单的提示工程绕过。我们提出了一种轻量级、模型不可知的防御方案——Adversarial Suffix Filtering（ASF），旨在保护 LLMs 免受对抗后缀攻击。ASF 通过检测并移除提示中的对抗后缀，有效中和恶意注入。实验表明，ASF 在黑盒和白盒攻击下均表现优异，将现有最先进攻击方法的成功率降至 4% 以下，同时对正常场景下的模型性能影响极小。

> Large Language Models (LLMs) are increasingly embedded in autonomous systems and public-facing environments, yet they remain susceptible to jailbreak vulnerabilities that may undermine their security and trustworthiness. Adversarial suffixes are considered to be the current state-of-the-art jailbreak, consistently outperforming simpler methods and frequently succeeding even in black-box settings. Existing defenses rely on access to the internal architecture of models limiting diverse deployment, increase memory and computation footprints dramatically, or can be bypassed with simple prompt engineering methods. We introduce $\textbf{Adversarial Suffix Filtering}$ (ASF), a lightweight novel model-agnostic defensive pipeline designed to protect LLMs against adversarial suffix attacks. ASF functions as an input preprocessor and sanitizer that detects and filters adversarially crafted suffixes in prompts, effectively neutralizing malicious injections. We demonstrate that ASF provides comprehensive defense capabilities across both black-box and white-box attack settings, reducing the attack efficacy of state-of-the-art adversarial suffix generation methods to below 4%, while only minimally affecting the target model's capabilities in non-adversarial scenarios.

[Arxiv](https://arxiv.org/abs/2505.09602)