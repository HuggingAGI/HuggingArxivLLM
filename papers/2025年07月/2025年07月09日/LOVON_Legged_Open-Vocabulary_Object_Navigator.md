# LOVON: 腿足式开放词汇表对象导航器

发布时间：2025年07月09日

`LLM应用` `机器人` `物体检测`

> LOVON: Legged Open-Vocabulary Object Navigator

# 摘要

> 在开放世界的环境中，物体导航对于机器人系统来说仍然是一个严峻而普遍的挑战，尤其是在执行需要开放世界物体检测和高层任务规划的长时域任务时。传统方法往往难以有效整合这些组件，这限制了它们处理复杂、长距离导航任务的能力。本文中，我们提出了LOVON，一个将大型语言模型（LLMs）用于分层任务规划与开放词汇视觉检测模型相结合的新型框架，专为在动态、无结构环境中实现有效的长距离物体导航而设计。为了应对视觉抖动、盲区和临时目标丢失等现实挑战，我们设计了专门的解决方案，例如用于视觉稳定的拉普拉斯方差滤波。我们还为机器人开发了一套功能执行逻辑，以确保LOVON在自主导航、任务适应和鲁棒任务完成方面的能力。广泛的评估证明了涉及实时检测、搜索和导航至开放词汇动态目标的长序列任务的成功完成。此外，跨不同腿式机器人（Unitree Go2、B2 和 H1-2）的现实世界实验展示了LOVON的兼容性和吸引人的即插即用特性。

> Object navigation in open-world environments remains a formidable and pervasive challenge for robotic systems, particularly when it comes to executing long-horizon tasks that require both open-world object detection and high-level task planning. Traditional methods often struggle to integrate these components effectively, and this limits their capability to deal with complex, long-range navigation missions. In this paper, we propose LOVON, a novel framework that integrates large language models (LLMs) for hierarchical task planning with open-vocabulary visual detection models, tailored for effective long-range object navigation in dynamic, unstructured environments. To tackle real-world challenges including visual jittering, blind zones, and temporary target loss, we design dedicated solutions such as Laplacian Variance Filtering for visual stabilization. We also develop a functional execution logic for the robot that guarantees LOVON's capabilities in autonomous navigation, task adaptation, and robust task completion. Extensive evaluations demonstrate the successful completion of long-sequence tasks involving real-time detection, search, and navigation toward open-vocabulary dynamic targets. Furthermore, real-world experiments across different legged robots (Unitree Go2, B2, and H1-2) showcase the compatibility and appealing plug-and-play feature of LOVON.

[Arxiv](https://arxiv.org/abs/2507.06747)