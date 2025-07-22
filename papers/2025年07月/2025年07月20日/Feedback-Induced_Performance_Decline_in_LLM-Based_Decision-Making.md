# 基于反馈的LLM决策性能下降

发布时间：2025年07月20日

`LLM应用` `决策过程`

> Feedback-Induced Performance Decline in LLM-Based Decision-Making

# 摘要

> 大型语言模型（LLMs）从自然语言问题描述中提取上下文的能力，自然而然地引发了对其在自主决策环境中的适用性的疑问。本文研究了这些模型在马尔可夫决策过程（MDPs）中的行为。虽然传统强化学习（RL）策略依赖于迭代探索，但预训练于多样化数据集的LLMs能够利用先前知识实现更快的适应。我们研究了在序列决策任务中采用在线结构化提示策略，并比较了LLM方法的零-shot表现与经典RL方法的性能。研究发现，尽管LLMs在简单环境中表现出初始性能的提升，但若无微调或额外指导，它们在复杂场景中面临规划与推理的挑战。我们的结果表明，旨在提升决策能力的反馈机制，往往引入混淆，导致在复杂环境中表现下降。这些见解强调了进一步探索混合策略、微调与先进记忆整合的必要性，以提升LLM的决策能力。

> The ability of Large Language Models (LLMs) to extract context from natural language problem descriptions naturally raises questions about their suitability in autonomous decision-making settings. This paper studies the behaviour of these models within a Markov Decision Process (MDPs). While traditional reinforcement learning (RL) strategies commonly employed in this setting rely on iterative exploration, LLMs, pre-trained on diverse datasets, offer the capability to leverage prior knowledge for faster adaptation. We investigate online structured prompting strategies in sequential decision making tasks, comparing the zero-shot performance of LLM-based approaches to that of classical RL methods. Our findings reveal that although LLMs demonstrate improved initial performance in simpler environments, they struggle with planning and reasoning in complex scenarios without fine-tuning or additional guidance. Our results show that feedback mechanisms, intended to improve decision-making, often introduce confusion, leading to diminished performance in intricate environments. These insights underscore the need for further exploration into hybrid strategies, fine-tuning, and advanced memory integration to enhance LLM-based decision-making capabilities.

[Arxiv](https://arxiv.org/abs/2507.14906)