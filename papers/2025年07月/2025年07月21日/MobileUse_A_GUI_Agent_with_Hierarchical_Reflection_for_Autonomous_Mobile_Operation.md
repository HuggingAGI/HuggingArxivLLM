# MobileUse：一个用于智能移动设备自主操作的层次化反射GUI代理

发布时间：2025年07月21日

`Agent

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在移动代理中的应用，特别是针对移动设备上的复杂任务自动化。论文提出了一种名为MobileUse的图形界面代理，并详细介绍了其架构和解决方案，以应对实际移动场景中的挑战。虽然涉及LLM的应用，但核心内容集中在移动代理的设计、实现和性能上，因此更符合“Agent”分类。` `移动设备` `人工智能`

> MobileUse: A GUI Agent with Hierarchical Reflection for Autonomous Mobile Operation

# 摘要

> 多模态大型语言模型（MLLMs）的突破性进展推动了能够理解视觉输入并执行用户指令的移动代理的开发，为移动设备上的复杂任务自动化开辟了新路径。然而，实际移动场景中的应用仍面临三大挑战：长周期任务执行、错误恢复难度以及陌生环境中的冷启动问题。为解决这些难题，我们提出了MobileUse——一个专注于强健且自适应移动任务执行的图形界面（GUI）代理。

为提升在长周期任务和动态环境中的韧性，我们创新性地引入了分层反思架构。这一架构使代理能够在从单个动作到整体任务完成的多个时间尺度上实现自我监控、错误检测与恢复，同时通过按需反思策略保持高效运行。针对冷启动问题，我们还设计了一个主动探索模块，通过自我规划的探索方式，帮助代理更深入地理解环境。

在AndroidWorld和AndroidLab基准测试中，MobileUse展现了卓越的性能，分别取得了62.9%和44.2%的成功率，树立了新的最先进水平。为了推动实际应用，我们开源了MobileUse工具包，支持在物理移动设备上实现自动化任务执行，项目地址为https://github.com/MadeAgents/mobile-use。


> Recent advances in Multimodal Large Language Models (MLLMs) have enabled the development of mobile agents that can understand visual inputs and follow user instructions, unlocking new possibilities for automating complex tasks on mobile devices. However, applying these models to real-world mobile scenarios remains a significant challenge due to the long-horizon task execution, difficulty in error recovery, and the cold-start problem in unfamiliar environments. To address these challenges, we propose MobileUse, a GUI agent designed for robust and adaptive mobile task execution. To improve resilience in long-horizon tasks and dynamic environments, we introduce a hierarchical reflection architecture that enables the agent to self-monitor, detect, and recover from errors across multiple temporal scales-ranging from individual actions to overall task completion-while maintaining efficiency through a reflection-on-demand strategy. To tackle cold-start issues, we further introduce a proactive exploration module, which enriches the agent's understanding of the environment through self-planned exploration. Evaluations on AndroidWorld and AndroidLab benchmarks demonstrate that MobileUse establishes new state-of-the-art performance, achieving success rates of 62.9% and 44.2%, respectively. To facilitate real-world applications, we release an out-of-the-box toolkit for automated task execution on physical mobile devices, which is available at https://github.com/MadeAgents/mobile-use.

[Arxiv](https://arxiv.org/abs/2507.16853)