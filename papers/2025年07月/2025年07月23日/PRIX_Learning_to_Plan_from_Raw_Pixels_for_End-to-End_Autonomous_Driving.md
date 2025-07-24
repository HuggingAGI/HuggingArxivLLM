# # PRIX：从原始像素学习规划，实现端到端自动驾驶

发布时间：2025年07月23日

`其他` `自动驾驶` `计算机视觉`

> PRIX: Learning to Plan from Raw Pixels for End-to-End Autonomous Driving

# 摘要

> 尽管端到端自动驾驶模型展现出极具潜力的结果，但实际部署中常受限于模型体积庞大、昂贵的LiDAR传感器以及计算密集的BEV特征表示。这尤其限制了仅配备摄像头的量产车型的应用。为解决这些挑战，我们提出PRIX（Plan from Raw Pixels）。PRIX是一种新型高效端到端驾驶架构，仅使用摄像头数据，无需显式的BEV表示和LiDAR。通过视觉特征提取器与生成式规划头的结合，PRIX可直接从原始像素输入预测安全轨迹。我们架构的核心是上下文感知重校准变换器（CaRT），这一创新模块专为有效增强多级视觉特征以实现更稳健规划而设计。通过全面实验，PRIX在NavSim和nuScenes基准测试中达到了当前最优性能，其能力可与更大规模的多模态扩散规划器相媲美，同时在推理速度和模型规模上显著更高效，使其成为现实世界部署的切实可行的解决方案。我们的工作是开源的，代码将在https://maxiuw.github.io/prix上提供。


> While end-to-end autonomous driving models show promising results, their practical deployment is often hindered by large model sizes, a reliance on expensive LiDAR sensors and computationally intensive BEV feature representations. This limits their scalability, especially for mass-market vehicles equipped only with cameras. To address these challenges, we propose PRIX (Plan from Raw Pixels). Our novel and efficient end-to-end driving architecture operates using only camera data, without explicit BEV representation and forgoing the need for LiDAR. PRIX leverages a visual feature extractor coupled with a generative planning head to predict safe trajectories from raw pixel inputs directly. A core component of our architecture is the Context-aware Recalibration Transformer (CaRT), a novel module designed to effectively enhance multi-level visual features for more robust planning. We demonstrate through comprehensive experiments that PRIX achieves state-of-the-art performance on the NavSim and nuScenes benchmarks, matching the capabilities of larger, multimodal diffusion planners while being significantly more efficient in terms of inference speed and model size, making it a practical solution for real-world deployment. Our work is open-source and the code will be at https://maxiuw.github.io/prix.

[Arxiv](https://arxiv.org/abs/2507.17596)