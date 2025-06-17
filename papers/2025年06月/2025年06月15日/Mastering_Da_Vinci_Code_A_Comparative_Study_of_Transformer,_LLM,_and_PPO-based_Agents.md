# 掌握达芬奇密码：比较Transformer、LLM与PPO代理的性能研究。

发布时间：2025年06月15日

`Agent` `游戏AI` `人工智能`

> Mastering Da Vinci Code: A Comparative Study of Transformer, LLM, and PPO-based Agents

# 摘要

> 《达芬奇密码》是一款结合逻辑推理与不完美信息的独特游戏，对人工智能提出了超越简单模式识别的复杂推理要求。本文深入探讨了不同AI范式在掌握这款游戏中的表现。我们开发并评估了三种创新的智能体架构：基于Transformer的基准模型，具有有限历史上下文；由结构化提示驱动的大型语言模型（LLM）代理（包括Gemini、DeepSeek和GPT变体）；以及采用Transformer编码器处理完整游戏历史的近端策略优化（PPO）智能体。通过与基准模型的对比测试，基于PPO的智能体以高达（$58.5\% \pm 1.0\%$）的胜率脱颖而出，显著超越了LLM代理的表现。我们的研究表明，深度强化学习在复杂推理任务中的策略优化具有显著优势，尤其在通过自我博弈学习隐性策略方面表现突出。此外，我们还分析了当前LLM在长期游戏中，尽管采用了复杂提示，但在保持逻辑一致性和战略深度方面的能力与局限性。这项研究不仅深化了我们对涉及隐藏信息和多步逻辑推理的休闲游戏中人工智能的理解，还为有效智能体设计提供了宝贵的见解，并揭示了不同AI方法的独特优势。

> The Da Vinci Code, a game of logical deduction and imperfect information, presents unique challenges for artificial intelligence, demanding nuanced reasoning beyond simple pattern recognition. This paper investigates the efficacy of various AI paradigms in mastering this game. We develop and evaluate three distinct agent architectures: a Transformer-based baseline model with limited historical context, several Large Language Model (LLM) agents (including Gemini, DeepSeek, and GPT variants) guided by structured prompts, and an agent based on Proximal Policy Optimization (PPO) employing a Transformer encoder for comprehensive game history processing. Performance is benchmarked against the baseline, with the PPO-based agent demonstrating superior win rates ($58.5\% \pm 1.0\%$), significantly outperforming the LLM counterparts. Our analysis highlights the strengths of deep reinforcement learning in policy refinement for complex deductive tasks, particularly in learning implicit strategies from self-play. We also examine the capabilities and inherent limitations of current LLMs in maintaining strict logical consistency and strategic depth over extended gameplay, despite sophisticated prompting. This study contributes to the broader understanding of AI in recreational games involving hidden information and multi-step logical reasoning, offering insights into effective agent design and the comparative advantages of different AI approaches.

[Arxiv](https://arxiv.org/abs/2506.12801)