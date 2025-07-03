# 情感智能型任务导向对话系统：架构、表示及优化

发布时间：2025年07月02日

`LLM应用` `对话系统` `任务导向型对话`

> Emotionally Intelligent Task-oriented Dialogue Systems: Architecture, Representation, and Optimisation

# 摘要

> 任务导向型对话（ToD）系统通过自然语言交互帮助用户实现特定目标。尽管大型语言模型（LLMs）的最新进展显著提升了语言流畅度和上下文理解能力，但构建高效且情感智能的ToD系统仍是一项复杂挑战。有效的ToD系统必须在本质上嘈杂且模糊的对话环境中优化任务成功、情感理解和响应能力，以及信息传递的精准度。

本研究探讨了ToD系统在架构、表示、优化以及情感方面的考量。我们搭建了一个涵盖这些设计考量的系统，并采用了一个具有挑战性的评估环境，该环境由自然语言用户模拟器与不完美的自然语言理解模块组成。我们提出了	extbf{LUSTER}，一个基于	extbf{L}LM的	extbf{U}nified 	extbf{S}ystem，专为	extbf{T}ask-oriented对话设计，采用端到端的	extbf{R}einforcement learning，结合短期（用户情感）和长期（任务成功）奖励。我们的研究结果表明，将LLM能力与结构化奖励建模相结合，能够构建更具韧性和情感响应的ToD系统，为下一代对话代理提供了切实可行的发展方向。

> Task-oriented dialogue (ToD) systems are designed to help users achieve specific goals through natural language interaction. While recent advances in large language models (LLMs) have significantly improved linguistic fluency and contextual understanding, building effective and emotionally intelligent ToD systems remains a complex challenge. Effective ToD systems must optimise for task success, emotional understanding and responsiveness, and precise information conveyance, all within inherently noisy and ambiguous conversational environments. In this work, we investigate architectural, representational, optimisational as well as emotional considerations of ToD systems. We set up systems covering these design considerations with a challenging evaluation environment composed of a natural-language user simulator coupled with an imperfect natural language understanding module. We propose \textbf{LUSTER}, an \textbf{L}LM-based \textbf{U}nified \textbf{S}ystem for \textbf{T}ask-oriented dialogue with \textbf{E}nd-to-end \textbf{R}einforcement learning with both short-term (user sentiment) and long-term (task success) rewards. Our findings demonstrate that combining LLM capability with structured reward modelling leads to more resilient and emotionally responsive ToD systems, offering a practical path forward for next-generation conversational agents.

[Arxiv](https://arxiv.org/abs/2507.01594)