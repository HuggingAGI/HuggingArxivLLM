# MoGERNN: 动态感知网络中未观测位置的智能交通预测器

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文提出了一个名为MoGERNN的模型，用于预测未观测位置的交通状态。虽然该模型本身并不是直接基于大型语言模型（LLM），但它受到了大型语言模型中专家混合方法的启发，并引入了图专家混合（MoGE）块来建模复杂的空间依赖关系。这表明该研究在某种程度上借鉴了LLM的思想和方法，并将其应用于交通预测领域。因此，将其分类为“LLM应用”是合适的。` `交通管理` `智能交通`

> MoGERNN: An Inductive Traffic Predictor for Unobserved Locations in Dynamic Sensing Networks

# 摘要

> 给定一个部分观测的道路网络，如何预测未观测位置的交通状态？尽管深度学习方法在交通预测中表现出色，但大多数方法假设所有感兴趣的位置都装有传感器，这在财务限制下是不现实的。此外，这些方法通常在传感器配置发生变化时需要昂贵的重新训练。我们提出了MoGERNN，一种归纳时空图表示模型，以应对这些挑战。受大型语言模型中专家混合方法的启发，我们引入了图专家混合（MoGE）块，通过多个图消息聚合器和一个稀疏门控网络来建模复杂的空间依赖关系。该块估计未观测位置的初始状态，然后由基于GRU的编码器-解码器处理，该编码器-解码器集成了图消息聚合器以捕捉时空依赖关系并预测未来状态。在两个真实世界数据集上的实验表明，MoGERNN在观测和未观测位置上都始终优于基线方法。MoGERNN即使在没有传感器的区域也能准确预测拥堵演变，为交通管理提供了宝贵信息。此外，MoGERNN能够适应动态传感网络，即使与重新训练的对应方法相比，也能保持竞争力。不同数量可用传感器的测试证实了其一致的优势，消融研究验证了其关键模块的有效性。

> Given a partially observed road network, how can we predict the traffic state of unobserved locations? While deep learning approaches show exceptional performance in traffic prediction, most assume sensors at all locations of interest, which is impractical due to financial constraints. Furthermore, these methods typically require costly retraining when sensor configurations change. We propose MoGERNN, an inductive spatio-temporal graph representation model, to address these challenges. Inspired by the Mixture of Experts approach in Large Language Models, we introduce a Mixture of Graph Expert (MoGE) block to model complex spatial dependencies through multiple graph message aggregators and a sparse gating network. This block estimates initial states for unobserved locations, which are then processed by a GRU-based Encoder-Decoder that integrates a graph message aggregator to capture spatio-temporal dependencies and predict future states. Experiments on two real-world datasets show MoGERNN consistently outperforms baseline methods for both observed and unobserved locations. MoGERNN can accurately predict congestion evolution even in areas without sensors, offering valuable information for traffic management. Moreover, MoGERNN is adaptable to dynamic sensing networks, maintaining competitive performance even compared to its retrained counterpart. Tests with different numbers of available sensors confirm its consistent superiority, and ablation studies validate the effectiveness of its key modules.

[Arxiv](https://arxiv.org/abs/2501.12281)