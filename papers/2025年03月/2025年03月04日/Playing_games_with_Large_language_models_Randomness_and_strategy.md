# 与大型语言模型一起玩游戏：随机性与策略

发布时间：2025年03月04日

`LLM应用` `人工智能`

> Playing games with Large language models: Randomness and strategy

# 摘要

> 玩游戏的历史可以追溯到用简化形式描述复杂互动的悠久历史。本文中，我们探讨大型语言模型（LLMs）是否能够玩游戏，通过同时进行和顺序进行的游戏互动来研究它们的随机化和战略适应能力。我们聚焦于GPT-4o-Mini-2024-08-17，测试了两个LLMs之间的游戏：石头剪刀布（RPS）和策略游戏（囚徒困境 PD）。人们常说大型语言模型是随机鹦鹉，虽然它们可能确实是鹦鹉，但我们的研究结果表明，它们在随机性方面并不那么随机，因为当被提示生成随机输出时，它们的结果往往带有明显偏见。我们的研究表明，LLMs似乎在重复游戏中发展出了损失厌恶策略，RPS逐渐陷入僵局，而PD则根据提示设计在合作与竞争结果之间系统性地转变。我们详细介绍了用于独立智能体互动的程序化工具以及在实现过程中面临的智能体AI挑战。我们证明，大型语言模型确实可以玩游戏，只是表现得还不够理想。这些研究成果对多智能体LLM系统的应用具有重要意义，并揭示了当前模型在战略决策输出方面的一些局限性。

> Playing games has a long history of describing intricate interactions in simplified forms. In this paper we explore if large language models (LLMs) can play games, investigating their capabilities for randomisation and strategic adaptation through both simultaneous and sequential game interactions. We focus on GPT-4o-Mini-2024-08-17 and test two games between LLMs: Rock Paper Scissors (RPS) and games of strategy (Prisoners Dilemma PD). LLMs are often described as stochastic parrots, and while they may indeed be parrots, our results suggest that they are not very stochastic in the sense that their outputs - when prompted to be random - are often very biased. Our research reveals that LLMs appear to develop loss aversion strategies in repeated games, with RPS converging to stalemate conditions while PD shows systematic shifts between cooperative and competitive outcomes based on prompt design. We detail programmatic tools for independent agent interactions and the Agentic AI challenges faced in implementation. We show that LLMs can indeed play games, just not very well. These results have implications for the use of LLMs in multi-agent LLM systems and showcase limitations in current approaches to model output for strategic decision-making.

[Arxiv](https://arxiv.org/abs/2503.02582)