# # 多模态不确定性下的自动驾驶集成决策与轨迹规划：贝叶斯博弈方法
自动驾驶在多模态不确定性下的集成决策与轨迹规划是一个复杂挑战。本文提出了一种基于贝叶斯博弈的创新方法来解决这一难题。

发布时间：2024年09月20日

`Agent

理由：这篇论文主要讨论的是自动驾驶中的交互建模和决策规划问题，涉及到多模态和行为不确定性。提出的框架基于贝叶斯博弈和无遗憾学习，旨在捕捉交通参与者之间的交互并生成最优策略。这些内容与智能体（Agent）的设计和决策过程密切相关，因此将其分类为Agent。` `自动驾驶` `交通规划`

> Integrated Decision Making and Trajectory Planning for Autonomous Driving Under Multimodal Uncertainties: A Bayesian Game Approach

# 摘要

> # 摘要
在自动驾驶中，交通参与者之间的交互建模是设计安全且非保守操作的核心问题。当涉及多模态和行为不确定性时，这一挑战尤为显著。现有方法要么缺乏交互式规划能力，要么局限于单模态行为，可能导致严重后果。本文提出了一种基于贝叶斯博弈（即不完全信息博弈）的集成决策与轨迹规划框架。人类决策具有离散特性，因此在博弈中被建模为玩家类型。我们引入了一种基于无遗憾学习的通用求解器，以获取贝叶斯粗相关均衡，从而捕捉多模态背景下交通参与者之间的交互。通过这一均衡，决策与轨迹规划得以同步进行，且所得到的交互策略在对手驾驶意图的期望下被证明是最优的。我们在多种交通场景下进行了闭环仿真，验证了该框架的通用性和有效性。

> Modeling the interaction between traffic agents is a key issue in designing safe and non-conservative maneuvers in autonomous driving. This problem can be challenging when multi-modality and behavioral uncertainties are engaged. Existing methods either fail to plan interactively or consider unimodal behaviors that could lead to catastrophic results. In this paper, we introduce an integrated decision-making and trajectory planning framework based on Bayesian game (i.e., game of incomplete information). Human decisions inherently exhibit discrete characteristics and therefore are modeled as types of players in the game. A general solver based on no-regret learning is introduced to obtain a corresponding Bayesian Coarse Correlated Equilibrium, which captures the interaction between traffic agents in the multimodal context. With the attained equilibrium, decision-making and trajectory planning are performed simultaneously, and the resulting interactive strategy is shown to be optimal over the expectation of rivals' driving intentions. Closed-loop simulations on different traffic scenarios are performed to illustrate the generalizability and the effectiveness of the proposed framework.

[Arxiv](https://arxiv.org/abs/2409.13993)