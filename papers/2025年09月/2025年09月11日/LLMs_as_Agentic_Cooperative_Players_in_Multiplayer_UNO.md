# LLMs：多人UNO中的智能体协作玩家

发布时间：2025年09月11日

`Agent` `媒体与娱乐`

> LLMs as Agentic Cooperative Players in Multiplayer UNO

# 摘要

> 大型语言模型（LLMs）不仅能答疑解惑，更有望在各类任务中为人类提供实用指导。但这种辅助能力究竟有多强？基于大语言模型的智能体真能以积极参与者的身份，助力他人达成目标吗？为找到答案，我们让LLM参与回合制卡牌游戏UNO，任务不是让它自己赢，而是协助另一名玩家获胜。我们开发了专用工具，使仅解码器LLM能以智能体身份接入RLCard游戏环境，这些模型会获取完整的游戏状态信息，并在两种不同提示策略下通过简单文本指令做出响应。我们测试了从10亿参数小模型到700亿参数大模型，探究模型规模对性能的影响。结果显示：所有模型玩UNO时都能轻松超越随机基线，但几乎没有模型能真正显著助力队友。

> LLMs promise to assist humans -- not just by answering questions, but by offering useful guidance across a wide range of tasks. But how far does that assistance go? Can a large language model based agent actually help someone accomplish their goal as an active participant? We test this question by engaging an LLM in UNO, a turn-based card game, asking it not to win but instead help another player to do so. We built a tool that allows decoder-only LLMs to participate as agents within the RLCard game environment. These models receive full game-state information and respond using simple text prompts under two distinct prompting strategies. We evaluate models ranging from small (1B parameters) to large (70B parameters) and explore how model scale impacts performance. We find that while all models were able to successfully outperform a random baseline when playing UNO, few were able to significantly aid another player.

[Arxiv](https://arxiv.org/abs/2509.09867)