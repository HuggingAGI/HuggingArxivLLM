# 基于奖励引导的保守Q学习协调拼车与公共交通：离线训练与在线微调的强化学习框架

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了一种新型强化学习框架（RG-CQL），用于优化多模式交通网络中的拼车与公共交通协同效率。论文中将每辆拼车车辆视为由马尔可夫决策过程（MDP）控制的智能体，并通过离线训练与在线微调的RL框架来优化决策。这涉及到智能体的行为控制和决策优化，符合“Agent”分类的定义。`

> Coordinating Ride-Pooling with Public Transit using Reward-Guided Conservative Q-Learning: An Offline Training and Online Fine-Tuning Reinforcement Learning Framework

# 摘要

> 本文提出了一种名为奖励引导的保守Q学习（RG-CQL）的新型强化学习框架，旨在提升多模式交通网络中拼车与公共交通的协同效率。我们将每辆拼车车辆视为由马尔可夫决策过程（MDP）控制的智能体，并设计了一个离线训练与在线微调的RL框架，用于优化多模式交通系统的运营决策，包括乘客-车辆匹配、下车点选择及车辆路径规划，同时显著提升数据利用效率。在离线训练阶段，我们构建了保守双深度Q网络（CDDQN）作为动作执行器，并引入基于监督学习的奖励估计器——引导网络，从数据中挖掘动作与奖励的深层关联。在线微调阶段，引导网络充当探索向导，协助CDDQN高效且稳健地探索未知状态-动作空间。通过曼哈顿真实数据的案例研究，我们验证了算法的有效性：拼车与公共交通的整合在系统奖励上分别比单独乘车与公共交通协调及无公共交通协调的拼车高出17%和22%。此外，我们的离线训练与在线微调框架在数据效率上比传统在线RL方法提升了81.3%，总奖励增加4.3%，高估误差减少5.6%。实验结果表明，RG-CQL成功应对了大规模拼车系统与公共交通集成中从离线到在线RL过渡的挑战。

> This paper introduces a novel reinforcement learning (RL) framework, termed Reward-Guided Conservative Q-learning (RG-CQL), to enhance coordination between ride-pooling and public transit within a multimodal transportation network. We model each ride-pooling vehicle as an agent governed by a Markov Decision Process (MDP) and propose an offline training and online fine-tuning RL framework to learn the optimal operational decisions of the multimodal transportation systems, including rider-vehicle matching, selection of drop-off locations for passengers, and vehicle routing decisions, with improved data efficiency. During the offline training phase, we develop a Conservative Double Deep Q Network (CDDQN) as the action executor and a supervised learning-based reward estimator, termed the Guider Network, to extract valuable insights into action-reward relationships from data batches. In the online fine-tuning phase, the Guider Network serves as an exploration guide, aiding CDDQN in effectively and conservatively exploring unknown state-action pairs. The efficacy of our algorithm is demonstrated through a realistic case study using real-world data from Manhattan. We show that integrating ride-pooling with public transit outperforms two benchmark cases solo rides coordinated with transit and ride-pooling without transit coordination by 17% and 22% in the achieved system rewards, respectively. Furthermore, our innovative offline training and online fine-tuning framework offers a remarkable 81.3% improvement in data efficiency compared to traditional online RL methods with adequate exploration budgets, with a 4.3% increase in total rewards and a 5.6% reduction in overestimation errors. Experimental results further demonstrate that RG-CQL effectively addresses the challenges of transitioning from offline to online RL in large-scale ride-pooling systems integrated with transit.

[Arxiv](https://arxiv.org/abs/2501.14199)