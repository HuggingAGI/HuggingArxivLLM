# # 从物理学到机器学习：回归之路（第二部分）- PHM中的学习与观测偏差

发布时间：2025年09月25日

`强化学习` `工业与制造`

> From Physics to Machine Learning and Back: Part II - Learning and Observational Bias in PHM

# 摘要

> 预测与健康管理通过在资产全生命周期内实现故障检测、预测设备故障和优化维护活动，确保复杂工程系统的可靠性、安全性与效率。然而，现实中的PHM仍面临诸多长期挑战：传感器数据常含噪声或不完整，可用标签有限，且退化行为与系统间依赖关系可能高度复杂且呈非线性。物理知情机器学习通过将物理知识融入数据驱动模型，为解决这些局限提供了一种极具潜力的方法。本综述探讨了如何通过物理知情建模与数据策略纳入学习和观察偏差，引导模型做出符合物理规律且可靠的预测。学习偏差通过物理知情损失函数、控制方程或纳入单调性等属性，将物理约束嵌入模型训练过程。观察偏差则通过虚拟传感（用于估计未测状态）、物理模拟（用于数据增强）及多传感器融合策略，影响数据选择与合成，确保模型捕捉真实系统行为。接着，综述探讨了这些方法如何借助强化学习实现从被动预测到主动决策的跨越——强化学习使智能体能够学习兼顾物理约束与运营目标优化的维护策略。这一过程闭合了基于模型的预测、模拟与实际系统运行之间的回路，为自适应决策提供了支持。最后，综述还讨论了将PHM解决方案从单资产扩展至全舰队部署的核心挑战。文中综述了元学习、少样本学习等快速适应方法，以及领域泛化技术...

> Prognostics and Health Management ensures the reliability, safety, and efficiency of complex engineered systems by enabling fault detection, anticipating equipment failures, and optimizing maintenance activities throughout an asset lifecycle. However, real-world PHM presents persistent challenges: sensor data is often noisy or incomplete, available labels are limited, and degradation behaviors and system interdependencies can be highly complex and nonlinear. Physics-informed machine learning has emerged as a promising approach to address these limitations by embedding physical knowledge into data-driven models. This review examines how incorporating learning and observational biases through physics-informed modeling and data strategies can guide models toward physically consistent and reliable predictions. Learning biases embed physical constraints into model training through physics-informed loss functions and governing equations, or by incorporating properties like monotonicity. Observational biases influence data selection and synthesis to ensure models capture realistic system behavior through virtual sensing for estimating unmeasured states, physics-based simulation for data augmentation, and multi-sensor fusion strategies. The review then examines how these approaches enable the transition from passive prediction to active decision-making through reinforcement learning, which allows agents to learn maintenance policies that respect physical constraints while optimizing operational objectives. This closes the loop between model-based predictions, simulation, and actual system operation, empowering adaptive decision-making. Finally, the review addresses the critical challenge of scaling PHM solutions from individual assets to fleet-wide deployment. Fast adaptation methods including meta-learning and few-shot learning are reviewed alongside domain generalization techniques ...

[Arxiv](https://arxiv.org/abs/2509.21207)