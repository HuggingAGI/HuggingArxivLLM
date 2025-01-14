# DVM: 社交推理游戏中可控的LLM智能体探索

发布时间：2025年01月11日

`Agent

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来提升社交推理游戏（SDGs）中游戏代理的能力，并提出了一个名为DVM的框架来开发可控的LLM代理。论文的核心内容集中在如何通过LLM技术来增强游戏代理的智能和策略化，使其能够更好地适应游戏中的不同难度，并确保其安全性和公平性。因此，这篇论文应归类为Agent。` `人工智能`

> DVM: Towards Controllable LLM Agents in Social Deduction Games

# 摘要

> 大型语言模型（LLMs）显著提升了社交推理游戏（SDGs）中游戏代理的能力。这些游戏高度依赖对话驱动的互动，要求代理能够基于信息进行推理、决策和表达。尽管这一进展使得SDGs中的非玩家角色（NPCs）更加智能和策略化，但控制这些代理的熟练度仍然至关重要。这种控制不仅确保NPCs能够适应游戏中的不同难度，还为LLM代理的安全性和公平性提供了重要见解。本文提出了DVM框架，用于开发可控的LLM代理，并在热门SDG《狼人杀》中展示了其应用。DVM由预测器、决策器和讨论器三大组件构成，结合强化学习与胜率约束的决策链奖励机制，使代理能够动态调整游戏表现，达到指定胜率。实验表明，DVM不仅在《狼人杀》中表现优异，还能灵活调节其表现以满足预设胜率目标。这些成果为LLM代理在SDGs中的自适应与平衡玩法奠定了基础，为可控游戏代理的研究开辟了新方向。

> Large Language Models (LLMs) have advanced the capability of game agents in social deduction games (SDGs). These games rely heavily on conversation-driven interactions and require agents to infer, make decisions, and express based on such information. While this progress leads to more sophisticated and strategic non-player characters (NPCs) in SDGs, there exists a need to control the proficiency of these agents. This control not only ensures that NPCs can adapt to varying difficulty levels during gameplay, but also provides insights into the safety and fairness of LLM agents. In this paper, we present DVM, a novel framework for developing controllable LLM agents for SDGs, and demonstrate its implementation on one of the most popular SDGs, Werewolf. DVM comprises three main components: Predictor, Decider, and Discussor. By integrating reinforcement learning with a win rate-constrained decision chain reward mechanism, we enable agents to dynamically adjust their gameplay proficiency to achieve specified win rates. Experiments show that DVM not only outperforms existing methods in the Werewolf game, but also successfully modulates its performance levels to meet predefined win rate targets. These results pave the way for LLM agents' adaptive and balanced gameplay in SDGs, opening new avenues for research in controllable game agents.

[Arxiv](https://arxiv.org/abs/2501.06695)