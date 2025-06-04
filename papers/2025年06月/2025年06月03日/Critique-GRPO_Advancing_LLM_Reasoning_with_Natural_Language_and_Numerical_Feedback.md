# Critique-GRPO：以自然语言与数值反馈推进LLM推理能力

发布时间：2025年06月03日

`LLM应用

摘要讨论了强化学习在大型语言模型中的应用，特别是结合自然语言反馈来提升模型性能，属于应用层面的研究。` `人工智能`

> Critique-GRPO: Advancing LLM Reasoning with Natural Language and Numerical Feedback

# 摘要

> 基于数值反馈（如标量奖励）的强化学习（RL）近期取得了显著进展，极大提升了大型语言模型（LLMs）的复杂推理能力。尽管如此，仅基于数值反馈的强化学习仍面临三个关键挑战：性能瓶颈、自我反思效果有限以及持续性失败问题。我们发现，即使强化学习微调模型已达到性能瓶颈，仍能通过借助以批评形式呈现的自然语言反馈，生成对持续性失败问题的正确改进。基于这一发现，我们提出了一种结合自然语言和数值反馈的在线强化学习框架——Critique-GRPO，以实现有效的策略优化。Critique-GRPO使LLMs能够在保持探索能力的同时，从初始响应和基于批评的改进中学习。使用Qwen2.5-7B-Base和Qwen3-8B-Base进行的大量实验表明，相比基于监督学习和基于强化学习的微调方法，Critique-GRPO在八个具有挑战性的数学、STEM和通用推理任务中表现更优，平均通过率@1分别提高了约4.5%和5%。值得注意的是，Critique-GRPO超越了一个在在线RL中整合专家演示的强大基线模型。进一步分析揭示了关于策略探索的两个关键见解：（1）更高的熵并不总是保证从探索中高效学习，（2）更长的响应并不必然导致更有效的探索。

> Recent advances in reinforcement learning (RL) with numerical feedback, such as scalar rewards, have significantly enhanced the complex reasoning capabilities of large language models (LLMs). Despite this success, we identify three key challenges encountered by RL with solely numerical feedback: performance plateaus, limited effectiveness of self-reflection, and persistent failures. We then demonstrate that RL-finetuned models, even after exhibiting performance plateaus, can generate correct refinements on persistently failed problems by leveraging natural language feedback in the form of critiques. Building on this insight, we propose Critique-GRPO, an online RL framework that integrates both natural language and numerical feedback for effective policy optimization. Critique-GRPO enables LLMs to learn from initial responses and critique-guided refinements simultaneously while maintaining exploration. Extensive experiments using Qwen2.5-7B-Base and Qwen3-8B-Base show that Critique-GRPO consistently outperforms supervised learning-based and RL-based fine-tuning approaches across eight challenging mathematical, STEM, and general reasoning tasks, improving average pass@1 scores by approximately 4.5% and 5%, respectively. Notably, Critique-GRPO surpasses a strong baseline that incorporates expert demonstrations within online RL. Further analysis reveals two critical insights about policy exploration: (1) higher entropy does not always guarantee efficient learning from exploration, and (2) longer responses do not necessarily lead to more effective exploration.

[Arxiv](https://arxiv.org/abs/2506.03106)