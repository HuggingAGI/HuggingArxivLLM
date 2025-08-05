# MHARFedLLM：多模态人体活动识别的联邦大模型

发布时间：2025年08月03日

`LLM应用

摘要中提到，这篇论文将轻量级的T5编码器架构应用于人体活动识别任务，属于将大型语言模型（T5）应用于特定领域的实际问题，因此归类为LLM应用。` `健身追踪` `健康监测`

> MHARFedLLM: Multimodal Human Activity Recognition Using Federated Large Language Model

# 摘要

> 人体活动识别（HAR）在健身追踪、智能家居和健康监测等领域发挥着重要作用。然而，传统HAR系统往往依赖单一模态（如运动传感器或摄像头），这在复杂的真实环境中限制了其准确性和鲁棒性。本研究提出了一种全新的多模态联邦学习框架FedTime-MAGNET，通过融合深度摄像头、压力垫和加速度计等多种异构数据源来提升HAR性能。该框架的核心是多模态自适应图神经专家变换器（MAGNET），它通过图注意力机制和专家混合策略生成跨模态的统一判别嵌入。为了更好地捕捉复杂的时序依赖关系，本研究还定制并优化了一种轻量级的T5编码器架构。实验结果表明，FedTime-MAGNET显著提升了HAR性能，实现了中心化F1分数0.934和联邦F1分数0.881的优异表现。这充分证明了将多模态融合、时序LLM和联邦学习相结合在构建准确且鲁棒的HAR系统中的巨大潜力。

> Human Activity Recognition (HAR) plays a vital role in applications such as fitness tracking, smart homes, and healthcare monitoring. Traditional HAR systems often rely on single modalities, such as motion sensors or cameras, limiting robustness and accuracy in real-world environments. This work presents FedTime-MAGNET, a novel multimodal federated learning framework that advances HAR by combining heterogeneous data sources: depth cameras, pressure mats, and accelerometers. At its core is the Multimodal Adaptive Graph Neural Expert Transformer (MAGNET), a fusion architecture that uses graph attention and a Mixture of Experts to generate unified, discriminative embeddings across modalities. To capture complex temporal dependencies, a lightweight T5 encoder only architecture is customized and adapted within this framework. Extensive experiments show that FedTime-MAGNET significantly improves HAR performance, achieving a centralized F1 Score of 0.934 and a strong federated F1 Score of 0.881. These results demonstrate the effectiveness of combining multimodal fusion, time series LLMs, and federated learning for building accurate and robust HAR systems.

[Arxiv](https://arxiv.org/abs/2508.01701)