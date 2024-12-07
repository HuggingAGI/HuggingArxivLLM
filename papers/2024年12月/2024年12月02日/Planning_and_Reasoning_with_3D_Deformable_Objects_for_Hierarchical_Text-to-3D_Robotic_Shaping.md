# 针对分层文本到 3D 机器人成型中 3D 可变形物体的规划与推理

发布时间：2024年12月02日

`LLM应用` `机器人` `3D 成型`

> Planning and Reasoning with 3D Deformable Objects for Hierarchical Text-to-3D Robotic Shaping

# 摘要

> 可变形物体的操作一直是开发能在现实场景成功部署的自主机器人系统的关键难题。在本研究中，我们借由将黏土塑造成 3D 形状的任务来探究可变形物体操作所面临的挑战。我们提出了首个从粗到精的自主雕刻系统，在这个系统里，雕刻代理首先决定在工作空间放置多少个以及在何处放置离散的黏土块来塑造出粗略形状，然后通过一系列变形动作来迭代地优化形状。我们借助大型语言模型生成子目标，并训练基于点云区域的动作模型，依据所需的点云子目标来预测机器人动作。另外，我们的方法是首个自主雕刻系统，是现实世界中的文本到 3D 成型管道，系统未提供任何明确的 3D 目标或子目标。我们证明了我们的方法能够仅依靠基于文本的提示成功塑造出一组简单形状。而且，我们深入探讨了如何最优地量化文本到 3D 雕刻任务的成功，并将现有的文本图像和文本点云相似性指标与人类对此任务的评估进行对比。关于实验视频、人类评估详情和完整提示，请访问我们的项目网站：https://sites.google.com/andrew.cmu.edu/hierarchicalsculpting

> Deformable object manipulation remains a key challenge in developing autonomous robotic systems that can be successfully deployed in real-world scenarios. In this work, we explore the challenges of deformable object manipulation through the task of sculpting clay into 3D shapes. We propose the first coarse-to-fine autonomous sculpting system in which the sculpting agent first selects how many and where to place discrete chunks of clay into the workspace to create a coarse shape, and then iteratively refines the shape with sequences of deformation actions. We leverage large language models for sub-goal generation, and train a point cloud region-based action model to predict robot actions from the desired point cloud sub-goals. Additionally, our method is the first autonomous sculpting system that is a real-world text-to-3D shaping pipeline without any explicit 3D goals or sub-goals provided to the system. We demonstrate our method is able to successfully create a set of simple shapes solely from text-based prompting. Furthermore, we explore rigorously how to best quantify success for the text-to-3D sculpting task, and compare existing text-image and text-point cloud similarity metrics to human evaluations for this task. For experimental videos, human evaluation details, and full prompts, please see our project website: https://sites.google.com/andrew.cmu.edu/hierarchicalsculpting

[Arxiv](https://arxiv.org/abs/2412.01765)