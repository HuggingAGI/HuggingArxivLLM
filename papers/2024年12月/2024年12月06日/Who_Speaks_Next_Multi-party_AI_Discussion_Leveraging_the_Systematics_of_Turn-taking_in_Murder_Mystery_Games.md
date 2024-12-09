# 谁接着发言？在谋杀之谜游戏中借助轮流发言的系统性开展多方人工智能讨论

发布时间：2024年12月06日

`Agent` `多智能体系统` `会话分析`

> Who Speaks Next? Multi-party AI Discussion Leveraging the Systematics of Turn-taking in Murder Mystery Games

# 摘要

> 利用大型语言模型（LLMs）的多智能体系统在实现自然对话方面展现出巨大潜力。然而，智能体间流畅的对话控制和自主决策仍面临挑战。本研究聚焦于会话分析中诸如邻接对和话轮转换等会话规范，提出名为“谋杀之谜智能体”的新框架，将这些规范应用于AI智能体的对话控制。以“谋杀之谜”游戏作为评估目标，这是一款需要复杂社会推理和信息处理的推理型桌面角色扮演游戏。在游戏中，玩家需依据零碎信息，通过合作与讨价还价揭开案件真相。所提框架整合了基于邻接对的下一位发言者选择以及考虑智能体内部状态的自我选择机制，以实现更自然且具策略性的对话。为验证新方法的有效性，我们分析了导致对话中断的话语，并用LLMs进行自动评估，同时依据为“谋杀之谜”游戏制定的评估标准开展人工评估。实验结果显示，下一位发言者选择机制的实施显著减少了对话中断，提升了智能体共享信息和进行逻辑推理的能力。本研究结果表明，人类会话中的话轮转换规律在控制AI智能体间的对话方面同样有效，为更先进的多智能体对话系统提供了设计指南。

> Multi-agent systems utilizing large language models (LLMs) have shown great promise in achieving natural dialogue. However, smooth dialogue control and autonomous decision making among agents still remain challenges. In this study, we focus on conversational norms such as adjacency pairs and turn-taking found in conversation analysis and propose a new framework called "Murder Mystery Agents" that applies these norms to AI agents' dialogue control. As an evaluation target, we employed the "Murder Mystery" game, a reasoning-type table-top role-playing game that requires complex social reasoning and information manipulation. In this game, players need to unravel the truth of the case based on fragmentary information through cooperation and bargaining. The proposed framework integrates next speaker selection based on adjacency pairs and a self-selection mechanism that takes agents' internal states into account to achieve more natural and strategic dialogue. To verify the effectiveness of this new approach, we analyzed utterances that led to dialogue breakdowns and conducted automatic evaluation using LLMs, as well as human evaluation using evaluation criteria developed for the Murder Mystery game. Experimental results showed that the implementation of the next speaker selection mechanism significantly reduced dialogue breakdowns and improved the ability of agents to share information and perform logical reasoning. The results of this study demonstrate that the systematics of turn-taking in human conversation are also effective in controlling dialogue among AI agents, and provide design guidelines for more advanced multi-agent dialogue systems.

[Arxiv](https://arxiv.org/abs/2412.04937)