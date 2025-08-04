# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年07月31日

`其他` `城市交通` `传感器网络`

> INSPIRE-GNN: Intelligent Sensor Placement to Improve Sparse Bicycling Network Prediction via Reinforcement Learning Boosted Graph Neural Networks

# 摘要

> 准确估算自行车流量是实现可持续城市交通规划的关键。然而，许多城市由于传感器覆盖范围有限，面临数据稀疏性高的难题。为了解决这一挑战，我们提出了INSPIRE-GNN——一种结合强化学习（RL）的新型混合图神经网络（GNN）框架，旨在优化传感器部署并提升数据稀疏环境下的流量估计能力。该框架融合了图卷积网络（GCN）、图注意力网络（GAT）和基于深度Q网络（DQN）的强化学习代理，能够通过数据驱动的方式，战略性地选择传感器位置，以提升整体估计性能。在墨尔本的自行车网络中（包含15,933个道路段，其中仅141个路段有传感器覆盖，稀疏性高达99%），INSPIRE-GNN通过在50、100、200和500个传感器部署中选择最佳传感器位置，显著提升了流量估计效果。与传统的介数中心性、接近中心性、自行车活动观测和随机部署等启发式方法相比，INSPIRE-GNN在均方误差（MSE）、均方根误差（RMSE）和平均绝对误差（MAE）等关键指标上表现更优。此外，实验表明，与标准机器学习和深度学习模型相比，INSPIRE-GNN在自行车流量估计上更具优势。我们的框架为交通规划者提供了实用的见解，帮助他们有效扩展传感器网络、优化传感器部署，并提升自行车流量数据的估计精度和可靠性，从而支持更科学的交通规划决策。

> Accurate link-level bicycling volume estimation is essential for sustainable urban transportation planning. However, many cities face significant challenges of high data sparsity due to limited bicycling count sensor coverage. To address this issue, we propose INSPIRE-GNN, a novel Reinforcement Learning (RL)-boosted hybrid Graph Neural Network (GNN) framework designed to optimize sensor placement and improve link-level bicycling volume estimation in data-sparse environments. INSPIRE-GNN integrates Graph Convolutional Networks (GCN) and Graph Attention Networks (GAT) with a Deep Q-Network (DQN)-based RL agent, enabling a data-driven strategic selection of sensor locations to maximize estimation performance. Applied to Melbourne's bicycling network, comprising 15,933 road segments with sensor coverage on only 141 road segments (99% sparsity) - INSPIRE-GNN demonstrates significant improvements in volume estimation by strategically selecting additional sensor locations in deployments of 50, 100, 200 and 500 sensors. Our framework outperforms traditional heuristic methods for sensor placement such as betweenness centrality, closeness centrality, observed bicycling activity and random placement, across key metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). Furthermore, our experiments benchmark INSPIRE-GNN against standard machine learning and deep learning models in the bicycle volume estimation performance, underscoring its effectiveness. Our proposed framework provides transport planners actionable insights to effectively expand sensor networks, optimize sensor placement and maximize volume estimation accuracy and reliability of bicycling data for informed transportation planning decisions.

[Arxiv](https://arxiv.org/abs/2508.00141)