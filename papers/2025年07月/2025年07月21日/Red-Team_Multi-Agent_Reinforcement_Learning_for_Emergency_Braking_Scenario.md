# 红队多智能体强化学习在紧急刹车场景中的应用

发布时间：2025年07月21日

`Agent` `自动驾驶` `人工智能`

> Red-Team Multi-Agent Reinforcement Learning for Emergency Braking Scenario

# 摘要

> 目前，安全关键场景中的决策研究常依赖低效的数据驱动场景生成或特定建模方法，这些方法难以捕捉现实环境中的边缘案例。为解决这一问题，我们提出了一种Red-Team多智能体强化学习框架，将具有干扰能力的背景车辆视为Red-Team智能体。通过主动干扰和探索，Red-Team车辆能够发现数据分布之外的边缘案例。该框架采用带有约束图表示的马尔可夫决策过程，确保Red-Team车辆在持续干扰自动驾驶汽车（AVs）的同时遵守安全规则。我们构建了一个策略威胁区模型，量化Red-Team车辆对AVs的威胁程度，从而诱发更极端的行为以提高场景的危险级别。实验结果表明，该框架显著影响了AVs的决策安全，并生成了多种边缘案例。这一方法为安全关键场景的研究提供了全新的研究方向。


> Current research on decision-making in safety-critical scenarios often relies on inefficient data-driven scenario generation or specific modeling approaches, which fail to capture corner cases in real-world contexts. To address this issue, we propose a Red-Team Multi-Agent Reinforcement Learning framework, where background vehicles with interference capabilities are treated as red-team agents. Through active interference and exploration, red-team vehicles can uncover corner cases outside the data distribution. The framework uses a Constraint Graph Representation Markov Decision Process, ensuring that red-team vehicles comply with safety rules while continuously disrupting the autonomous vehicles (AVs). A policy threat zone model is constructed to quantify the threat posed by red-team vehicles to AVs, inducing more extreme actions to increase the danger level of the scenario. Experimental results show that the proposed framework significantly impacts AVs decision-making safety and generates various corner cases. This method also offers a novel direction for research in safety-critical scenarios.

[Arxiv](https://arxiv.org/abs/2507.15587)