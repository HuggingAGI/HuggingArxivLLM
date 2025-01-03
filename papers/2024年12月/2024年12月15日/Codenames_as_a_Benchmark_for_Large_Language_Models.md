# Codenames：大型语言模型的基准测试

发布时间：2024年12月15日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来评估和改进在《Codenames》游戏中的表现。论文涉及对多个先进LLMs（如GPT-4o、Gemini 1.5等）的评估，并讨论了它们在游戏中的推理能力和行为模式。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `人工智能`

> Codenames as a Benchmark for Large Language Models

# 摘要

> 本文提出将流行的文字桌游《Codenames》作为评估大型语言模型（LLMs）推理能力的基准。该游戏对AI提出了极具挑战性的要求，包括对语言、心智理论和认知推理的深刻理解。以往开发《Codenames》代理的尝试多依赖词嵌入技术，但其词汇范围有限，且与其他方法结合时表现不佳。LLMs在语言任务中展现了强大的推理和理解能力，但在横向思维挑战中仍有不足。我们评估了GPT-4o、Gemini 1.5、Claude 3.5 Sonnet和Llama 3.1等先进LLMs在不同棋盘设置下的表现。结果显示，尽管某些LLMs整体表现更优，但不同模型在游戏过程中展现出不同的行为模式，并在特定角色中表现突出。我们还测试了LLMs组合在合作游戏中的表现，证明其比传统技术更能适应多样化的队友。

> In this paper, we propose the use of the popular word-based board game Codenames as a suitable benchmark for evaluating the reasoning capabilities of Large Language Models (LLMs). Codenames presents a highly interesting challenge for achieving successful AI performance, requiring both a sophisticated understanding of language, theory of mind, and epistemic reasoning capabilities. Prior attempts to develop agents for Codenames have largely relied on word embedding techniques, which have a limited vocabulary range and perform poorly when paired with differing approaches. LLMs have demonstrated enhanced reasoning and comprehension capabilities for language-based tasks, but can still suffer in lateral thinking challenges. We evaluate the capabilities of several state-of-the-art LLMs, including GPT-4o, Gemini 1.5, Claude 3.5 Sonnet, and Llama 3.1, across a variety of board setups. Our results indicate that while certain LLMs perform better than others overall, different models exhibit varying emergent behaviours during gameplay and excel at specific roles. We also evaluate the performance of different combinations of LLMs when playing cooperatively together, demonstrating that LLM agents are more generalisable to a wider range of teammates than prior techniques.

[Arxiv](https://arxiv.org/abs/2412.11373)