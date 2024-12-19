# 通过大量人类视频进行学习，实现通用的类人姿势控制

发布时间：2024年12月18日

`LLM应用` `机器人` `人工智能`

> Learning from Massive Human Videos for Universal Humanoid Pose Control

# 摘要

> 可扩展学习对于人形机器人在现实应用中的部署至关重要。传统方法主要依赖强化学习或远程操作来实现全身控制，然而常受限于模拟环境的多样性及示范收集的高成本。相较而言，人类视频随处可见，是未被开发的语义和运动信息源，能显著提升人形机器人的泛化能力。本文引入了 Humanoid-X，这是一个拥有超 2000 万个人形机器人姿势及相应基于文本的运动描述的大规模数据集，旨在利用这丰富的数据。Humanoid-X 是通过全面的流程整理而成：从互联网挖掘数据、生成视频字幕、将人类运动重定向至人形机器人以及为现实部署进行策略学习。借助 Humanoid-X，我们进一步训练了大型人形模型 UH-1，它以文本指令为输入，输出相应动作以控制人形机器人。大量的模拟和现实实验证实，我们的可扩展训练方法在基于文本的人形控制中实现了出色的泛化，朝着适应性强、为现实世界做好准备的人形机器人迈出了重要一步。

> Scalable learning of humanoid robots is crucial for their deployment in real-world applications. While traditional approaches primarily rely on reinforcement learning or teleoperation to achieve whole-body control, they are often limited by the diversity of simulated environments and the high costs of demonstration collection. In contrast, human videos are ubiquitous and present an untapped source of semantic and motion information that could significantly enhance the generalization capabilities of humanoid robots. This paper introduces Humanoid-X, a large-scale dataset of over 20 million humanoid robot poses with corresponding text-based motion descriptions, designed to leverage this abundant data. Humanoid-X is curated through a comprehensive pipeline: data mining from the Internet, video caption generation, motion retargeting of humans to humanoid robots, and policy learning for real-world deployment. With Humanoid-X, we further train a large humanoid model, UH-1, which takes text instructions as input and outputs corresponding actions to control a humanoid robot. Extensive simulated and real-world experiments validate that our scalable training approach leads to superior generalization in text-based humanoid control, marking a significant step toward adaptable, real-world-ready humanoid robots.

[Arxiv](https://arxiv.org/abs/2412.14172)