# AdaF^2M^2: 推荐系统中的全方位学习与动态特征利用

发布时间：2025年01月27日

`其他

理由：这篇论文主要讨论的是推荐系统中的特征建模问题，特别是针对长尾数据分布的挑战。虽然论文中提到了模型的应用和效果，但其核心内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）、智能体（Agent）或LLM的理论研究。因此，将其归类为“其他”更为合适。` `推荐系统` `工业应用`

> AdaF^2M^2: Comprehensive Learning and Responsive Leveraging Features in Recommendation System

# 摘要

> # 摘要
特征建模（包括特征表示学习和利用）在工业推荐系统中至关重要。然而，现实应用中的数据分布常因流行度偏差呈现长尾模式，导致模型过度依赖基于ID的特征（如用户/物品ID和交互序列），难以全面学习非ID元特征（如用户/物品属性）。这种依赖还削弱了模型的泛化能力，使其更容易受数据噪声影响。以往研究多聚焦于特征提取和交互，忽视了长尾分布带来的问题。为此，我们提出了模型无关框架AdaF^2M^2（Adaptive Feature Modeling with Feature Mask），通过特征掩码机制和多前向训练增强样本学习，并结合适配器为不同用户/物品状态赋予自适应权重。在线A/B测试显示，AdaF^2M^2在用户活跃天数和应用时长上分别提升了1.37%和1.89%。离线实验也验证了其有效性。目前，AdaF^2M^2已在抖音集团的多个应用中广泛部署，展现了其卓越的普适性和效果。

> Feature modeling, which involves feature representation learning and leveraging, plays an essential role in industrial recommendation systems. However, the data distribution in real-world applications usually follows a highly skewed long-tail pattern due to the popularity bias, which easily leads to over-reliance on ID-based features, such as user/item IDs and ID sequences of interactions. Such over-reliance makes it hard for models to learn features comprehensively, especially for those non-ID meta features, e.g., user/item characteristics. Further, it limits the feature leveraging ability in models, getting less generalized and more susceptible to data noise. Previous studies on feature modeling focus on feature extraction and interaction, hardly noticing the problems brought about by the long-tail data distribution. To achieve better feature representation learning and leveraging on real-world data, we propose a model-agnostic framework AdaF^2M^2, short for Adaptive Feature Modeling with Feature Mask. The feature-mask mechanism helps comprehensive feature learning via multi-forward training with augmented samples, while the adapter applies adaptive weights on features responsive to different user/item states. By arming base models with AdaF^2M^2, we conduct online A/B tests on multiple recommendation scenarios, obtaining +1.37% and +1.89% cumulative improvements on user active days and app duration respectively. Besides, the extended offline experiments on different models show improvements as well. AdaF$^2$M$^2$ has been widely deployed on both retrieval and ranking tasks in multiple applications of Douyin Group, indicating its superior effectiveness and universality.

[Arxiv](https://arxiv.org/abs/2501.15816)