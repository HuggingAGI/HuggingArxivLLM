# 当风格威胁安全：如何保护语言模型抵御表面化的风格对齐

发布时间：2025年06月09日

`LLM应用` `人工智能安全` `模型安全`

> When Style Breaks Safety: Defending Language Models Against Superficial Style Alignment

# 摘要

> 大型语言模型（LLMs）可以通过特定的风格（例如，将响应格式化为列表）进行提示，包括在越狱查询中。尽管这些风格模式在语义上与越狱查询背后的恶意意图无关，但它们的安全影响仍然不明朗。本研究旨在理解风格模式是否会损害LLM的安全性，表面风格对齐如何增加模型的脆弱性，以及如何在对齐过程中最好地缓解这些风险。我们评估了32个LLMs在七个越狱基准上的表现，并发现具有风格模式的恶意查询显著提升了几乎所有模型的攻击成功率（ASR）。值得注意的是，ASR的提升与风格模式的长度以及LLM对它们表现出的相对注意力相关。随后，我们研究了表面风格对齐，发现通过特定风格进行微调使LLMs更容易受到相同风格的越狱攻击。最后，我们提出了SafeStyle，这是一种防御策略，通过少量增强的安全训练数据来匹配微调数据中风格模式的分布。在三个LLMs和五种微调风格设置下，SafeStyle在保持LLM安全性方面始终优于基线方法。

> Large language models (LLMs) can be prompted with specific styles (e.g., formatting responses as lists), including in jailbreak queries. Although these style patterns are semantically unrelated to the malicious intents behind jailbreak queries, their safety impact remains unclear. In this work, we seek to understand whether style patterns compromise LLM safety, how superficial style alignment increases model vulnerability, and how best to mitigate these risks during alignment. We evaluate 32 LLMs across seven jailbreak benchmarks, and find that malicious queries with style patterns inflate the attack success rate (ASR) for nearly all models. Notably, ASR inflation correlates with both the length of style patterns and the relative attention an LLM exhibits on them. We then investigate superficial style alignment, and find that fine-tuning with specific styles makes LLMs more vulnerable to jailbreaks of those same styles. Finally, we propose SafeStyle, a defense strategy that incorporates a small amount of safety training data augmented to match the distribution of style patterns in the fine-tuning data. Across three LLMs and five fine-tuning style settings, SafeStyle consistently outperforms baselines in maintaining LLM safety.

[Arxiv](https://arxiv.org/abs/2506.07452)