# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月13日

`Agent` `机器人` `人工智能`

> SmartWay: Enhanced Waypoint Prediction and Backtracking for Zero-Shot Vision-and-Language Navigation

# 摘要

> 视觉语言导航（VLN）要求智能体在连续环境中同时理解自然语言指令并自由导航于3D空间。现有VLN-CE框架采用两阶段方法：路径点预测器生成导航点，导航器执行移动。然而，现有预测器在空间感知上存在局限，导航器缺乏历史推理和回溯能力，限制了其适应性。我们提出了一种零样本VLN-CE框架，整合增强路径点预测器与基于多模态大语言模型（MLLM）的导航器。我们的预测器采用更强的视觉编码器、掩码交叉注意力融合和占用感知损失，提升路径点质量。导航器则结合历史感知推理和自适应路径规划与回溯功能，增强鲁棒性。在R2R-CE和MP3D基准上的实验显示，我们的方法在零样本设置下达到最先进的（SOTA）性能，并与完全监督方法相比展现出竞争力。在Turtlebot 4上的实际验证进一步凸显了其适应性。

> Vision-and-Language Navigation (VLN) in continuous environments requires agents to interpret natural language instructions while navigating unconstrained 3D spaces. Existing VLN-CE frameworks rely on a two-stage approach: a waypoint predictor to generate waypoints and a navigator to execute movements. However, current waypoint predictors struggle with spatial awareness, while navigators lack historical reasoning and backtracking capabilities, limiting adaptability. We propose a zero-shot VLN-CE framework integrating an enhanced waypoint predictor with a Multi-modal Large Language Model (MLLM)-based navigator. Our predictor employs a stronger vision encoder, masked cross-attention fusion, and an occupancy-aware loss for better waypoint quality. The navigator incorporates history-aware reasoning and adaptive path planning with backtracking, improving robustness. Experiments on R2R-CE and MP3D benchmarks show our method achieves state-of-the-art (SOTA) performance in zero-shot settings, demonstrating competitive results compared to fully supervised methods. Real-world validation on Turtlebot 4 further highlights its adaptability.

[Arxiv](https://arxiv.org/abs/2503.10069)