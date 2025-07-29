# JT-Math：面向大型语言模型的高级数学推理多阶段框架

发布时间：2025年07月25日

`LLM应用` `数学推理`

> JT-Math: A Multi-Stage Framework for Advanced Mathematical Reasoning in Large Language Models

# 摘要

> 数学推理是人工通用智能的基石，也是评估大型语言模型（LLMs）能力的重要基准。尽管当前最先进的模型展现出巨大潜力，但面对需要深刻概念理解以及复杂、多步骤推理的难题时，它们往往表现欠佳。为应对这一挑战，我们推出了JT-Math-8B，这是一系列开源模型，包含基础、指令和思考版本，构建于一个系统化、多阶段优化框架之上。我们的预训练语料库是一个高质量的、包含2100亿个token的数据集，通过专门的数据管道整理而成，该管道采用基于模型的验证方法以确保数据的质量和多样性。指令模型通过监督微调（SFT）和基于GRPO的强化学习（RL）方法优化，以提供直接、简洁的回答。思考模型则采用长链式推理（Long CoT）方法，结合SFT与一种创新的、多阶段RL课程，逐步增加任务难度和上下文长度至32K个token，以提升复杂问题解决能力。JT-Math-8B在开源模型中达到了与自身规模相当的最先进水平，超越了OpenAI的O1-mini和GPT-4o等知名模型，并在竞赛级别的数学任务中展现了卓越性能。

> Mathematical reasoning is a cornerstone of artificial general intelligence and a primary benchmark for evaluating the capabilities of Large Language Models (LLMs). While state-of-the-art models show promise, they often falter when faced with complex problems that demand deep conceptual understanding and intricate, multi-step deliberation. To address this challenge, we introduce JT-Math-8B, a series of open-source models comprising base, instruct, and thinking versions, built upon a systematic, multi-stage optimization framework. Our pre-training corpus is a high-quality, 210B-token dataset curated through a dedicated data pipeline that uses model-based validation to ensure quality and diversity. The Instruct Model is optimized for direct, concise answers through Supervised Fine-Tuning (SFT) and a GRPO-based reinforcement learning (RL) method. The Thinking Model is trained for complex problem-solving using a Long Chain-of-Thought (Long CoT) approach, combining SFT with a novel, multi-stage RL curriculum that progressively increases task difficulty and context length up to 32K tokens. JT-Math-8B achieves state-of-the-art results among open-source models of similar size, surpassing prominent models like OpenAI's O1-mini and GPT-4o , and demonstrating superior performance on competition-level mathematics.

[Arxiv](https://arxiv.org/abs/2507.19748)