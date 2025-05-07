# RobotxR1：通过闭环强化学习赋能大型语言模型的具身机器人智能

发布时间：2025年05月06日

`LLM应用` `机器人` `自动驾驶`

> RobotxR1: Enabling Embodied Robotic Intelligence on Large Language Models through Closed-Loop Reinforcement Learning

# 摘要

> 未来机器人系统要在现实环境中独立运行，必须具备车载具身智能，无需持续依赖云端，在有限的计算资源和内存条件下实现高效运作。本研究扩展了 R1-zero 方法，使其能够支持低参数量的大型语言模型（LLMs）在机器人领域的应用。最初，R1-Zero 方法专注于通过静态数据集实现大型语言模型的数学推理能力。我们将其与闭环强化学习（RL）框架相结合，成功扩展到机器人领域。这一扩展不仅增强了具身人工智能（Embodied AI）环境下的推理能力，还突破了传统监督微调（SFT）对大型模型的依赖。研究发现，小型 LLM 通过与环境的持续交互学习，能够实现高效的推理性能，完成此前需要更大模型才能完成的任务。在自动驾驶场景中，Qwen2.5-1.5B 模型的表现比基于 SFT 的基线提升了 20.2 个百分点。通过我们的训练方法，Qwen2.5-3B 达到了 63.3% 的控制适应性得分，显著超越了云端大型模型 GPT-4o 的 58.5%。这些成果表明，小型 LLM 的实际车载部署不仅可行，而且在通过环境反馈进行训练时，甚至能够超越更大模型的表现。这凸显了交互式学习框架在机器人具身智能中的重要性，其核心在于实践经验而非静态监督。

> Future robotic systems operating in real-world environments will require on-board embodied intelligence without continuous cloud connection, balancing capabilities with constraints on computational power and memory. This work presents an extension of the R1-zero approach, which enables the usage of low parameter-count Large Language Models (LLMs) in the robotic domain. The R1-Zero approach was originally developed to enable mathematical reasoning in LLMs using static datasets. We extend it to the robotics domain through integration in a closed-loop Reinforcement Learning (RL) framework. This extension enhances reasoning in Embodied Artificial Intelligence (Embodied AI) settings without relying solely on distillation of large models through Supervised Fine-Tuning (SFT). We show that small-scale LLMs can achieve effective reasoning performance by learning through closed-loop interaction with their environment, which enables tasks that previously required significantly larger models. In an autonomous driving setting, a performance gain of 20.2%-points over the SFT-based baseline is observed with a Qwen2.5-1.5B model. Using the proposed training procedure, Qwen2.5-3B achieves a 63.3% control adaptability score, surpassing the 58.5% obtained by the much larger, cloud-bound GPT-4o. These results highlight that practical, on-board deployment of small LLMs is not only feasible but can outperform larger models if trained through environmental feedback, underscoring the importance of an interactive learning framework for robotic Embodied AI, one grounded in practical experience rather than static supervision.

[Arxiv](https://arxiv.org/abs/2505.03238)