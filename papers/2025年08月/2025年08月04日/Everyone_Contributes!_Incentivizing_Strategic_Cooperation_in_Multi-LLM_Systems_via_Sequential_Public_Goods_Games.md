# 人人皆贡献！通过序贯公共品博弈激励多语言模型系统的战略协作

发布时间：2025年08月04日

`LLM应用

理由：这篇论文探讨了多个大型语言模型（LLMs）之间的协作机制，通过基于博弈论的强化学习框架来优化它们的合作行为，从而提升在多种任务上的性能。研究重点在于如何应用这些模型进行协作，因此归类为LLM应用。` `人工智能`

> Everyone Contributes! Incentivizing Strategic Cooperation in Multi-LLM Systems via Sequential Public Goods Games

# 摘要

> 协调多个大型语言模型（LLMs）协作解决复杂任务时，计算成本与整体性能之间存在基础性的权衡。我们提出了一种基于博弈论的强化学习新框架——多智能体合作序贯公共物品游戏（MAC-SPGG），以系统性地促进多LLM集合中的合作行为。在MAC-SPGG框架中，LLM智能体依次行动，通过观察前驱模型的输出并更新信念，从而动态调整自身的贡献。通过重新设计公共物品奖励机制，我们使努力贡献成为唯一的子博弈完美纳什均衡（SPNE），从而有效消除了传统SPGG或公共物品博弈中的搭便车现象。MAC-SPGG的序贯协议通过精简决策流程替代了传统的基于轮次的信息交换，显著降低了通信开销，同时保留了战略深度。我们证明了在现实参数下SPNE的存在性和唯一性，并通过实验证明，MAC-SPGG训练的集合模型在推理、数学、代码生成和NLP任务上均优于单智能体基线、链式思维提示以及其它合作方法，甚至达到了与大规模模型相当的性能水平。我们的研究结果凸显了结构化、激励对齐的MAC-SPGG合作在实现可扩展和稳健的多智能体语言生成中的强大潜力。

> Coordinating multiple large language models (LLMs) to solve complex tasks collaboratively poses a fundamental trade-off between the computation costs and collective performance compared with individual model. We introduce a novel, game-theoretically grounded reinforcement learning (RL) framework, the Multi-Agent Cooperation Sequential Public Goods Game (MAC-SPGG), to systematically incentivize cooperation in multi-LLM ensembles. In MAC-SPGG, LLM agents move in sequence, observing predecessors' outputs and updating beliefs to condition their own contributions. By redesigning the public-goods reward, effortful contributions become the unique Subgame Perfect Nash Equilibrium (SPNE), which eliminates free-riding under traditional SPGG or PGG. Its sequential protocol replaces costly round-based information exchanges with a streamlined decision flow, cutting communication overhead while retaining strategic depth. We prove the existence and uniqueness of the SPNE under realistic parameters, and empirically show that MAC-SPGG-trained ensembles outperform single-agent baselines, chain-of-thought prompting, and other cooperative methods, even achieving comparable performance to large-scale models across reasoning, math, code generation, and NLP tasks. Our results highlight the power of structured, incentive-aligned MAC-SPGG cooperation for scalable and robust multi-agent language generation.

[Arxiv](https://arxiv.org/abs/2508.02076)