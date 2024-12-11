# 自适应通信支持对人类与 AI 协作的作用

发布时间：2024年11月25日

`Agent` `人机协作` `团队协作`

> Effect of Adaptive Communication Support on Human-AI Collaboration

# 摘要

> 有效的人类与 AI 协作，需要代理依据人类需求、任务要求及复杂程度来确定自身角色和支持程度。传统的人类与 AI 团队合作往往依赖预先设定的机器人通信方案，这限制了在复杂任务中的团队适应性。借助大型语言模型（LLMs）强大的通信能力，我们提出了具有多模态语言反馈的人机团队框架（HRT-ML），旨在通过调整语言反馈的频率和内容来增强人机交互。HRT-ML 框架包含两个核心模块：负责高级、低频战略指导的协调员，以及针对特定任务、高频指令的管理器，实现与人类队友的被动和主动交互。为评估协作场景中语言反馈的影响，我们在增强版的 Overcooked-AI 游戏环境中开展实验，设置了不同的任务复杂度（简单、中等、困难）和反馈频率（不活跃、被动、主动、超活跃）。结果显示，随着任务复杂度相对于人类能力的提升，人类队友更倾向于能提供频繁、主动支持的机器人代理。然而，当任务复杂度超出 LLM 的能力时，来自超活跃代理的嘈杂且不准确的反馈反而会阻碍团队表现，因为这需要人类队友花费更多精力去理解和回应大量通信，而获得的性能提升却有限。我们的研究结果为机器人代理提供了一个通用原则，即动态调整其通信水平和频率，以便与人类无缝协作，实现更优的团队表现。

> Effective human-AI collaboration requires agents to adopt their roles and levels of support based on human needs, task requirements, and complexity. Traditional human-AI teaming often relies on a pre-determined robot communication scheme, restricting teamwork adaptability in complex tasks. Leveraging the strong communication capabilities of Large Language Models (LLMs), we propose a Human-Robot Teaming Framework with Multi-Modal Language feedback (HRT-ML), a framework designed to enhance human-robot interaction by adjusting the frequency and content of language-based feedback. The HRT-ML framework includes two core modules: a Coordinator for high-level, low-frequency strategic guidance and a Manager for task-specific, high-frequency instructions, enabling passive and active interactions with human teammates. To assess the impact of language feedback in collaborative scenarios, we conducted experiments in an enhanced Overcooked-AI game environment with varying levels of task complexity (easy, medium, hard) and feedback frequency (inactive, passive, active, superactive). Our results show that as task complexity increases relative to human capabilities, human teammates exhibited stronger preferences toward robotic agents that can offer frequent, proactive support. However, when task complexities exceed the LLM's capacity, noisy and inaccurate feedback from superactive agents can instead hinder team performance, as it requires human teammates to increase their effort to interpret and respond to the large amount of communications, with limited performance return. Our results offer a general principle for robotic agents to dynamically adjust their levels and frequencies of communication to work seamlessly with humans and achieve improved teaming performance.

[Arxiv](https://arxiv.org/abs/2412.06808)