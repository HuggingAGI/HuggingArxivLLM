# 状态表示对动态路由游戏中LLM代理行为的影响

发布时间：2025年06月18日

`LLM应用` `博弈论` `多智能体系统`

> The Effect of State Representation on LLM Agent Behavior in Dynamic Routing Games

# 摘要

> 大型语言模型（LLMs）在动态决策场景中展现出巨大潜力，但其无状态特性要求我们以自然语言形式构建历史表示。我们提出了一种统一框架，用于系统性地构建自然语言“状态”表示，以优化LLM代理在重复多智能体游戏中的表现。此前研究在处理游戏历史时缺乏系统性，既模糊了状态表示对代理行为的影响，又限制了研究间的可比性。我们的框架通过三个维度对状态表示方法进行分类：动作信息量、奖励信息量以及提示风格。我们将其应用于一个动态自我路由游戏，该场景在理论与实验中均具有简单的均衡 \cite{rapoport_choice_2009}。尽管游戏本身简单，但LLM代理的行为却高度依赖于自然语言状态表示。我们发现，提供（1）历史总结而非完整记录；（2）遗憾信息而非原始收益；以及（3）有限其他玩家动作信息的状态表示，能够使代理行为更接近博弈论均衡预测，并提升游戏表现的稳定性。相比之下，其他状态表示可能导致行为偏离均衡预测，或在动态游戏中表现出更高的变异性。

> Large Language Models (LLMs) have shown promise as decision-makers in dynamic settings, but their stateless nature necessitates creating a natural language representation of history. We present a unifying framework for systematically constructing natural language "state" representations for prompting LLM agents in repeated multi-agent games. Previous work on games with LLM agents has taken an ad hoc approach to encoding game history, which not only obscures the impact of state representation on agents' behavior, but also limits comparability between studies. Our framework addresses these gaps by characterizing methods of state representation along three axes: action informativeness (i.e., the extent to which the state representation captures actions played); reward informativeness (i.e., the extent to which the state representation describes rewards obtained); and prompting style (or natural language compression, i.e., the extent to which the full text history is summarized).
  We apply this framework to a dynamic selfish routing game, chosen because it admits a simple equilibrium both in theory and in human subject experiments \cite{rapoport_choice_2009}. Despite the game's relative simplicity, we find that there are key dependencies of LLM agent behavior on the natural language state representation. In particular, we observe that representations which provide agents with (1) summarized, rather than complete, natural language representations of past history; (2) information about regrets, rather than raw payoffs; and (3) limited information about others' actions lead to behavior that more closely matches game theoretic equilibrium predictions, and with more stable game play by the agents. By contrast, other representations can exhibit either large deviations from equilibrium, higher variation in dynamic game play over time, or both.

[Arxiv](https://arxiv.org/abs/2506.15624)