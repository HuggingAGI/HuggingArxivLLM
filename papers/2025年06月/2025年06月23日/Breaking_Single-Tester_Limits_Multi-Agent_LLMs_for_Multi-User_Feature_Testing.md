# 打破单点测试限制：多智能体大语言模型赋能多用户场景下的功能测试

发布时间：2025年06月23日

`Agent

理由：这篇论文提出了一种基于大型语言模型的多智能体方法，用于实现多用户互动功能的自动化测试。论文的核心在于多智能体系统的设计与应用，而非深入探讨大型语言模型本身的理论或应用。因此，它更符合Agent类别。` `移动应用` `软件开发`

> Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing

# 摘要

> 移动设备的普及和应用依赖使得多用户互动功能（如语音通话、直播和视频会议）成为弥合社交连接缺口的重要手段。然而，现有自动化测试方法难以有效应对这些功能对及时、动态和协作性交互的高要求。为此，我们提出了一种基于大型语言模型（LLMs）的多智能体方法MAdroid，旨在实现应用功能测试中的多用户互动任务自动化。MAdroid采用了三种角色分明的智能体：Coordinator负责指挥任务，Operator模拟用户操作，Observer则全程监控和评估自动化过程。实验结果表明，MAdroid在41项测试任务中实现了82.9%的完成率和96.8%的动作相似度，显著优于对照组和现有最优方案。此外，MAdroid在实际应用中表现出色，帮助发现11项多用户互动功能缺陷，充分证明了其在现实软件开发中的应用价值。

> The growing dependence on mobile phones and their apps has made multi-user interactive features, like chat calls, live streaming, and video conferencing, indispensable for bridging the gaps in social connectivity caused by physical and situational barriers. However, automating these interactive features for testing is fraught with challenges, owing to their inherent need for timely, dynamic, and collaborative user interactions, which current automated testing methods inadequately address. Inspired by the concept of agents designed to autonomously and collaboratively tackle problems, we propose MAdroid, a novel multi-agent approach powered by the Large Language Models (LLMs) to automate the multi-user interactive task for app feature testing. Specifically, MAdroid employs two functional types of multi-agents: user agents (Operator) and supervisor agents (Coordinator and Observer). Each agent takes a specific role: the Coordinator directs the interactive task; the Operator mimics user interactions on the device; and the Observer monitors and reviews the task automation process. Our evaluation, which included 41 multi-user interactive tasks, demonstrates the effectiveness of our approach, achieving 82.9% of the tasks with 96.8% action similarity, outperforming the ablation studies and state-of-the-art baselines. Additionally, a preliminary investigation underscores MAdroid's practicality by helping identify 11 multi-user interactive bugs during regression app testing, confirming its potential value in real-world software development contexts.

[Arxiv](https://arxiv.org/abs/2506.17539)