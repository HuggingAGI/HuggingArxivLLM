# TypeTele：通过灵巧操作类型，释放远程操作的灵巧性。

发布时间：2025年07月02日

`LLM应用` `机器人技术` `自动化`

> TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types

# 摘要

> 灵巧遥操作在机器人操控中扮演着关键角色，特别是在真实世界的数据收集和远程机器人控制方面。传统的方法主要依赖于手部姿态重映射来模仿人类手部姿势，但这种方法可能未能充分发挥灵巧机械手的结构优势，因为这些机械手相较于人类手部具有执行独特动作的结构优势。为了克服这一局限性，我们提出了TypeTele，这是一种基于类型引导的灵巧遥操作系统，使灵巧机械手能够执行不受人类运动模式限制的动作。通过将灵巧操作类型引入遥操作系统，操作员可以选用合适类型来完成特定任务。为了支持这一系统，我们构建了一个可扩展的灵巧操作类型库，涵盖了用于操作任务的综合灵巧姿势。在遥操作过程中，我们采用多模态大型语言模型（MLLM）辅助的类型检索模块，根据具体任务和操作员指令识别最合适的操作类型。大量真实世界遥操作和模仿学习实验表明，引入操作类型显著提升了灵巧机器人在多样复杂任务中的成功率，充分发挥了其能力。

> Dexterous teleoperation plays a crucial role in robotic manipulation for real-world data collection and remote robot control. Previous dexterous teleoperation mostly relies on hand retargeting to closely mimic human hand postures. However, these approaches may fail to fully leverage the inherent dexterity of dexterous hands, which can execute unique actions through their structural advantages compared to human hands. To address this limitation, we propose TypeTele, a type-guided dexterous teleoperation system, which enables dexterous hands to perform actions that are not constrained by human motion patterns. This is achieved by introducing dexterous manipulation types into the teleoperation system, allowing operators to employ appropriate types to complete specific tasks. To support this system, we build an extensible dexterous manipulation type library to cover comprehensive dexterous postures used in manipulation tasks. During teleoperation, we employ a MLLM (Multi-modality Large Language Model)-assisted type retrieval module to identify the most suitable manipulation type based on the specific task and operator commands. Extensive experiments of real-world teleoperation and imitation learning demonstrate that the incorporation of manipulation types significantly takes full advantage of the dexterous robot's ability to perform diverse and complex tasks with higher success rates.

[Arxiv](https://arxiv.org/abs/2507.01857)