# 什么对你来说是禁忌？——大型语言模型对敏感内容行为的实证评估

发布时间：2025年07月31日

`LLM应用` `内容安全`

> What's Taboo for You? - An Empirical Evaluation of LLMs Behavior Toward Sensitive Content

# 摘要

> 专有大型语言模型（LLMs）在生成内容时表现出礼貌、正式以及隐性内容 moderation 的倾向。虽然以往研究主要关注显式训练模型以处理敏感内容，但对 LLMs 是否能在无明确指令的情况下隐式净化语言的探索仍显不足。本研究通过实证分析了 GPT-4o-mini 在改写敏感内容时的隐性 moderation 行为，评估了其敏感度的变化程度。实验结果显示，GPT-4o-mini 系统性地将内容导向更不敏感的类别，显著减少了贬低性和禁忌语言的使用。此外，我们还评估了 LLMs 在零样本情况下对句子敏感度进行分类的能力，并将其性能与传统方法进行了对比。

> Proprietary Large Language Models (LLMs) have shown tendencies toward politeness, formality, and implicit content moderation. While previous research has primarily focused on explicitly training models to moderate and detoxify sensitive content, there has been limited exploration of whether LLMs implicitly sanitize language without explicit instructions. This study empirically analyzes the implicit moderation behavior of GPT-4o-mini when paraphrasing sensitive content and evaluates the extent of sensitivity shifts. Our experiments indicate that GPT-4o-mini systematically moderates content toward less sensitive classes, with substantial reductions in derogatory and taboo language. Also, we evaluate the zero-shot capabilities of LLMs in classifying sentence sensitivity, comparing their performances against traditional methods.

[Arxiv](https://arxiv.org/abs/2507.23319)