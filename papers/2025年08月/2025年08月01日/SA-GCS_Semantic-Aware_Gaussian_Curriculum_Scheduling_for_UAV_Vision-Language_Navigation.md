# # SA-GCS：无人机视觉-语言导航的语义感知高斯课程调度方法

发布时间：2025年08月01日

`Agent` `无人机` `智慧城市`

> SA-GCS: Semantic-Aware Gaussian Curriculum Scheduling for UAV Vision-Language Navigation

# 摘要

> # 摘要  
无人机视觉语言导航（UAV VLN）旨在使智能体能够根据自然语言指令在复杂环境中准确定位目标并规划飞行路径，在智能巡检、灾害救援和城市监控等领域有广泛应用。近年来，视觉语言模型（VLMs）的进步为该任务提供了强大的语义理解能力，而强化学习（RL）作为一种有前途的后训练策略，被提出用于进一步提升模型的泛化能力。然而，现有的RL方法通常存在训练数据利用率低、收敛速度慢以及对训练样本难度差异考虑不足的问题，这限制了性能的进一步提升。为了解决这些挑战，我们提出了\textbf{语义感知高斯课程调度（SA-GCS）}，这是一种将课程学习（CL）系统性融入RL的新型训练框架。SA-GCS采用语义感知难度估计器（SA-DE）量化训练样本的复杂度，并通过高斯课程调度器（GCS）动态调整采样分布，从而实现从简单任务到具有挑战性任务的平滑过渡。这一设计显著提升了训练效率，加速了收敛过程，并增强了整体模型性能。在CityNav基准上的大量实验表明，SA-GCS在所有指标上均一致优于强大的基线方法，实现了更快且更稳定的收敛，并在不同规模的模型间表现出良好的泛化能力，凸显了其鲁棒性和可扩展性。我们的方法的实现已公开发布。

> Unmanned Aerial Vehicle (UAV) Vision-Language Navigation (VLN) aims to enable agents to accurately localize targets and plan flight paths in complex environments based on natural language instructions, with broad applications in intelligent inspection, disaster rescue, and urban monitoring. Recent progress in Vision-Language Models (VLMs) has provided strong semantic understanding for this task, while reinforcement learning (RL) has emerged as a promising post-training strategy to further improve generalization. However, existing RL methods often suffer from inefficient use of training data, slow convergence, and insufficient consideration of the difficulty variation among training samples, which limits further performance improvement. To address these challenges, we propose \textbf{Semantic-Aware Gaussian Curriculum Scheduling (SA-GCS)}, a novel training framework that systematically integrates Curriculum Learning (CL) into RL. SA-GCS employs a Semantic-Aware Difficulty Estimator (SA-DE) to quantify the complexity of training samples and a Gaussian Curriculum Scheduler (GCS) to dynamically adjust the sampling distribution, enabling a smooth progression from easy to challenging tasks. This design significantly improves training efficiency, accelerates convergence, and enhances overall model performance. Extensive experiments on the CityNav benchmark demonstrate that SA-GCS consistently outperforms strong baselines across all metrics, achieves faster and more stable convergence, and generalizes well across models of different scales, highlighting its robustness and scalability. The implementation of our approach is publicly available.

[Arxiv](https://arxiv.org/abs/2508.00390)