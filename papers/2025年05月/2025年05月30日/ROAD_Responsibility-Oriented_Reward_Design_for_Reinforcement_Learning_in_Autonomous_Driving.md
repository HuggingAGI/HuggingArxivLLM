# # 责任导向的奖励设计在自动驾驶强化学习中的应用 (ROAD)
在自动驾驶的强化学习中，责任导向的奖励设计是一个至关重要的研究方向。

发布时间：2025年05月30日

`RAG` `自动驾驶` `交通法规`

> ROAD: Responsibility-Oriented Reward Design for Reinforcement Learning in Autonomous Driving

# 摘要

> 强化学习 (RL) 在自动驾驶中通过试错机制提升了在不可预测环境中的鲁棒性。然而，设计有效的奖励函数依然面临挑战，传统方法严重依赖手动设计且在复杂场景中效果有限。为解决这一问题，本研究提出了一种责任导向的奖励函数，将交通法规显式纳入 RL 框架。具体而言，我们引入了交通法规知识图谱，并结合视觉语言模型和检索增强生成技术，实现了奖励的自动化分配。这种整合引导代理严格遵守交通法规，从而减少违规行为，并在各种驾驶条件下优化决策性能。实验结果表明，所提出的方法显著提升了事故责任判定的准确性，并有效降低了代理在交通事件中的责任。

> Reinforcement learning (RL) in autonomous driving employs a trial-and-error mechanism, enhancing robustness in unpredictable environments. However, crafting effective reward functions remains challenging, as conventional approaches rely heavily on manual design and demonstrate limited efficacy in complex scenarios. To address this issue, this study introduces a responsibility-oriented reward function that explicitly incorporates traffic regulations into the RL framework. Specifically, we introduced a Traffic Regulation Knowledge Graph and leveraged Vision-Language Models alongside Retrieval-Augmented Generation techniques to automate reward assignment. This integration guides agents to adhere strictly to traffic laws, thus minimizing rule violations and optimizing decision-making performance in diverse driving conditions. Experimental validations demonstrate that the proposed methodology significantly improves the accuracy of assigning accident responsibilities and effectively reduces the agent's liability in traffic incidents.

[Arxiv](https://arxiv.org/abs/2505.24317)