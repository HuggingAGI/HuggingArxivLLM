# RoboTwin：利用生成式数字孪生的双臂机器人基准

发布时间：2025年04月17日

`Agent

论文摘要讨论了机器人领域中的双臂协调与复杂物体操作，并介绍了RoboTwin框架，该框架结合了3D生成式模型和大型语言模型来生成数据和代码，提升机器人性能。因此，这篇论文属于Agent类别，因为它专注于智能体（机器人）的开发和应用。` `机器人` `自动化`

> RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins

# 摘要

> 在快速发展的机器人领域，双臂协调与复杂物体操作是开发先进自主系统的关键能力。然而，高质量多样化演示数据的匮乏以及与现实世界对齐的评估基准的缺失，严重制约了这一领域的发展。为了解决这一问题，我们推出了RoboTwin——一个基于3D生成式基础模型和大型语言模型的生成式数字孪生框架，用于生成多样化的专家数据集，并为双臂机器人任务提供与现实世界对齐的评估平台。具体来说，RoboTwin能够从单一的2D图像生成多样化的物体数字孪生，创造出真实且可交互的场景。它还引入了一种基于空间关系感知的代码生成框架，结合物体标注与大型语言模型，实现任务分解、空间约束判定以及精确机器人动作代码生成。我们的框架提供了包含模拟与现实数据的全面基准测试，支持标准化评估，并促进模拟训练与现实性能之间的更好对齐。我们通过开源的COBOT Magic Robot平台验证了这一方法。在RoboTwin生成数据上预训练，并通过有限现实样本进行微调的策略，相较于仅基于现实数据训练的模型，单臂任务成功率提升了70%以上，双臂任务成功率提升了40%以上，展现出显著的提升潜力。

> In the rapidly advancing field of robotics, dual-arm coordination and complex object manipulation are essential capabilities for developing advanced autonomous systems. However, the scarcity of diverse, high-quality demonstration data and real-world-aligned evaluation benchmarks severely limits such development. To address this, we introduce RoboTwin, a generative digital twin framework that uses 3D generative foundation models and large language models to produce diverse expert datasets and provide a real-world-aligned evaluation platform for dual-arm robotic tasks. Specifically, RoboTwin creates varied digital twins of objects from single 2D images, generating realistic and interactive scenarios. It also introduces a spatial relation-aware code generation framework that combines object annotations with large language models to break down tasks, determine spatial constraints, and generate precise robotic movement code. Our framework offers a comprehensive benchmark with both simulated and real-world data, enabling standardized evaluation and better alignment between simulated training and real-world performance. We validated our approach using the open-source COBOT Magic Robot platform. Policies pre-trained on RoboTwin-generated data and fine-tuned with limited real-world samples demonstrate significant potential for enhancing dual-arm robotic manipulation systems by improving success rates by over 70% for single-arm tasks and over 40% for dual-arm tasks compared to models trained solely on real-world data.

[Arxiv](https://arxiv.org/abs/2504.13059)