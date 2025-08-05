# VPN：视觉提示导航

发布时间：2025年08月03日

`Agent` `计算机视觉` `机器人技术`

> VPN: Visual Prompt Navigation

# 摘要

> 尽管自然语言常用于指导具身智能体，但其固有的模糊性和冗长性往往限制了在复杂环境中进行语言引导导航的效果。针对这一问题，我们提出了一种全新范式——视觉提示导航（VPN），仅使用用户提供的视觉提示在2D俯视图地图上引导智能体导航。这种视觉提示主要关注在场景的俯视图中标记视觉导航轨迹，提供直观且基于空间的指导，无需依赖语言指令。它对非专家用户更友好，减少了解释上的模糊性。我们在离散和连续的导航设置下构建了VPN任务，通过在现有R2R和R2R-CE任务中添加相应的视觉提示，创建了两个新数据集R2R-VP和R2R-CE-VP。此外，我们引入了专门用于处理VPN任务的VPNet基线网络，并提出了两种数据增强策略：视角增强策略（改变初始朝向和提示方向）和轨迹增强策略（整合大规模3D场景中的多样化轨迹），以提升导航性能。大量实验评估了视觉提示形式、俯视图地图格式以及数据增强策略对视觉提示导航性能的影响。代码可在https://github.com/farlit/VPN获取。

> While natural language is commonly used to guide embodied agents, the inherent ambiguity and verbosity of language often hinder the effectiveness of language-guided navigation in complex environments. To this end, we propose Visual Prompt Navigation (VPN), a novel paradigm that guides agents to navigate using only user-provided visual prompts within 2D top-view maps. This visual prompt primarily focuses on marking the visual navigation trajectory on a top-down view of a scene, offering intuitive and spatially grounded guidance without relying on language instructions. It is more friendly for non-expert users and reduces interpretive ambiguity. We build VPN tasks in both discrete and continuous navigation settings, constructing two new datasets, R2R-VP and R2R-CE-VP, by extending existing R2R and R2R-CE episodes with corresponding visual prompts. Furthermore, we introduce VPNet, a dedicated baseline network to handle the VPN tasks, with two data augmentation strategies: view-level augmentation (altering initial headings and prompt orientations) and trajectory-level augmentation (incorporating diverse trajectories from large-scale 3D scenes), to enhance navigation performance. Extensive experiments evaluate how visual prompt forms, top-view map formats, and data augmentation strategies affect the performance of visual prompt navigation. The code is available at https://github.com/farlit/VPN.

[Arxiv](https://arxiv.org/abs/2508.01766)