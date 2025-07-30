# # 摘要
利用深度强化学习优化小区DTX/DRX配置，实现网络节能

发布时间：2025年07月28日

`Agent` `人工智能`

> Deep Reinforcement Learning-based Cell DTX/DRX Configuration for Network Energy Saving

# 摘要

> 3GPP Release 18小区不连续传输和接收（cell DTX/DRX）是5G网络中的一个重要新节能功能。作为一种时间域技术，它在交通负载不重的时间段内，定期聚合用户数据传输，这样剩下的时间就可以保持静默，启用先进睡眠模式（ASM），关闭更多无线组件，从而节省更多能源。然而，不可避免的是，数据包延迟会增加，因为在静默期间不允许传输。本文研究如何配置小区DTX/DRX，以在节能和数据包延迟之间达到最佳平衡，使得对于延迟敏感的流量，在最小化服务质量（QoS）下降的同时，实现最大的节能。由于最优配置在不同网络和流量条件下可能不同，这个问题相当复杂，因此我们求助于深度强化学习（DRL）框架来训练一个AI代理来解决它。通过精心设计1) 学习算法，它在一个上下文强盗（CB）模型上实现深度Q网络（DQN），以及2) 奖励函数，它利用了理论上最优但不连续的奖励函数的平滑近似，我们能够训练出一个AI代理，它始终试图在任何网络和流量条件下选择最佳的小区DTX/DRX配置。仿真结果表明，与未使用小区DTX/DRX的情况相比，我们的代理可以根据流量负载场景实现高达约45%的节能，同时始终保持不超过约1%的服务质量下降。

> 3GPP Release 18 cell discontinuous transmission and reception (cell DTX/DRX) is an important new network energy saving feature for 5G. As a time-domain technique, it periodically aggregates the user data transmissions in a given duration of time when the traffic load is not heavy, so that the remaining time can be kept silent and advanced sleep modes (ASM) can be enabled to shut down more radio components and save more energy for the cell. However, inevitably the packet delay is increased, as during the silent period no transmission is allowed. In this paper we study how to configure cell DTX/DRX to optimally balance energy saving and packet delay, so that for delay-sensitive traffic maximum energy saving can be achieved while the degradation of quality of service (QoS) is minimized. As the optimal configuration can be different for different network and traffic conditions, the problem is complex and we resort to deep reinforcement learning (DRL) framework to train an AI agent to solve it. Through careful design of 1) the learning algorithm, which implements a deep Q-network (DQN) on a contextual bandit (CB) model, and 2) the reward function, which utilizes a smooth approximation of a theoretically optimal but discontinuous reward function, we are able to train an AI agent that always tries to select the best possible Cell DTX/DRX configuration under any network and traffic conditions. Simulation results show that compared to the case when cell DTX/DRX is not used, our agent can achieve up to ~45% energy saving depending on the traffic load scenario, while always maintaining no more than ~1% QoS degradation.

[Arxiv](https://arxiv.org/abs/2507.21385)