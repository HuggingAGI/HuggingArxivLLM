# 面向边缘数据流处理的主动式自动扩缩框架：基于GRU和迁移学习的方法

发布时间：2025年07月19日

`其他` `数据流处理` `边缘计算`

> Towards a Proactive Autoscaling Framework for Data Stream Processing at the Edge using GRU and Transfer Learning

# 摘要

> 在数字经济生成海量数据的背景下，高速数据处理变得越来越重要。目前，及时处理数据的两大范式是边缘计算和数据流处理（DSP）。边缘计算将资源部署在数据生成的附近，而流处理则分析高速流动的无界数据。然而，边缘流处理面临快速波动的工作负载，使得资源供应变得复杂。资源分配不足会导致瓶颈，而过度分配则会造成浪费。

现有反应式方法，如基于阈值的策略和队列理论，在性能下降后才进行扩展，可能导致SLA违规。虽然强化学习（RL）通过智能体学习最优运行时适应策略提供了一种主动方法，但需要大量模拟。此外，预测机器学习模型还面临在线分布和概念漂移问题，这些问题会降低其准确性。

我们针对主动边缘流处理的自动扩缩问题提出了一种三步解决方案。首先，使用GRU神经网络基于真实世界和合成DSP数据集预测上游负载。其次，通过转移学习框架，利用DTW算法和联合分布适应，将预测模型集成到在线流处理系统中，以处理离线和在线领域之间的差异。最后，水平自动扩缩模块根据预测负载，同时考虑边缘资源限制，动态调整操作符的并行程度。

在真实数据集上，用于负载预测的轻量级GRU模型记录了高达1.3% SMAPE值。它在SMAPE和RMSE评估指标上优于CNN、ARIMA和Prophet，并且训练时间低于计算密集型的RL模型。

> Processing data at high speeds is becoming increasingly critical as digital economies generate enormous data. The current paradigms for timely data processing are edge computing and data stream processing (DSP). Edge computing places resources closer to where data is generated, while stream processing analyzes the unbounded high-speed data in motion. However, edge stream processing faces rapid workload fluctuations, complicating resource provisioning. Inadequate resource allocation leads to bottlenecks, whereas excess allocation results in wastage. Existing reactive methods, such as threshold-based policies and queuing theory scale only after performance degrades, potentially violating SLAs. Although reinforcement learning (RL) offers a proactive approach through agents that learn optimal runtime adaptation policies, it requires extensive simulation. Furthermore, predictive machine learning models face online distribution and concept drift that minimize their accuracy. We propose a three-step solution to the proactive edge stream processing autoscaling problem. Firstly, a GRU neural network forecasts the upstream load using real-world and synthetic DSP datasets. Secondly, a transfer learning framework integrates the predictive model into an online stream processing system using the DTW algorithm and joint distribution adaptation to handle the disparities between offline and online domains. Finally, a horizontal autoscaling module dynamically adjusts the degree of operator parallelism, based on predicted load while considering edge resource constraints. The lightweight GRU model for load predictions recorded up to 1.3\% SMAPE value on a real-world data set. It outperformed CNN, ARIMA, and Prophet on the SMAPE and RMSE evaluation metrics, with lower training time than the computationally intensive RL models.

[Arxiv](https://arxiv.org/abs/2507.14597)