# # 探索性研究：基于 LLM 的复杂推理任务——以费米问题为例
大型语言模型 (LLM) 在复杂推理任务中的表现：以费米问题为例的探索性研究

发布时间：2025年04月03日

`LLM应用` `数学推理` `问题解决`

> LLM for Complex Reasoning Task: An Exploratory Study in Fermi Problems

# 摘要

> 费米问题（FPs）是一类需要人类逻辑与数值推理能力的数学推理任务。与其它推理问题不同，FPs常常涉及现实世界中的不合理性或模糊概念，这让它们即使对人类来说也充满挑战。尽管AI，特别是大型语言模型（LLMs），在多种推理任务中取得了进展，但FPs领域仍然相对未被探索。本研究旨在探索LLMs在解决FPs方面的能力与局限性。我们首先使用公开的FP数据集评估了三个先进LLMs的整体表现。根据最近提出的TELeR分类法，我们设计了包括零样本场景在内的提示。结果显示，所有模型的fp_score（范围在0-1之间）均低于0.5，凸显了这些推理任务的难度。为了进一步研究，我们将FPs分为标准与特定问题，假设LLMs在标准问题上表现更佳，因其以清晰简洁为特点。实验结果证实了这一假设：LLMs在标准FPs上无论是在准确率还是效率上都表现更优。

> Fermi Problems (FPs) are mathematical reasoning tasks that require human-like logic and numerical reasoning. Unlike other reasoning questions, FPs often involve real-world impracticalities or ambiguous concepts, making them challenging even for humans to solve. Despite advancements in AI, particularly with large language models (LLMs) in various reasoning tasks, FPs remain relatively under-explored. This work conducted an exploratory study to examine the capabilities and limitations of LLMs in solving FPs. We first evaluated the overall performance of three advanced LLMs using a publicly available FP dataset. We designed prompts according to the recently proposed TELeR taxonomy, including a zero-shot scenario. Results indicated that all three LLMs achieved a fp_score (range between 0 - 1) below 0.5, underscoring the inherent difficulty of these reasoning tasks. To further investigate, we categorized FPs into standard and specific questions, hypothesizing that LLMs would perform better on standard questions, which are characterized by clarity and conciseness, than on specific ones. Comparative experiments confirmed this hypothesis, demonstrating that LLMs performed better on standard FPs in terms of both accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2504.02671)