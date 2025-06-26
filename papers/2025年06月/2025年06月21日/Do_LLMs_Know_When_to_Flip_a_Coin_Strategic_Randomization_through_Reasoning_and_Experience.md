# 大型语言模型何时该随机选择？基于推理与经验的策略性随机化

发布时间：2025年06月21日

`LLM理论

摘要中讨论了大型语言模型（LLMs）在战略随机化方面的理论探索，特别是通过博弈论中的零和博弈和纳什均衡来分析模型的行为。研究的重点在于模型的内在机制和理论特性，而不是具体的应用场景或外部工具如RAG。因此，这篇论文应归类为LLM理论。` `人工智能` `博弈论`

> Do LLMs Know When to Flip a Coin? Strategic Randomization through Reasoning and Experience

# 摘要

> 战略随机化是博弈论中的关键原则，但在大型语言模型（LLMs）中仍未得到充分探索。以往研究常常混淆随机化的认知决策与随机性的机械生成，导致评估不完整。为解决这一问题，我们提出了一种受田忌赛马启发的零和博弈，其中纳什均衡对应于一种熵最大化策略。游戏的复杂性使得未受过训练的人类和欠发达的LLMs难以察觉这一特性。我们采用具有系统提供的随机选择的多轮竞技玩法，对五种LLMs进行了评估，涉及框架式、中立式和暗示式三种提示风格，从而将随机化决策与其他因素分离。结果显示，较弱的模型无论提示如何都保持确定性，而较强的模型在明确提示下表现出更多的随机化。当面对较弱模型时，强大的LLMs采用确定性策略来利用偏见，但在面对同级模型时则趋向于均衡玩法。通过胜负结果和贝叶斯因子分析，我们展示了LLMs在战略推理能力上的显著差异，突显了在抽象推理和自适应学习方面改进的机会。我们公开了我们的实现代码，确保完全可重复性。

> Strategic randomization is a key principle in game theory, yet it remains underexplored in large language models (LLMs). Prior work often conflates the cognitive decision to randomize with the mechanical generation of randomness, leading to incomplete evaluations. To address this, we propose a novel zero-sum game inspired by the Tian Ji Horse Race, where the Nash equilibrium corresponds to a maximal entropy strategy. The game's complexity masks this property from untrained humans and underdeveloped LLMs. We evaluate five LLMs across prompt styles -- framed, neutral, and hinted -- using competitive multi-tournament gameplay with system-provided random choices, isolating the decision to randomize. Results show that weaker models remain deterministic regardless of prompts, while stronger models exhibit increased randomization under explicit hints. When facing weaker models, strong LLMs adopt deterministic strategies to exploit biases, but converge toward equilibrium play when facing peers. Through win/loss outcomes and Bayes factor analysis, we demonstrate meaningful variation in LLMs' strategic reasoning capabilities, highlighting opportunities for improvement in abstract reasoning and adaptive learning. We make our implementation publicly available at https://github.com/ocelopus/llm-when-to-throw-coin to ensure full reproducibility.

[Arxiv](https://arxiv.org/abs/2506.18928)