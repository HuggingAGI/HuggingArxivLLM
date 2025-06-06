# 空地一体化机器人系统中的语义导航与操作，基于分层语言模型

发布时间：2025年06月05日

`Agent` `机器人`

> Hierarchical Language Models for Semantic Navigation and Manipulation in an Aerial-Ground Robotic System

# 摘要

> 异构多机器人系统在复杂任务中展现出巨大潜力，但传统方法难以应对多样性和动态环境。我们提出了一种创新的分层框架，结合提示强化的大型语言模型（LLM）与GridMask增强型视觉语言模型（VLM）。LLM负责任务分解和全局语义地图构建，VLM从航拍图像中提取语义信息，支持局部规划。空中机器人提供鸟瞰图像，指导地面机器人的导航与操作，包括目标缺失场景。真实世界实验验证了该框架的适应性和鲁棒性。这标志着首次将基于VLM的感知与LLM驱动的推理规划相结合，开创了空地异构系统的新纪元。

> Heterogeneous multi-robot systems show great potential in complex tasks requiring coordinated hybrid cooperation. However, traditional approaches relying on static models often struggle with task diversity and dynamic environments. This highlights the need for generalizable intelligence that can bridge high-level reasoning with low-level execution across heterogeneous agents. To address this, we propose a hierarchical framework integrating a prompted Large Language Model (LLM) and a GridMask-enhanced fine-tuned Vision Language Model (VLM). The LLM performs task decomposition and global semantic map construction, while the VLM extracts task-specified semantic labels and 2D spatial information from aerial images to support local planning. Within this framework, the aerial robot follows a globally optimized semantic path and continuously provides bird-view images, guiding the ground robot's local semantic navigation and manipulation, including target-absent scenarios where implicit alignment is maintained. Experiments on a real-world letter-cubes arrangement task demonstrate the framework's adaptability and robustness in dynamic environments. To the best of our knowledge, this is the first demonstration of an aerial-ground heterogeneous system integrating VLM-based perception with LLM-driven task reasoning and motion planning.

[Arxiv](https://arxiv.org/abs/2506.05020)