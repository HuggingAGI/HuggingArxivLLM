# 逻辑突破：利用形式逻辑高效解除LLM安全限制

发布时间：2025年05月18日

`LLM应用` `网络安全` `人工智能`

> Logic Jailbreak: Efficiently Unlocking LLM Safety Restrictions Through Formal Logical Expression

# 摘要

> 尽管在对齐大型语言模型 (LLMs) 与人类价值观方面取得了显著进展，现有的安全机制仍然容易受到越狱攻击的影响。我们假设这种漏洞源于以对齐为导向的提示与恶意提示之间的分布差异。为了研究这一问题，我们引入了LogiBreak，这是一种新颖且通用的黑盒越狱方法，它利用逻辑表达式翻译来绕过LLM的安全系统。通过将有害的自然语言提示转换为正式的逻辑表达式，LogiBreak利用了对齐数据与基于逻辑的输入之间的分布差距，在保持潜在语义意图和可读性的同时，规避了安全约束。我们在一个多语言越狱数据集上对LogiBreak进行了评估，该数据集涵盖三种语言，结果展示了其在各种评估设置和语言背景下的有效性。

> Despite substantial advancements in aligning large language models (LLMs) with human values, current safety mechanisms remain susceptible to jailbreak attacks. We hypothesize that this vulnerability stems from distributional discrepancies between alignment-oriented prompts and malicious prompts. To investigate this, we introduce LogiBreak, a novel and universal black-box jailbreak method that leverages logical expression translation to circumvent LLM safety systems. By converting harmful natural language prompts into formal logical expressions, LogiBreak exploits the distributional gap between alignment data and logic-based inputs, preserving the underlying semantic intent and readability while evading safety constraints. We evaluate LogiBreak on a multilingual jailbreak dataset spanning three languages, demonstrating its effectiveness across various evaluation settings and linguistic contexts.

[Arxiv](https://arxiv.org/abs/2505.13527)