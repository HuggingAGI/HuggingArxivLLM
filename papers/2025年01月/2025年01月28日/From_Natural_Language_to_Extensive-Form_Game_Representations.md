# 从自然语言到扩展形式游戏的表示

发布时间：2025年01月28日

`LLM应用

**理由**：该论文提出了一种利用大型语言模型（LLMs）和上下文学习将自然语言中的游戏描述转化为博弈论中的扩展形式表示的框架。这属于LLM在实际问题中的应用，特别是通过LLM进行自然语言处理和生成特定领域的表示（如博弈论中的扩展形式游戏树）。因此，该论文应归类为LLM应用。` `博弈论` `游戏设计`

> From Natural Language to Extensive-Form Game Representations

# 摘要

> 我们提出了一种框架，利用大型语言模型（LLMs）和上下文学习，将自然语言中的游戏描述转化为博弈论中的扩展形式表示。由于游戏中的策略复杂性各异（如完全信息与不完全信息），直接应用上下文学习效果有限。为此，我们设计了一个两阶段框架，通过专用模块增强上下文学习，使其能够有效分解并解决问题。第一阶段，我们开发了一个模块来应对不完全信息的挑战，识别信息集及其对应的部分树结构。第二阶段，结合上下文学习和自我调试模块，生成完整的扩展形式游戏树，并使用pygambit（Gambit博弈论分析工具的Python API）进行表示。这种Python表示法使得直接从自然语言描述中自动化计算纳什均衡等任务成为可能。我们使用不同LLMs在不同策略复杂度的游戏上评估了框架及其组件的性能。实验结果表明，该框架在生成准确扩展形式游戏方面显著优于基线模型，每个模块都对其成功起到了关键作用。

> We introduce a framework for translating game descriptions in natural language into extensive-form representations in game theory, leveraging Large Language Models (LLMs) and in-context learning. Given the varying levels of strategic complexity in games, such as perfect versus imperfect information, directly applying in-context learning would be insufficient. To address this, we introduce a two-stage framework with specialized modules to enhance in-context learning, enabling it to divide and conquer the problem effectively. In the first stage, we tackle the challenge of imperfect information by developing a module that identifies information sets along and the corresponding partial tree structure. With this information, the second stage leverages in-context learning alongside a self-debugging module to produce a complete extensive-form game tree represented using pygambit, the Python API of a recognized game-theoretic analysis tool called Gambit. Using this python representation enables the automation of tasks such as computing Nash equilibria directly from natural language descriptions. We evaluate the performance of the full framework, as well as its individual components, using various LLMs on games with different levels of strategic complexity. Our experimental results show that the framework significantly outperforms baseline models in generating accurate extensive-form games, with each module playing a critical role in its success.

[Arxiv](https://arxiv.org/abs/2501.17282)