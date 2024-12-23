# 人类移动性预测的通用模型

发布时间：2024年12月19日

`其他` `城市规划`

> A Universal Model for Human Mobility Prediction

# 摘要

> 预测人类移动性对于城市规划、交通管控和应急响应意义重大。移动行为可分为个体和集体两类，其由诸如个体轨迹和人群流量等多种移动数据予以记录。作为不同类型的移动数据，个体轨迹和人群流量存在紧密的耦合关系。人群流量源自个体轨迹的自下而上聚合，而人群流量所施加的限制塑造了这些个体轨迹。由于个体轨迹和人群流量之间存在模态差异，现有的移动性预测方法局限于单一任务。在本研究中，我们致力于统一移动性预测，以突破特定任务模型的限制。我们提出了一个通用的人类移动性预测模型（命名为 UniMob），它能够适用于个体轨迹和人群流量。UniMob 借助多视图移动性标记器，将轨迹和流量数据都转化为时空标记，通过扩散变压器架构助力统一的序列建模。为了弥补这两种数据模式不同特征之间的差距，我们实施了一种新颖的双向个体和集体对齐机制。该机制能够从不同的移动数据中学习共同的时空模式，促进轨迹和流量预测的相互增强。在真实世界数据集上开展的大量实验证实，我们的模型在轨迹和流量预测方面优于最先进的基线。特别是在噪声和稀缺数据的场景中，我们的模型在 MAPE 和 Accuracy@5 中分别实现了超过 14％和 25％的最高性能提升。

> Predicting human mobility is crucial for urban planning, traffic control, and emergency response. Mobility behaviors can be categorized into individual and collective, and these behaviors are recorded by diverse mobility data, such as individual trajectory and crowd flow. As different modalities of mobility data, individual trajectory and crowd flow have a close coupling relationship. Crowd flows originate from the bottom-up aggregation of individual trajectories, while the constraints imposed by crowd flows shape these individual trajectories. Existing mobility prediction methods are limited to single tasks due to modal gaps between individual trajectory and crowd flow. In this work, we aim to unify mobility prediction to break through the limitations of task-specific models. We propose a universal human mobility prediction model (named UniMob), which can be applied to both individual trajectory and crowd flow. UniMob leverages a multi-view mobility tokenizer that transforms both trajectory and flow data into spatiotemporal tokens, facilitating unified sequential modeling through a diffusion transformer architecture. To bridge the gap between the different characteristics of these two data modalities, we implement a novel bidirectional individual and collective alignment mechanism. This mechanism enables learning common spatiotemporal patterns from different mobility data, facilitating mutual enhancement of both trajectory and flow predictions. Extensive experiments on real-world datasets validate the superiority of our model over state-of-the-art baselines in trajectory and flow prediction. Especially in noisy and scarce data scenarios, our model achieves the highest performance improvement of more than 14% and 25% in MAPE and Accuracy@5.

[Arxiv](https://arxiv.org/abs/2412.15294)