# 直接偏好优化的主动学习方法

发布时间：2025年03月02日

`Agent` `主动学习框架`

> Active Learning for Direct Preference Optimization

# 摘要

> 直接偏好优化（DPO）是一种从人类反馈中进行强化学习的方法，它通过直接利用偏好反馈来优化策略。尽管存在多种人类偏好模型，但如何选择最具信息量的反馈用于训练这一关键任务仍未得到充分探索。我们提出了一种适用于DPO的主动学习框架，它既可用于在线收集人类反馈，也可用于从已收集的反馈中选择最具信息量的子集进行离线处理。我们分别为这两种场景设计了高效的算法。核心思想是将DPO目标在优化策略的神经网络表示的最后一层进行线性化，然后通过计算D-最优设计来收集偏好反馈。我们证明了随着反馈量的增加，我们的DPO对数几率估计误差会减小。我们在与理论相匹配的设置以及大型语言模型上进行了实证研究，展示了我们算法的有效性。

> Direct preference optimization (DPO) is a form of reinforcement learning from human feedback (RLHF) where the policy is learned directly from preferential feedback. Although many models of human preferences exist, the critical task of selecting the most informative feedback for training them is under-explored. We propose an active learning framework for DPO, which can be applied to collect human feedback online or to choose the most informative subset of already collected feedback offline. We propose efficient algorithms for both settings. The key idea is to linearize the DPO objective at the last layer of the neural network representation of the optimized policy and then compute the D-optimal design to collect preferential feedback. We prove that the errors in our DPO logit estimates diminish with more feedback. We show the effectiveness of our algorithms empirically in the setting that matches our theory and also on large language models.

[Arxiv](https://arxiv.org/abs/2503.01076)