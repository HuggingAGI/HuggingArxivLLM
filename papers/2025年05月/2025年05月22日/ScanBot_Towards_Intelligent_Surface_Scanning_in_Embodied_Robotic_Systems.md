# ScanBot：实现具身机器人系统中的智能表面扫描

发布时间：2025年05月22日

`LLM应用` `机器人技术`

> ScanBot: Towards Intelligent Surface Scanning in Embodied Robotic Systems

# 摘要

> 我们很高兴推出 ScanBot，一个专为机器人系统中基于指令的高精度表面扫描设计的全新数据集。与现有专注于抓取、导航或对话等粗粒度任务的机器人学习数据集不同，ScanBot 瞄准了工业激光扫描的高精度需求，其中亚毫米级的路径连续性和参数稳定性至关重要。该数据集收录了机器人在 12 种不同对象和 6 种任务类型上的激光扫描轨迹，包括全表面扫描、几何聚焦区域、空间参考部件、功能相关结构、缺陷检测和比较分析。每个扫描均由自然语言指令引导，并与同步的 RGB、深度和激光轮廓、机器人姿态和关节状态数据配对。尽管近期技术有所进步，现有的视觉语言动作 (VLA) 模型仍难以在精细指令和现实世界精度要求下生成稳定的扫描轨迹。为探究这一局限，我们对多种多模态大型语言模型 (MLLMs) 进行了全面基准测试，覆盖完整的感知-规划-执行循环，揭示了在现实约束下遵循指令的持续挑战。

> We introduce ScanBot, a novel dataset designed for instruction-conditioned, high-precision surface scanning in robotic systems. In contrast to existing robot learning datasets that focus on coarse tasks such as grasping, navigation, or dialogue, ScanBot targets the high-precision demands of industrial laser scanning, where sub-millimeter path continuity and parameter stability are critical. The dataset covers laser scanning trajectories executed by a robot across 12 diverse objects and 6 task types, including full-surface scans, geometry-focused regions, spatially referenced parts, functionally relevant structures, defect inspection, and comparative analysis. Each scan is guided by natural language instructions and paired with synchronized RGB, depth, and laser profiles, as well as robot pose and joint states. Despite recent progress, existing vision-language action (VLA) models still fail to generate stable scanning trajectories under fine-grained instructions and real-world precision demands. To investigate this limitation, we benchmark a range of multimodal large language models (MLLMs) across the full perception-planning-execution loop, revealing persistent challenges in instruction-following under realistic constraints.

[Arxiv](https://arxiv.org/abs/2505.17295)