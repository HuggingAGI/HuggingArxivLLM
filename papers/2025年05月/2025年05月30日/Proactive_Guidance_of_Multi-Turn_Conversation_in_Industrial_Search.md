# # 工业搜索中多轮对话的主动引导策略

发布时间：2025年05月30日

`LLM应用` `搜索引擎` `对话系统`

> Proactive Guidance of Multi-Turn Conversation in Industrial Search

# 摘要

> 大型语言模型（LLMs）的演进为多轮对话系统带来了显著提升，特别是在主动引导以增强用户体验方面。然而，这些系统在动态适应用户目标变化和保持实时交互低延迟方面仍面临挑战。针对百度搜索AI助手这一工业级多轮搜索系统，我们提出了一种创新的两阶段框架，以实现高效的主动引导。首先，目标自适应监督微调（G-SFT）通过动态适应用户目标变化，提供相关的上下文信息，并结合知识迁移，将LLMs的洞察力提炼到轻量级模型中，从而实现快速响应。其次，点击导向强化学习（C-RL）通过生成-排序范式，从用户点击信号中构建偏好对，主动优化点击率。这种双管齐下的架构相辅相成：G-SFT确保精准的目标跟踪，而C-RL则通过点击驱动的强化学习提升交互质量。实验结果表明，我们的框架在离线评估中准确率达到86.10%（较基线提升23.95%），在线部署中点击率达到25.28%（相对提升149.06%），同时通过知识蒸馏将延迟降低了69.55%。

> The evolution of Large Language Models (LLMs) has significantly advanced multi-turn conversation systems, emphasizing the need for proactive guidance to enhance users' interactions. However, these systems face challenges in dynamically adapting to shifts in users' goals and maintaining low latency for real-time interactions. In the Baidu Search AI assistant, an industrial-scale multi-turn search system, we propose a novel two-phase framework to provide proactive guidance. The first phase, Goal-adaptive Supervised Fine-Tuning (G-SFT), employs a goal adaptation agent that dynamically adapts to user goal shifts and provides goal-relevant contextual information. G-SFT also incorporates scalable knowledge transfer to distill insights from LLMs into a lightweight model for real-time interaction. The second phase, Click-oriented Reinforcement Learning (C-RL), adopts a generate-rank paradigm, systematically constructs preference pairs from user click signals, and proactively improves click-through rates through more engaging guidance. This dual-phase architecture achieves complementary objectives: G-SFT ensures accurate goal tracking, while C-RL optimizes interaction quality through click signal-driven reinforcement learning. Extensive experiments demonstrate that our framework achieves 86.10% accuracy in offline evaluation (+23.95% over baseline) and 25.28% CTR in online deployment (149.06% relative improvement), while reducing inference latency by 69.55% through scalable knowledge distillation.

[Arxiv](https://arxiv.org/abs/2505.24251)