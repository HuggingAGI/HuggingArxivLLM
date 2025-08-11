# # 通过可扩展侧面专家混合模型实现高效多模态流推荐
通过可扩展侧面专家混合模型，我们实现了一种高效地进行多模态流推荐的方法。

发布时间：2025年08月08日

`其他` `推荐系统` `媒体内容推荐`

> Efficient Multimodal Streaming Recommendation via Expandable Side Mixture-of-Experts

# 摘要

> # 流推荐系统概述
流推荐系统（SRS）在实际应用中被广泛应用，因为用户兴趣随时间变化，新项目不断涌现。然而，有效捕捉用户的最新偏好充满挑战，因为反映近期兴趣的交互行为有限，而新项目往往缺乏足够的反馈。

**解决方案与挑战**  
一个常见方法是利用多模态编码器（如BERT或ViT）提取视觉和文本特征以丰富项目表示。然而，这些编码器是为通用任务预训练的，未专门针对用户偏好建模，且忽视了用户对特定模态特征（如视觉风格和文本语气）的偏好也会随时间漂移的事实。这在流场景中带来了两个关键挑战：
1. 对大型多模态编码器进行微调的高成本
2. 由于持续的模型更新而忘记长期用户偏好的风险

**我们的解决方案：XSMoE框架**  
为应对这些挑战，我们提出了**可扩展侧面专家混合模型（XSMoE）**，这是一种适用于多模态流推荐的内存高效框架。其核心思想是：
- 将轻量级侧面微调模块附加到冻结的预训练编码器上，这些模块包含可扩展的专家网络
- 根据用户反馈的演变逐步扩展这些模块
- 通过门控路由器动态结合专家和主干输出
- 采用基于利用率的剪枝策略保持模型紧凑性

**优势与效果**  
通过可扩展的专家学习新的模式，而不会覆盖之前获得的知识，XSMoE能够有效捕捉多模态特征中的冷启动和偏好的变化。实验结果表明：
- 在三个真实数据集上，XSMoE在推荐质量和计算效率方面均优于现有先进基线模型
- 其创新的动态扩展机制在保持模型紧凑性的同时，有效应对了流场景中的挑战

这一研究为多模态流推荐系统提供了一种高效、灵活的解决方案，具有重要的理论价值和实际应用意义。

> Streaming recommender systems (SRSs) are widely deployed in real-world applications, where user interests shift and new items arrive over time. As a result, effectively capturing users' latest preferences is challenging, as interactions reflecting recent interests are limited and new items often lack sufficient feedback. A common solution is to enrich item representations using multimodal encoders (e.g., BERT or ViT) to extract visual and textual features. However, these encoders are pretrained on general-purpose tasks: they are not tailored to user preference modeling, and they overlook the fact that user tastes toward modality-specific features such as visual styles and textual tones can also drift over time. This presents two key challenges in streaming scenarios: the high cost of fine-tuning large multimodal encoders, and the risk of forgetting long-term user preferences due to continuous model updates.
  To tackle these challenges, we propose Expandable Side Mixture-of-Experts (XSMoE), a memory-efficient framework for multimodal streaming recommendation. XSMoE attaches lightweight side-tuning modules consisting of expandable expert networks to frozen pretrained encoders and incrementally expands them in response to evolving user feedback. A gating router dynamically combines expert and backbone outputs, while a utilization-based pruning strategy maintains model compactness. By learning new patterns through expandable experts without overwriting previously acquired knowledge, XSMoE effectively captures both cold start and shifting preferences in multimodal features. Experiments on three real-world datasets demonstrate that XSMoE outperforms state-of-the-art baselines in both recommendation quality and computational efficiency.

[Arxiv](https://arxiv.org/abs/2508.05993)