# HyCodePolicy：面向具身智能体多模态监控与决策的混合语言控制器

发布时间：2025年08月04日

`Agent` `机器人` `机器人自主决策`

> HyCodePolicy: Hybrid Language Controllers for Multimodal Monitoring and Decision in Embodied Agents

# 摘要

> 近期，多模态大型语言模型（MLLMs）的进展为具身智能体的代码策略生成提供了更丰富的感知基础。然而，现有系统在任务执行过程中缺乏有效的机制来动态监控策略执行并修复代码。在本研究中，我们引入了HyCodePolicy，这是一个混合语言控制框架，系统地将代码合成、几何定位、感知监控和迭代修复整合到具身智能体的闭环编程循环中。

从技术角度来看，给定一个自然语言指令，我们的系统首先将其分解为子目标，并生成一个基于以对象为中心的几何原语的初始可执行程序。然后在模拟环境中执行该程序，同时视觉语言模型（VLM）观察选定的检查点以检测和定位执行失败并推断失败原因。通过将捕获程序级事件的结构化执行轨迹与基于VLM的感知反馈相结合，HyCodePolicy推断出失败原因并修复程序。这种混合双反馈机制使得在最少的人为监督下实现自我修正的程序合成成为可能。

我们的实验结果表明，HyCodePolicy显著提高了机器人操作策略的鲁棒性和采样效率，为将多模态推理整合到自主决策流水线中提供了一种可扩展的策略。

> Recent advances in multimodal large language models (MLLMs) have enabled richer perceptual grounding for code policy generation in embodied agents. However, most existing systems lack effective mechanisms to adaptively monitor policy execution and repair codes during task completion. In this work, we introduce HyCodePolicy, a hybrid language-based control framework that systematically integrates code synthesis, geometric grounding, perceptual monitoring, and iterative repair into a closed-loop programming cycle for embodied agents. Technically, given a natural language instruction, our system first decomposes it into subgoals and generates an initial executable program grounded in object-centric geometric primitives. The program is then executed in simulation, while a vision-language model (VLM) observes selected checkpoints to detect and localize execution failures and infer failure reasons. By fusing structured execution traces capturing program-level events with VLM-based perceptual feedback, HyCodePolicy infers failure causes and repairs programs. This hybrid dual feedback mechanism enables self-correcting program synthesis with minimal human supervision. Our results demonstrate that HyCodePolicy significantly improves the robustness and sample efficiency of robot manipulation policies, offering a scalable strategy for integrating multimodal reasoning into autonomous decision-making pipelines.

[Arxiv](https://arxiv.org/abs/2508.02629)