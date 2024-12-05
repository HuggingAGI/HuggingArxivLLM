# 由 AI 驱动的日常路线抉择

发布时间：2024年12月04日

`Agent`

> AI-Driven Day-to-Day Route Choice

# 摘要

> 理解旅行者的路线选择有助于政策制定者为正常及异常状况制定最优的运营和规划策略。然而，现有的选择建模方法通常依赖预先设定的假设，难以捕捉旅行行为的动态及适应性本质。近来，大型语言模型（LLMs）已成为颇具前景的替代之选，在众多领域展现出了复刻类人行为的卓越能力。尽管潜力巨大，但它们在交通场景中精准模拟人类路线选择行为的能力仍存疑。为解此惑，本文引入由LLM驱动的代理“LLMTraveler”，对LLMs在路线选择建模方面的潜力展开研究。该代理以LLM为核心，配备能从过往经验中学习的记忆系统，通过平衡所检索的数据与个性特征来做决策。研究通过两个阶段系统评估了LLMTraveler复刻类人决策的能力：（1）分析其在单一起讫点（OD）对拥堵游戏场景中的路线切换行为，其展现出与实验室数据相符的模式，但传统模型无法全然解释；（2）在Ortuzar和Willumsen（OW）网络上测试其对日常（DTD）自适应学习行为的建模能力，所得结果与多项Logit（MNL）和强化学习（RL）模型相当。这些实验表明，该框架能够部分复刻路线选择中的类人决策，同时为其决策提供自然语言解释。此能力为交通政策制定提供了宝贵的见解，比如模拟旅行者对新政策或网络变化的反应。

> Understanding travelers' route choices can help policymakers devise optimal operational and planning strategies for both normal and abnormal circumstances. However, existing choice modeling methods often rely on predefined assumptions and struggle to capture the dynamic and adaptive nature of travel behavior. Recently, Large Language Models (LLMs) have emerged as a promising alternative, demonstrating remarkable ability to replicate human-like behaviors across various fields. Despite this potential, their capacity to accurately simulate human route choice behavior in transportation contexts remains doubtful. To satisfy this curiosity, this paper investigates the potential of LLMs for route choice modeling by introducing an LLM-empowered agent, "LLMTraveler." This agent integrates an LLM as its core, equipped with a memory system that learns from past experiences and makes decisions by balancing retrieved data and personality traits. The study systematically evaluates the LLMTraveler's ability to replicate human-like decision-making through two stages: (1) analyzing its route-switching behavior in single origin-destination (OD) pair congestion game scenarios, where it demonstrates patterns align with laboratory data but are not fully explained by traditional models, and (2) testing its capacity to model day-to-day (DTD) adaptive learning behaviors on the Ortuzar and Willumsen (OW) network, producing results comparable to Multinomial Logit (MNL) and Reinforcement Learning (RL) models. These experiments demonstrate that the framework can partially replicate human-like decision-making in route choice while providing natural language explanations for its decisions. This capability offers valuable insights for transportation policymaking, such as simulating traveler responses to new policies or changes in the network.

[Arxiv](https://arxiv.org/abs/2412.03338)