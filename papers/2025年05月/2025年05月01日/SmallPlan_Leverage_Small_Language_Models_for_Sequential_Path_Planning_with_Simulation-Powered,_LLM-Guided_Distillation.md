# SmallPlan：利用小型语言模型实现顺序路径规划，结合仿真驱动与LLM引导的蒸馏方法

发布时间：2025年05月01日

`LLM应用` `机器人` `自主机器人`

> SmallPlan: Leverage Small Language Models for Sequential Path Planning with Simulation-Powered, LLM-Guided Distillation

# 摘要

> 机器人领域的高效路径规划，特别是在大规模动态环境中，仍是重大挑战。大型语言模型（LLMs）虽然推理能力强，但其高计算成本和动态场景下的有限适应性限制了在边缘设备上的实时应用。我们提出了SmallPlan——一个创新框架，利用LLMs作为教师模型，训练轻量级小语言模型（SLMs）进行高级路径规划。在SmallPlan中，SLMs通过场景图提供最优动作序列，场景图紧凑表示完整规模的3D场景。SLMs采用模拟增强、LLM引导的监督微调（SFT）与强化学习（RL）相结合的方式训练。这不仅让SLMs成功完成导航任务，还使其能够感知旅行距离和尝试次数等关键因素。实验表明，微调后的SLMs在序列路径规划上可与GPT-4o等大型模型媲美，同时避免了幻觉和过拟合。SmallPlan资源高效，适合边缘设备部署，推动了实用自主机器人技术的发展。

> Efficient path planning in robotics, particularly within large-scale, dynamic environments, remains a significant hurdle. While Large Language Models (LLMs) offer strong reasoning capabilities, their high computational cost and limited adaptability in dynamic scenarios hinder real-time deployment on edge devices. We present SmallPlan -- a novel framework leveraging LLMs as teacher models to train lightweight Small Language Models (SLMs) for high-level path planning tasks. In SmallPlan, the SLMs provide optimal action sequences to navigate across scene graphs that compactly represent full-scaled 3D scenes. The SLMs are trained in a simulation-powered, interleaved manner with LLM-guided supervised fine-tuning (SFT) and reinforcement learning (RL). This strategy not only enables SLMs to successfully complete navigation tasks but also makes them aware of important factors like travel distance and number of trials. Through experiments, we demonstrate that the fine-tuned SLMs perform competitively with larger models like GPT-4o on sequential path planning, without suffering from hallucination and overfitting. SmallPlan is resource-efficient, making it well-suited for edge-device deployment and advancing practical autonomous robotics.

[Arxiv](https://arxiv.org/abs/2505.00831)