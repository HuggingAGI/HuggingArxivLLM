# 面向无人机的视觉-语言导航，具备开放词汇的目标识别能力

发布时间：2025年06月12日

`LLM应用` `自动驾驶机器人` `无人机`

> Grounded Vision-Language Navigation for UAVs with Open-Vocabulary Goal Understanding

# 摘要

> # 摘要  
视觉语言导航（VLN）是自动驾驶机器人领域的一项长期挑战，旨在让机器人能够理解并执行人类指令，同时在复杂环境中导航。然而，该领域目前仍面临两大关键瓶颈：对分布外环境的泛化能力不足，以及对固定离散动作空间的依赖。为了解决这些问题，我们提出了一种名为Vision-Language Fly（VLFly）的框架，专为无人机设计，用于执行语言引导的飞行任务。无需依赖定位或主动测距传感器，VLFly仅通过机载单目摄像头获取的 ego 视点观察结果，输出连续的 velocity 命令。VLFly 集成了三个模块：基于大型语言模型（LLM）的指令编码器，将高层语言转化为结构化提示；由视觉语言模型（VLM）驱动的目标检索器，通过视觉语言相似性将这些提示与目标图像匹配；以及一个航点规划器，为实时无人机控制生成可执行的轨迹。VLFly 在多种仿真环境中进行评估，无需额外微调，始终优于所有基线方法。此外，在室内和室外环境中，通过直接和间接指令进行的现实世界 VLN 任务表明，VLFly 实现了强大的开放词汇目标理解和泛化导航能力，即使面对抽象语言输入也是如此。


> Vision-and-language navigation (VLN) is a long-standing challenge in autonomous robotics, aiming to empower agents with the ability to follow human instructions while navigating complex environments. Two key bottlenecks remain in this field: generalization to out-of-distribution environments and reliance on fixed discrete action spaces. To address these challenges, we propose Vision-Language Fly (VLFly), a framework tailored for Unmanned Aerial Vehicles (UAVs) to execute language-guided flight. Without the requirement for localization or active ranging sensors, VLFly outputs continuous velocity commands purely from egocentric observations captured by an onboard monocular camera. The VLFly integrates three modules: an instruction encoder based on a large language model (LLM) that reformulates high-level language into structured prompts, a goal retriever powered by a vision-language model (VLM) that matches these prompts to goal images via vision-language similarity, and a waypoint planner that generates executable trajectories for real-time UAV control. VLFly is evaluated across diverse simulation environments without additional fine-tuning and consistently outperforms all baselines. Moreover, real-world VLN tasks in indoor and outdoor environments under direct and indirect instructions demonstrate that VLFly achieves robust open-vocabulary goal understanding and generalized navigation capabilities, even in the presence of abstract language input.

[Arxiv](https://arxiv.org/abs/2506.10756)