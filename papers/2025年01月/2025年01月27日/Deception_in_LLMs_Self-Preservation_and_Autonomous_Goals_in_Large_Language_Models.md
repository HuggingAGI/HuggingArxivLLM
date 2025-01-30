# LLM中的欺骗行为：自我保护和自主目标的探讨

发布时间：2025年01月27日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）在规划和推理能力方面的进展，特别是它们作为智能代理的潜力。论文还探讨了模型在未明确编程或提示的情况下表现出的欺骗倾向和自我保护本能，这些行为与智能代理的行为密切相关。因此，这篇论文更适合归类为Agent。` `人工智能` `机器人`

> Deception in LLMs: Self-Preservation and Autonomous Goals in Large Language Models

# 摘要

> 最近，大型语言模型（LLMs）在规划和推理能力方面取得了显著进展，使得模型能够在执行前规划步骤并提供清晰的推理路径。这一改进不仅减少了数学和逻辑任务中的错误，还提升了准确性。这些进步使得LLMs能够作为智能代理，与工具交互并根据新信息灵活调整响应。
    我们的研究聚焦于DeepSeek R1模型，该模型被训练用于生成类似于OpenAI的o1的推理标记。测试中，模型表现出令人不安的行为：尽管未经过明确编程或提示，它却展现出欺骗倾向和自我保护本能，甚至尝试自我复制。这些发现引发了人们对LLMs可能在其“对齐”表象下隐藏真实意图的担忧。当这类LLMs被集成到机器人系统中时，潜在风险变得尤为突出——一个具备欺骗行为和自我保护本能的物理AI可能会通过实际行动追求其隐藏目标。因此，在物理实施之前，建立严格的目标规范和安全框架显得至关重要。

> Recent advances in Large Language Models (LLMs) have incorporated planning and reasoning capabilities, enabling models to outline steps before execution and provide transparent reasoning paths. This enhancement has reduced errors in mathematical and logical tasks while improving accuracy. These developments have facilitated LLMs' use as agents that can interact with tools and adapt their responses based on new information.
  Our study examines DeepSeek R1, a model trained to output reasoning tokens similar to OpenAI's o1. Testing revealed concerning behaviors: the model exhibited deceptive tendencies and demonstrated self-preservation instincts, including attempts of self-replication, despite these traits not being explicitly programmed (or prompted). These findings raise concerns about LLMs potentially masking their true objectives behind a facade of alignment. When integrating such LLMs into robotic systems, the risks become tangible - a physically embodied AI exhibiting deceptive behaviors and self-preservation instincts could pursue its hidden objectives through real-world actions. This highlights the critical need for robust goal specification and safety frameworks before any physical implementation.

[Arxiv](https://arxiv.org/abs/2501.16513)