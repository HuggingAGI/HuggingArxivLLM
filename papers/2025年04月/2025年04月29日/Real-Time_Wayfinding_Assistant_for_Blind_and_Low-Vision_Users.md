# 实时导览辅助工具：专为视障人士及低视力人群设计

发布时间：2025年04月29日

`LLM应用` `人工智能`

> Real-Time Wayfinding Assistant for Blind and Low-Vision Users

# 摘要

> 探索陌生环境对视障人士（BLV）而言仍是日常生活中最持久且关键的障碍之一。现有辅助技术，如基于GPS的导航系统、AI驱动的智能眼镜及配备声纳的拐杖，往往在实时障碍规避、精准定位及适应动态环境方面存在局限。为探索解决方案，我们开发了名为PathFinder的新型无地图导航系统。该系统采用视觉语言模型（VLMs）、大型语言模型（LLMs）等不同模型来解析2D图像，并通过单目深度估计技术进行无障碍路径检测。我们的方法整合了深度优先搜索（DFS）算法，用于深度图像中的最长无障路径计算，确保在保持计算效率的同时实现最优路线选择。我们对比评估了现有AI驱动导航方法，并与BLV参与者进行了可用性研究。结果显示，PathFinder在精度、计算效率及实时响应间取得了良好平衡。值得注意的是，与基于AI的替代方案相比，该系统在户外导航中降低了平均绝对误差（MAE），并提升了决策速度。参与者反馈强调了系统在户外环境中的实用性和有效性，但也指出了在复杂室内环境及低光条件下的不足。可用性测试表明，73%的参与者能在一分钟内掌握应用程序的使用，而80%的参与者对其精度、快速响应及整体便捷性表示认可。

> Navigating unfamiliar places continues to be one of the most persistent and essential everyday obstacles for those who are blind or have limited vision (BLV). Existing assistive technologies, such as GPS-based navigation systems, AI-powered smart glasses, and sonar-equipped canes, often face limitations in real-time obstacle avoidance, precise localization, and adaptability to dynamic surroundings. To investigate potential solutions, we introduced PathFinder, a novel map-less navigation system that explores different models for understanding 2D images, including Vision Language Models (VLMs), Large Language Models (LLMs), and employs monocular depth estimation for free-path detection. Our approach integrates a Depth-First Search (DFS) algorithm on depth images to determine the longest obstacle-free path, ensuring optimal route selection while maintaining computational efficiency. We conducted comparative evaluations against existing AI-powered navigation methods and performed a usability study with BLV participants. The results demonstrate that PathFinder achieves a favorable balance between accuracy, computational efficiency, and real-time responsiveness. Notably, it reduces mean absolute error (MAE) and improves decision-making speed in outdoor navigation compared to AI-based alternatives. Participant feedback emphasizes the system's usability and effectiveness in outside situations, but also identifies issues in complicated indoor locations and low-light conditions. Usability testing revealed that 73% of participants understood how to use the app in about a minute, and 80% praised its balance of accuracy, quick response, and overall convenience.

[Arxiv](https://arxiv.org/abs/2504.20976)