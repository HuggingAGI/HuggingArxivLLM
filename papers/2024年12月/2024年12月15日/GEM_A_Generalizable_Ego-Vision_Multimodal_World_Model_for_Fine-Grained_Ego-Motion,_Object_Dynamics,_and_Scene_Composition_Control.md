# GEM: 可泛化的自我视觉多模态世界模型，精准掌控自我运动、物体动力学与场景组合

发布时间：2024年12月15日

`其他

理由：这篇论文主要介绍了一个名为GEM的自我视觉多模态世界模型，专注于通过多模态数据预测未来帧，并涉及物体动态、自我代理运动和人姿态的控制。虽然它涉及生成模型和自回归技术，但其核心内容并不直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题。因此，将其分类为“其他”更为合适。` `自动驾驶` `无人机`

> GEM: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control

# 摘要

> 我们推出了GEM，一个可泛化的自我视觉多模态世界模型，通过参考帧、稀疏特征、人体姿态和自我轨迹预测未来帧。GEM精确控制物体动态、自我代理运动和人姿态，并生成配对的RGB和深度输出，增强空间理解。我们采用自回归噪声调度，确保长时程生成的稳定性。数据集包含4000多小时的多模态数据，涵盖自动驾驶、自我中心的人类活动和无人机飞行等领域。通过伪标签获取深度图、自我轨迹和人体姿态。我们引入了一个全面的评估框架，包括新的物体操作控制（COM）指标，评估可控性。实验证明，GEM在生成多样化、可控场景和长时间生成的时间一致性方面表现卓越。代码、模型和数据集均已开源。

> We present GEM, a Generalizable Ego-vision Multimodal world model that predicts future frames using a reference frame, sparse features, human poses, and ego-trajectories. Hence, our model has precise control over object dynamics, ego-agent motion and human poses. GEM generates paired RGB and depth outputs for richer spatial understanding. We introduce autoregressive noise schedules to enable stable long-horizon generations. Our dataset is comprised of 4000+ hours of multimodal data across domains like autonomous driving, egocentric human activities, and drone flights. Pseudo-labels are used to get depth maps, ego-trajectories, and human poses. We use a comprehensive evaluation framework, including a new Control of Object Manipulation (COM) metric, to assess controllability. Experiments show GEM excels at generating diverse, controllable scenarios and temporal consistency over long generations. Code, models, and datasets are fully open-sourced.

[Arxiv](https://arxiv.org/abs/2412.11198)