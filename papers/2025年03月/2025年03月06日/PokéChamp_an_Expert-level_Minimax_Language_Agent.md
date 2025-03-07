# PokéChamp：专家级极小极大语言智能体

发布时间：2025年03月06日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在宝可梦对战中的具体应用，特别是通过将其与minimax算法结合，构建了一个高效的代理系统。论文详细描述了LLMs在动作采样、对手建模和价值函数估计中的应用，这些都是LLM在特定领域中的实际应用案例。虽然涉及到智能体的设计，但核心是展示LLM在博弈场景中的应用，因此归类为LLM应用。` `博弈论`

> PokéChamp: an Expert-level Minimax Language Agent

# 摘要

> 我们推出 PokéChamp——一个由大型语言模型（LLMs）驱动的 minimax 代理，专为宝可梦对战而生。基于通用的两人竞争性游戏框架，PokéChamp 借助 LLMs 的通用能力，显著提升了 minimax 树搜索的效率。具体而言，LLMs 在三个关键模块中发挥了重要作用：(1) 玩家动作采样，(2) 对手建模，以及 (3) 价值函数估计。这些改进使代理能够充分利用游戏历史和人类知识，有效缩小搜索空间并应对部分可观测性挑战。值得一提的是，我们的框架无需额外训练 LLM。

我们在流行的 Gen 9 OU 格式下对 PokéChamp 进行了全面评估。当搭载 GPT-4o 时，它在与现有最佳的 LLM 基础机器人对战中取得了 76% 的胜率，而在与最强的基于规则的机器人对战中胜率更是达到了 84%，充分展现了其卓越的性能。即使使用开源的 80 亿参数 Llama 3.1 模型，PokéChamp 依然持续超越之前最佳的 LLM 基础机器人 Pokéllmon（由 GPT-4o 驱动），胜率达到了 64%。

在宝可梦 Showdown 在线天梯上，PokéChamp 的预计 Elo 分数为 1300-1500，使其跻身人类玩家中的前 30%-10%。此外，本研究还整理了目前最大的真实玩家宝可梦对战数据集，包含超过 300 万场比赛，其中包括超过 50 万场高 Elo 比赛。基于此数据集，我们建立了一系列战斗基准和难题，以评估特定的战斗技能。我们进一步对本地游戏引擎进行了关键更新。

我们希望这项工作能够推动进一步的研究，利用宝可梦对战作为基准，将 LLM 技术与博弈论算法相结合，以解决一般的多智能体问题。视频、代码和数据集可访问 https://sites.google.com/view/pokechamp-llm。


> We introduce PokéChamp, a minimax agent powered by Large Language Models (LLMs) for Pokémon battles. Built on a general framework for two-player competitive games, PokéChamp leverages the generalist capabilities of LLMs to enhance minimax tree search. Specifically, LLMs replace three key modules: (1) player action sampling, (2) opponent modeling, and (3) value function estimation, enabling the agent to effectively utilize gameplay history and human knowledge to reduce the search space and address partial observability. Notably, our framework requires no additional LLM training. We evaluate PokéChamp in the popular Gen 9 OU format. When powered by GPT-4o, it achieves a win rate of 76% against the best existing LLM-based bot and 84% against the strongest rule-based bot, demonstrating its superior performance. Even with an open-source 8-billion-parameter Llama 3.1 model, PokéChamp consistently outperforms the previous best LLM-based bot, Pokéllmon powered by GPT-4o, with a 64% win rate. PokéChamp attains a projected Elo of 1300-1500 on the Pokémon Showdown online ladder, placing it among the top 30%-10% of human players. In addition, this work compiles the largest real-player Pokémon battle dataset, featuring over 3 million games, including more than 500k high-Elo matches. Based on this dataset, we establish a series of battle benchmarks and puzzles to evaluate specific battling skills. We further provide key updates to the local game engine. We hope this work fosters further research that leverage Pokémon battle as benchmark to integrate LLM technologies with game-theoretic algorithms addressing general multiagent problems. Videos, code, and dataset available at https://sites.google.com/view/pokechamp-llm.

[Arxiv](https://arxiv.org/abs/2503.04094)