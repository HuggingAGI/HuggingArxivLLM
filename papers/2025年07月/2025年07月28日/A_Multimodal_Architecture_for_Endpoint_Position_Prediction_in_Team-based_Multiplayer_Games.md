# # A Multimodal Architecture for Endpoint Position Prediction in Team-based Multiplayer Games
# 为基于团队的多人游戏设计的多模态终点位置预测架构

发布时间：2025年07月28日

`Agent` `机器人导航`

> A Multimodal Architecture for Endpoint Position Prediction in Team-based Multiplayer Games

# 摘要

> 理解并预测多人游戏中的玩家移动对于实现模仿玩家行为的机器人导航、预防性机器人控制、策略推荐以及实时玩家行为分析等应用场景至关重要。然而，复杂的游戏环境为玩家提供了高度的导航自由度，同时玩家之间的互动和团队合作需要模型能够有效利用各种异构输入数据。本文提出了一种基于多模态架构的未来玩家位置预测方法，采用基于U-Net的端点位置概率热图计算方法，并通过多模态特征编码器进行条件约束。通过应用多头注意力机制来实现不同特征组之间的通信。这样，该架构能够高效利用包括图像输入、数值和类别特征以及动态游戏数据在内的多模态游戏状态。因此，本文提出的技术为依赖未来玩家位置的各种下游任务奠定了基础，例如创建基于预测的机器人行为或检测玩家异常行为。

> Understanding and predicting player movement in multiplayer games is crucial for achieving use cases such as player-mimicking bot navigation, preemptive bot control, strategy recommendation, and real-time player behavior analytics. However, the complex environments allow for a high degree of navigational freedom, and the interactions and team-play between players require models that make effective use of the available heterogeneous input data. This paper presents a multimodal architecture for predicting future player locations on a dynamic time horizon, using a U-Net-based approach for calculating endpoint location probability heatmaps, conditioned using a multimodal feature encoder. The application of a multi-head attention mechanism for different groups of features allows for communication between agents. In doing so, the architecture makes efficient use of the multimodal game state including image inputs, numerical and categorical features, as well as dynamic game data. Consequently, the presented technique lays the foundation for various downstream tasks that rely on future player positions such as the creation of player-predictive bot behavior or player anomaly detection.

[Arxiv](https://arxiv.org/abs/2507.20670)