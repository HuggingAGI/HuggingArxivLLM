# 多智能体 KTO：增强 LLM 在语言游戏中的战略互动

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了如何通过多代理系统（MaKTO）在复杂的社交推理游戏（如《狼人杀》）中实现战略决策和自然语言生成。论文的核心是开发了一个多代理系统，并通过优化模型的决策过程来提高其在游戏中的表现。这涉及到多个代理之间的互动和协作，符合“Agent”分类的定义，即研究多代理系统的行为和决策过程。` `人工智能` `社交推理`

> Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game

# 摘要

> 实现人工通用智能（AGI）需要AI代理既能做出战略决策，又能进行灵活且有意义的交流。受维特根斯坦《哲学研究》中语言游戏理论的启发，我们提出语言代理可以通过上下文互动学习，而非传统的将决策与语言表达分离的多阶段框架。我们利用《狼人杀》这一测试语言理解、战略互动和适应性的社交推理游戏，开发了多代理卡尼曼与特沃斯基优化（MaKTO）。MaKTO通过让多种模型在广泛的游戏中进行互动，生成未配对的理想和不可接受的响应，并利用KTO优化模型的决策过程。在9人狼人杀游戏中，MaKTO在各种模型中实现了61%的平均胜率，分别比GPT-4o和两阶段强化学习代理高出23.0%和10.9%。值得注意的是，MaKTO还表现出类人性能，在与专家玩家的对抗中赢得了60%的胜利，并在图灵式盲测中仅显示出49%的可检测性。这些结果展示了MaKTO在复杂社交推理游戏中的卓越决策、战略适应和自然语言生成能力。

> Achieving Artificial General Intelligence (AGI) requires AI agents that can not only make stratigic decisions but also engage in flexible and meaningful communication. Inspired by Wittgenstein's language game theory in Philosophical Investigations, we propose that language agents can learn through in-context interaction rather than traditional multi-stage frameworks that separate decision-making from language expression. Using Werewolf, a social deduction game that tests language understanding, strategic interaction, and adaptability, we develop the Multi-agent Kahneman & Tversky's Optimization (MaKTO). MaKTO engages diverse models in extensive gameplay to generate unpaired desirable and unacceptable responses, then employs KTO to refine the model's decision-making process. In 9-player Werewolf games, MaKTO achieves a 61% average win rate across various models, outperforming GPT-4o and two-stage RL agents by relative improvements of 23.0% and 10.9%, respectively. Notably, MaKTO also demonstrates human-like performance, winning 60% against expert players and showing only 49% detectability in Turing-style blind tests. These results showcase MaKTO's superior decision-making, strategic adaptation, and natural language generation in complex social deduction games.

[Arxiv](https://arxiv.org/abs/2501.14225)