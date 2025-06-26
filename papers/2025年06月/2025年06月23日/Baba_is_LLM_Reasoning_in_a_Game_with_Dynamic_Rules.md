# # Baba是LLM：动态规则游戏中的推理

发布时间：2025年06月23日

`LLM应用` `人工智能`

> Baba is LLM: Reasoning in a Game with Dynamic Rules

# 摘要

> 大型语言模型（LLMs）在语言任务上表现出色，但在推理任务上仍显不足。本文研究了LLMs在2D益智游戏《Baba is You》中的表现，玩家通过重新排列定义物体属性的文本块来操纵规则。这种规则操纵依赖于语言能力和推理，对LLMs来说是一个巨大挑战。我们采用三种提示类型（简单提示、规则扩展提示和动作扩展提示），对六种LLMs进行了评估。此外，我们使用游戏中的文本和结构化数据对两种模型（Mistral、OLMo）进行了微调。结果显示，较大的模型（尤其是GPT-4o）在推理和解谜方面表现更优，但未经调整的小型模型难以识别游戏机制或应用规则更改。微调提升了模型对游戏关卡的分析能力，但未能显著改善解决方案的制定。我们发现，即使是经过微调的先进LLMs，对动态规则变化的推理仍然困难（特别是理解使用-提及的区别）。这些结果揭示了LLMs在复杂问题解决中的适用性，并表明具有动态规则变化的游戏是测试LLMs推理和反思能力的理想选择。

> Large language models (LLMs) are known to perform well on language tasks, but struggle with reasoning tasks. This paper explores the ability of LLMs to play the 2D puzzle game Baba is You, in which players manipulate rules by rearranging text blocks that define object properties. Given that this rule-manipulation relies on language abilities and reasoning, it is a compelling challenge for LLMs. Six LLMs are evaluated using different prompt types, including (1) simple, (2) rule-extended and (3) action-extended prompts. In addition, two models (Mistral, OLMo) are finetuned using textual and structural data from the game. Results show that while larger models (particularly GPT-4o) perform better in reasoning and puzzle solving, smaller unadapted models struggle to recognize game mechanics or apply rule changes. Finetuning improves the ability to analyze the game levels, but does not significantly improve solution formulation. We conclude that even for state-of-the-art and finetuned LLMs, reasoning about dynamic rule changes is difficult (specifically, understanding the use-mention distinction). The results provide insights into the applicability of LLMs to complex problem-solving tasks and highlight the suitability of games with dynamically changing rules for testing reasoning and reflection by LLMs.

[Arxiv](https://arxiv.org/abs/2506.19095)