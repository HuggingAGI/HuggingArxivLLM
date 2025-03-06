# 探索真实世界物理动力学的视觉辨别与推理：基于物理的异常检测研究

发布时间：2025年03月05日

`其他`

> Towards Visual Discrimination and Reasoning of Real-World Physical Dynamics: Physics-Grounded Anomaly Detection

# 摘要

> 人类通过基于物体条件的物理知识感知、交互和推理来检测现实世界中的物体异常。工业异常检测（IAD）的目标是让机器能够自主复制这一技能。然而，现有的 IAD 算法主要依赖于静态、语义简单的数据集，这与现实世界中需要物理理解和推理的复杂场景相差甚远。

为弥合这一差距，我们推出了 Physics Anomaly Detection (Phys-AD) 数据集——首个大规模、现实世界、基于物理的工业异常检测视频数据集。通过真实机械臂和电机收集，Phys-AD 提供了多样化的动态、语义丰富的场景。该数据集包含 22 个现实世界物体类别的 6400 多个视频，展示了 47 种类型的异常。在 Phys-AD 中检测异常需要结合物理知识和视频内容进行视觉推理。

我们在无监督 AD、弱监督 AD 和视频理解 AD 三种设置下对现有最先进的异常检测方法进行了基准测试，揭示了它们在处理基于物理的异常方面的局限性。此外，我们引入了 Physics Anomaly Explanation (PAEval) 指标，旨在评估视觉-语言基础模型不仅能够检测异常，还能为其潜在物理原因提供准确解释的能力。我们的数据集和基准测试将公开发布，为相关研究提供重要支持。


> Humans detect real-world object anomalies by perceiving, interacting, and reasoning based on object-conditioned physical knowledge. The long-term goal of Industrial Anomaly Detection (IAD) is to enable machines to autonomously replicate this skill. However, current IAD algorithms are largely developed and tested on static, semantically simple datasets, which diverge from real-world scenarios where physical understanding and reasoning are essential.To bridge this gap, we introduce the Physics Anomaly Detection (Phys-AD) dataset, the first large-scale, real-world, physics-grounded video dataset for industrial anomaly detection. Collected using a real robot arm and motor, Phys-AD provides a diverse set of dynamic, semantically rich scenarios. The dataset includes more than 6400 videos across 22 real-world object categories, interacting with robot arms and motors, and exhibits 47 types of anomalies. Anomaly detection in Phys-AD requires visual reasoning, combining both physical knowledge and video content to determine object abnormality.We benchmark state-of-the-art anomaly detection methods under three settings: unsupervised AD, weakly-supervised AD, and video-understanding AD, highlighting their limitations in handling physics-grounded anomalies. Additionally, we introduce the Physics Anomaly Explanation (PAEval) metric, designed to assess the ability of visual-language foundation models to not only detect anomalies but also provide accurate explanations for their underlying physical causes. Our dataset and benchmark will be publicly available.

[Arxiv](https://arxiv.org/abs/2503.03562)