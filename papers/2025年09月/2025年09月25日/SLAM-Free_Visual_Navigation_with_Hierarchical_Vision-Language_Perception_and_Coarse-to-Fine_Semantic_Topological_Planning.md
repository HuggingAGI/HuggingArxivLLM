# 无SLAM视觉导航：采用分层视觉-语言感知与粗到精语义拓扑规划

发布时间：2025年09月25日

`Agent` `工业与制造`

> SLAM-Free Visual Navigation with Hierarchical Vision-Language Perception and Coarse-to-Fine Semantic Topological Planning

# 摘要

> 传统腿式机器人导航的SLAM流程在快速运动、校准要求和传感器漂移时稳定性较差，且在任务驱动探索中语义推理能力有限。针对这些问题，我们提出一种纯视觉、无SLAM的导航框架，用语义推理和轻量级拓扑表示取代密集几何信息。该框架包含层次化视觉-语言感知模块，融合场景级上下文与目标级线索实现鲁棒语义推理；同时构建语义-概率拓扑图支持由粗到细规划：基于LLM的全局推理用于子目标选择，基于视觉的局部规划用于避障。结合强化学习运动控制器后，该框架可部署于多种腿式机器人平台。仿真与真实环境实验表明，其在语义准确性、规划质量和导航成功率上均有稳定提升；消融实验进一步验证了层次化感知与精细局部规划的必要性。这项工作开创了无SLAM、视觉-语言驱动导航的新范式，推动机器人探索从几何中心的建图转向语义驱动的决策。

> Conventional SLAM pipelines for legged robot navigation are fragile under rapid motion, calibration demands, and sensor drift, while offering limited semantic reasoning for task-driven exploration. To deal with these issues, we propose a vision-only, SLAM-free navigation framework that replaces dense geometry with semantic reasoning and lightweight topological representations. A hierarchical vision-language perception module fuses scene-level context with object-level cues for robust semantic inference. And a semantic-probabilistic topological map supports coarse-to-fine planning: LLM-based global reasoning for subgoal selection and vision-based local planning for obstacle avoidance. Integrated with reinforcement-learning locomotion controllers, the framework is deployable across diverse legged robot platforms. Experiments in simulation and real-world settings demonstrate consistent improvements in semantic accuracy, planning quality, and navigation success, while ablation studies further showcase the necessity of both hierarchical perception and fine local planning. This work introduces a new paradigm for SLAM-free, vision-language-driven navigation, shifting robotic exploration from geometry-centric mapping to semantics-driven decision making.

[Arxiv](https://arxiv.org/abs/2509.20739)