# MaestroMotif：基于人工智能反馈的技能设计

发布时间：2024年12月11日

`Agent` `人工智能`

> MaestroMotif: Skill Design from Artificial Intelligence Feedback

# 摘要

> 用自然语言描述技能，有望为将人类的决策知识注入人工智能系统提供一条可行途径。我们推出了 MaestroMotif 这一人工智能辅助的技能设计方法，它能造就高性能且适应性强的代理。MaestroMotif 借助大型语言模型（LLMs）的能力，有效创建和复用技能。它先是依据 LLM 的反馈，从技能的自然语言描述出发，自动设计出与之对应的奖励。接着，它运用 LLM 的代码生成能力，结合强化学习，对技能加以训练，并将它们组合起来，以实现语言所指定的复杂行为。我们在 NetHack 学习环境（NLE）中的一系列复杂任务中对 MaestroMotif 进行了评估，结果表明，它在性能和可用性上均超越了现有方法。

> Describing skills in natural language has the potential to provide an accessible way to inject human knowledge about decision-making into an AI system. We present MaestroMotif, a method for AI-assisted skill design, which yields high-performing and adaptable agents. MaestroMotif leverages the capabilities of Large Language Models (LLMs) to effectively create and reuse skills. It first uses an LLM's feedback to automatically design rewards corresponding to each skill, starting from their natural language description. Then, it employs an LLM's code generation abilities, together with reinforcement learning, for training the skills and combining them to implement complex behaviors specified in language. We evaluate MaestroMotif using a suite of complex tasks in the NetHack Learning Environment (NLE), demonstrating that it surpasses existing approaches in both performance and usability.

[Arxiv](https://arxiv.org/abs/2412.08542)