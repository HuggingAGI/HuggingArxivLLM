# 衡量具身智能体在协作场景中的实时适应与通信能力

发布时间：2024年11月30日

`Agent` `人工智能` `人机交互`

> Benchmark Real-time Adaptation and Communication Capabilities of Embodied Agent in Collaborative Scenarios

# 摘要

> 大型语言模型（LLMs）的进步为人类与机器人的交互带来了变革性机遇，尤其在协作场景中。然而，实时的人类 - 人工智能协作要求智能体适应未曾见过的人类行为，同时动态保持有效沟通。现有的基准在评估具身智能体的此类适应性方面存在不足，多聚焦于智能体自身的任务表现。为弥补这一差距，我们提出了一种全新的基准，用于评估智能体每一步的反应适应能力和瞬时通信能力。基于此基准，我们提出了监控然后适应框架（MonTA），将强大的适应能力和通信与实时执行相融合。MonTA 包含三个关键的 LLM 模块，一个轻量级的【监控器】用于高频监测适应需求，还有两个熟练的【适配器】用于低频的子任务和路径适应推理。我们的结果显示，在我们提出的基准上，MonTA 优于其他基线智能体。进一步的用户研究证实了我们框架提供的高度合理的适应计划和一致的语言指令。

> Advancements in Large Language Models (LLMs) have opened transformative possibilities for human-robot interaction, especially in collaborative environments. However, Real-time human-AI collaboration requires agents to adapt to unseen human behaviors while maintaining effective communication dynamically. Existing benchmarks fall short in evaluating such adaptability for embodied agents, focusing mostly on the task performance of the agent itself. To address this gap, we propose a novel benchmark that assesses agents' reactive adaptability and instantaneous communication capabilities at every step. Based on this benchmark, we propose a Monitor-then-Adapt framework (MonTA), combining strong adaptability and communication with real-time execution. MonTA contains three key LLM modules, a lightweight \textit{Monitor} for monitoring the need for adaptation in high frequency, and two proficient \textit{Adapters} for subtask and path adaptation reasoning in low frequency. Our results demonstrate that MonTA outperforms other baseline agents on our proposed benchmark. Further user studies confirm the high reasonability adaptation plan and consistent language instruction provided by our framework.

[Arxiv](https://arxiv.org/abs/2412.00435)