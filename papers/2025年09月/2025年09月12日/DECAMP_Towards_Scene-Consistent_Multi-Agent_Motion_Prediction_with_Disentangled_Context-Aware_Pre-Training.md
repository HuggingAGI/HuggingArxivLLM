# DECAMP：面向场景一致的多智能体运动预测——借助解耦上下文感知预训练

发布时间：2025年09月12日

`其他` `交通运输`

> DECAMP: Towards Scene-Consistent Multi-Agent Motion Prediction with Disentangled Context-Aware Pre-Training

# 摘要

> 轨迹预测是自动驾驶的核心模块，对保障道路安全与效率至关重要。但传统方法常受限于标记数据稀缺问题，在多智能体预测场景中表现欠佳。为此，我们提出了多智能体运动预测的解耦上下文感知预训练框架 DECAMP。不同于现有方法将表示学习与 pretext 任务纠缠，我们的框架将行为模式学习与潜在特征重建解耦，优先关注可解释动态，进而提升下游预测的场景表示能力。此外，框架还融合了上下文感知表示学习与协同空间-运动 pretext 任务，能在捕捉潜在动态意图的同时，联合优化结构推理与意图推理。在 Argoverse 2 基准数据集上的实验验证了该方法的优越性能，结果表明其在多智能体运动预测中成效显著。据我们所知，这是自动驾驶领域首个用于多智能体运动预测的上下文自编码器框架，相关代码与模型将公开共享。

> Trajectory prediction is a critical component of autonomous driving, essential for ensuring both safety and efficiency on the road. However, traditional approaches often struggle with the scarcity of labeled data and exhibit suboptimal performance in multi-agent prediction scenarios. To address these challenges, we introduce a disentangled context-aware pre-training framework for multi-agent motion prediction, named DECAMP. Unlike existing methods that entangle representation learning with pretext tasks, our framework decouples behavior pattern learning from latent feature reconstruction, prioritizing interpretable dynamics and thereby enhancing scene representation for downstream prediction. Additionally, our framework incorporates context-aware representation learning alongside collaborative spatial-motion pretext tasks, which enables joint optimization of structural and intentional reasoning while capturing the underlying dynamic intentions. Our experiments on the Argoverse 2 benchmark showcase the superior performance of our method, and the results attained underscore its effectiveness in multi-agent motion forecasting. To the best of our knowledge, this is the first context autoencoder framework for multi-agent motion forecasting in autonomous driving. The code and models will be made publicly available.

[Arxiv](https://arxiv.org/abs/2509.10426)