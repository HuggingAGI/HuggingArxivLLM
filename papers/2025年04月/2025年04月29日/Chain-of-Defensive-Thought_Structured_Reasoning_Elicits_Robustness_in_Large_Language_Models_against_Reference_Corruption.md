# 防御性思维链：结构化推理提升大型语言模型对抗参考腐败的鲁棒性

发布时间：2025年04月29日

`LLM应用` `人工智能`

> Chain-of-Defensive-Thought: Structured Reasoning Elicits Robustness in Large Language Models against Reference Corruption

# 摘要

> 链式思维提示显著提升了大型语言模型的推理能力。本研究探索了如何利用这一能力增强模型在非推理任务中的稳健性。通过一种名为防御性思维链的简单方法，我们发现各类大型语言模型在应对参考数据污染时展现出显著增强的稳健性。该方法只需提供少量具有结构化防御性推理的示例。实验结果令人瞩目，尤其是考虑到方法的简洁性和广泛适用性。例如，在自然问题任务中，当10个参考数据中有1个被提示注入攻击污染时，采用标准提示的GPT-4o准确率从60%骤降至3%。而采用防御性思维链提示的GPT-4o则保持了50%的准确率。

> Chain-of-thought prompting has demonstrated great success in facilitating the reasoning abilities of large language models. In this work, we explore how these enhanced reasoning abilities can be exploited to improve the robustness of large language models in tasks that are not necessarily reasoning-focused. In particular, we show how a wide range of large language models exhibit significantly improved robustness against reference corruption using a simple method called chain-of-defensive-thought, where only a few exemplars with structured and defensive reasoning are provided as demonstrations. Empirically, the improvements can be astounding, especially given the simplicity and applicability of the method. For example, in the Natural Questions task, the accuracy of GPT-4o degrades from 60% to as low as 3% with standard prompting when 1 out of 10 references provided is corrupted with prompt injection attacks. In contrast, GPT-4o using chain-of-defensive-thought prompting maintains an accuracy of 50%.

[Arxiv](https://arxiv.org/abs/2504.20769)