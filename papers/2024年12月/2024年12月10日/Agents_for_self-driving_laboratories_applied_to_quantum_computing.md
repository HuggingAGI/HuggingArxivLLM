# 自动驾驶实验室的代理在量子计算中的应用

发布时间：2024年12月10日

`Agent` `自动驾驶` `科学实验`

> Agents for self-driving laboratories applied to quantum computing

# 摘要

> 全自动化的自动驾驶实验室有望通过减少重复劳动，实现高通量、大规模的科学发现。然而，有效的自动化需要深度整合实验室知识，这些知识通常是非结构化、多模态的，难以融入当下的人工智能系统。本文引入了 k-agents 框架，旨在助力实验人员整理实验室知识，并通过代理实现实验自动化。我们的框架借助基于大型语言模型的代理来封装实验室知识，涵盖可用的实验室操作以及分析实验结果的方法。为实现实验自动化，我们引入执行代理，将多步骤实验流程拆解为状态机，与其他代理交互来执行每一步骤并分析实验结果。随后，分析得出的结果用于驱动状态转换，达成闭环反馈控制。为展示其能力，我们将这些代理应用于超导量子处理器的校准和操作，它们自主规划并执行实验数小时，成功生成并表征了纠缠量子态，达到了人类科学家的水平。我们基于知识的代理系统为管理实验室知识、加速科学发现开创了新的可能。

> Fully automated self-driving laboratories are promising to enable high-throughput and large-scale scientific discovery by reducing repetitive labour. However, effective automation requires deep integration of laboratory knowledge, which is often unstructured, multimodal, and difficult to incorporate into current AI systems. This paper introduces the k-agents framework, designed to support experimentalists in organizing laboratory knowledge and automating experiments with agents. Our framework employs large language model-based agents to encapsulate laboratory knowledge including available laboratory operations and methods for analyzing experiment results. To automate experiments, we introduce execution agents that break multi-step experimental procedures into state machines, interact with other agents to execute each step and analyze the experiment results. The analyzed results are then utilized to drive state transitions, enabling closed-loop feedback control. To demonstrate its capabilities, we applied the agents to calibrate and operate a superconducting quantum processor, where they autonomously planned and executed experiments for hours, successfully producing and characterizing entangled quantum states at the level achieved by human scientists. Our knowledge-based agent system opens up new possibilities for managing laboratory knowledge and accelerating scientific discovery.

[Arxiv](https://arxiv.org/abs/2412.07978)