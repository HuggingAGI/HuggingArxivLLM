# RoBridge：连接认知与执行的通用机器人操作分层架构

发布时间：2025年05月03日

`Agent` `机器人学` `通用机器人操作`

> RoBridge: A Hierarchical Architecture Bridging Cognition and Execution for General Robotic Manipulation

# 摘要

> 在开放且任务多样化的场景中操作机器人，是机器人学中至关重要的研究与应用方向。尽管自然语言处理和大规模多模态模型的最新进展增强了机器人理解复杂指令的能力，但在开放环境中，机器人操作仍然面临程序性技能和陈述性技能的双重挑战。现有方法往往需要在认知能力和执行能力之间做出妥协。

为了解决这些挑战，本文提出了一种名为RoBridge的分层智能架构，用于通用机器人操作。该架构由三个核心组件构成：基于大规模预训练视觉语言模型（VLM）的高层认知规划器（HCP）、作为符号桥梁的不变可操作表示（IOR），以及通用具身智能体（GEA）。RoBridge既保留了VLM的陈述性技能，又释放了强化学习的程序性技能潜力，有效弥合了认知与执行之间的鸿沟。

实验结果表明，与现有基线方法相比，RoBridge在性能上实现了显著提升。在新任务中，RoBridge达到了75%的成功率，并在仅使用每个任务五个真实世界数据样本的情况下，实现了83%的平均成功率，充分验证了其在模拟到现实迁移中的有效性。这项研究为机器人系统中认知推理与物理执行的融合迈出了重要一步，为通用机器人操作提供了一种全新的范式。

> Operating robots in open-ended scenarios with diverse tasks is a crucial research and application direction in robotics. While recent progress in natural language processing and large multimodal models has enhanced robots' ability to understand complex instructions, robot manipulation still faces the procedural skill dilemma and the declarative skill dilemma in open environments. Existing methods often compromise cognitive and executive capabilities. To address these challenges, in this paper, we propose RoBridge, a hierarchical intelligent architecture for general robotic manipulation. It consists of a high-level cognitive planner (HCP) based on a large-scale pre-trained vision-language model (VLM), an invariant operable representation (IOR) serving as a symbolic bridge, and a generalist embodied agent (GEA). RoBridge maintains the declarative skill of VLM and unleashes the procedural skill of reinforcement learning, effectively bridging the gap between cognition and execution. RoBridge demonstrates significant performance improvements over existing baselines, achieving a 75% success rate on new tasks and an 83% average success rate in sim-to-real generalization using only five real-world data samples per task. This work represents a significant step towards integrating cognitive reasoning with physical execution in robotic systems, offering a new paradigm for general robotic manipulation.

[Arxiv](https://arxiv.org/abs/2505.01709)