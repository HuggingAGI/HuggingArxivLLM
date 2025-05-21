# 大型语言模型的结构化代理蒸馏

发布时间：2025年05月19日

`Agent` `人工智能` `决策系统`

> Structured Agent Distillation for Large Language Model

# 摘要

> 大型语言模型（LLMs）通过将推理与行动交织在一起，展现出强大的决策代理能力，这一点在ReAct-style框架中得到了充分体现。然而，高昂的推理成本和庞大的模型规模限制了它们的实际部署。为此，我们提出了一种名为“结构化代理蒸馏”的框架，该框架能够将大型LLM代理压缩为更小的学生模型，同时保留推理的准确性和行动的一致性。与传统的基于token级别的蒸馏方法不同，我们的方法将轨迹分割为{[REASON]}和{[ACT]}跨度，并应用特定于每个跨度的损失函数，以确保每个组件与教师模型的行为保持一致。这种基于结构的监督方式使紧凑型代理能够更好地复制教师模型的决策过程。实验结果表明，在ALFWorld、HotPotQA-ReAct和WebShop上，我们的方法在压缩模型的同时，性能下降极小，且在多个基准测试中表现优于传统的token级别和模仿学习方法。扩展性和消融实验进一步突显了基于跨度级别的对齐对于实现高效且易于部署的代理的重要性。


> Large language models (LLMs) exhibit strong capabilities as decision-making agents by interleaving reasoning and actions, as seen in ReAct-style frameworks. Yet, their practical deployment is constrained by high inference costs and large model sizes. We propose Structured Agent Distillation, a framework that compresses large LLM-based agents into smaller student models while preserving both reasoning fidelity and action consistency. Unlike standard token-level distillation, our method segments trajectories into {[REASON]} and {[ACT]} spans, applying segment-specific losses to align each component with the teacher's behavior. This structure-aware supervision enables compact agents to better replicate the teacher's decision process. Experiments on ALFWorld, HotPotQA-ReAct, and WebShop show that our approach consistently outperforms token-level and imitation learning baselines, achieving significant compression with minimal performance drop. Scaling and ablation results further highlight the importance of span-level alignment for efficient and deployable agents.

[Arxiv](https://arxiv.org/abs/2505.13820)