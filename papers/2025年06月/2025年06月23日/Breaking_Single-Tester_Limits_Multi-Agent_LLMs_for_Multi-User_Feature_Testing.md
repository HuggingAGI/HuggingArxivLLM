# # 突破单人测试局限：多智能体大语言模型助力多用户功能测试

发布时间：2025年06月23日

`Agent` `软件开发` `自动化测试`

> Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing

# 摘要

> 随着移动设备及应用的普及，多用户互动功能（如聊天通话、直播和视频会议）已成为跨越物理和情境障碍、维系社交连接的重要工具。然而，由于这些功能需要及时、动态且协作的用户互动，现有自动化测试方法难以满足这一需求，因此对这些互动功能进行自动化测试面临诸多挑战。受自主协作解决问题的智能体概念启发，我们提出了一种基于大型语言模型（LLMs）的新型多智能体方法——MAdroid，用于自动化应用功能测试中的多用户互动任务。具体而言，MAdroid采用了两种功能类型的多智能体：用户智能体（Operator）和监督智能体（Coordinator和Observer）。每个智能体承担特定角色：协调器负责指导互动任务；操作员在设备上模拟用户互动；观察员负责监控和审查任务自动化过程。我们的评估涵盖了41项多用户互动任务，结果证明了我们方法的有效性，成功完成82.9%的任务，且动作相似度高达96.8%，优于消融研究和现有最优基线。此外，初步调查通过在回归应用测试中帮助识别11个与多用户互动相关的故障，凸显了MAdroid的实际应用价值，证实了其在现实世界软件开发环境中的潜在价值。

> The growing dependence on mobile phones and their apps has made multi-user interactive features, like chat calls, live streaming, and video conferencing, indispensable for bridging the gaps in social connectivity caused by physical and situational barriers. However, automating these interactive features for testing is fraught with challenges, owing to their inherent need for timely, dynamic, and collaborative user interactions, which current automated testing methods inadequately address. Inspired by the concept of agents designed to autonomously and collaboratively tackle problems, we propose MAdroid, a novel multi-agent approach powered by the Large Language Models (LLMs) to automate the multi-user interactive task for app feature testing. Specifically, MAdroid employs two functional types of multi-agents: user agents (Operator) and supervisor agents (Coordinator and Observer). Each agent takes a specific role: the Coordinator directs the interactive task; the Operator mimics user interactions on the device; and the Observer monitors and reviews the task automation process. Our evaluation, which included 41 multi-user interactive tasks, demonstrates the effectiveness of our approach, achieving 82.9% of the tasks with 96.8% action similarity, outperforming the ablation studies and state-of-the-art baselines. Additionally, a preliminary investigation underscores MAdroid's practicality by helping identify 11 multi-user interactive bugs during regression app testing, confirming its potential value in real-world software development contexts.

[Arxiv](https://arxiv.org/abs/2506.17539)