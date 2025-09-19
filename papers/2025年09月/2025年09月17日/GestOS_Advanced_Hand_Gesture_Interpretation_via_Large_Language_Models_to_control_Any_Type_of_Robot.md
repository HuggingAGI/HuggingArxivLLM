# GestOS：基于大型语言模型的高级手势解读技术——控制各类机器人

发布时间：2025年09月17日

`LLM应用` `工业与制造`

> GestOS: Advanced Hand Gesture Interpretation via Large Language Models to control Any Type of Robot

# 摘要

> 我们提出GestOS——一款基于手势的操作系统，专为异构机器人团队的高级控制设计。与现有系统将手势映射为固定命令或单智能体动作不同，GestOS对人手手势进行语义理解，并根据机器人的能力、当前状态及支持的指令集，在多机器人间动态分配任务。该系统融合了轻量级视觉感知与大型语言模型（LLM）推理：手部姿态被转化为结构化文本描述，LLM据此推断用户意图并生成机器人专属命令。机器人选择模块则确保每个手势触发的任务实时匹配至最优智能体。该架构实现了上下文感知的自适应控制，无需用户明确指定目标或命令。通过将手势交互从简单识别升级为智能编排，GestOS支持在动态环境中与机器人系统开展可扩展、灵活且易用的协作。

> We present GestOS, a gesture-based operating system for high-level control of heterogeneous robot teams. Unlike prior systems that map gestures to fixed commands or single-agent actions, GestOS interprets hand gestures semantically and dynamically distributes tasks across multiple robots based on their capabilities, current state, and supported instruction sets. The system combines lightweight visual perception with large language model (LLM) reasoning: hand poses are converted into structured textual descriptions, which the LLM uses to infer intent and generate robot-specific commands. A robot selection module ensures that each gesture-triggered task is matched to the most suitable agent in real time. This architecture enables context-aware, adaptive control without requiring explicit user specification of targets or commands. By advancing gesture interaction from recognition to intelligent orchestration, GestOS supports scalable, flexible, and user-friendly collaboration with robotic systems in dynamic environments.

[Arxiv](https://arxiv.org/abs/2509.14412)