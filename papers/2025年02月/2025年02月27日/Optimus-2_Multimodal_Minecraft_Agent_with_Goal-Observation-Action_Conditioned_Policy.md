# Optimus-2：目标-观察-动作条件策略驱动的多模态Minecraft代理

发布时间：2025年02月27日

`Agent

理由：这篇论文主要关注构建能够模仿人类行为模式以完成各种开放世界任务的智能体。它提出了一个结合多模态大型语言模型和基于目标-观察-行动条件的策略（GOAP）的智能体架构，展示了其在Minecraft中的应用。尽管涉及大型语言模型，但核心内容是智能体的设计和实现，因此归类为Agent。` `人工智能`

> Optimus-2: Multimodal Minecraft Agent with Goal-Observation-Action Conditioned Policy

# 摘要

> 构建能够模仿人类行为模式以完成各种开放世界任务的智能体，是一个长期目标。为了使智能体有效学习跨多种任务的行为模式，关键在于建模观察、行动和语言间的复杂关系。为此，我们提出了Optimus-2——一个新型Minecraft智能体，它结合多模态大型语言模型（MLLM）进行高层次规划，以及基于目标-观察-行动条件的策略（GOAP）实现低层次控制。GOAP包含两个部分：（1）一个行为引导编码器，用于建模观察与行动在每个时间步的因果关系，并与历史观察-行动序列动态交互，整合为固定长度的行为令牌；（2）一个多模态大型语言模型，将行为令牌与开放式语言指令对齐，以自回归方式预测行动。此外，我们引入了一个高质量的Minecraft目标-观察-行动（MGOA）数据集，包含8个原子任务的25,000个视频，提供约3000万个目标-观察-行动对。自动化构建方法与MGOA数据集的结合，为训练Minecraft智能体的社区工作提供了助力。大量实验结果表明，Optimus-2在Minecraft中的原子任务、长时任务和开放式指令任务中均表现出色。

> Building an agent that can mimic human behavior patterns to accomplish various open-world tasks is a long-term goal. To enable agents to effectively learn behavioral patterns across diverse tasks, a key challenge lies in modeling the intricate relationships among observations, actions, and language. To this end, we propose Optimus-2, a novel Minecraft agent that incorporates a Multimodal Large Language Model (MLLM) for high-level planning, alongside a Goal-Observation-Action Conditioned Policy (GOAP) for low-level control. GOAP contains (1) an Action-guided Behavior Encoder that models causal relationships between observations and actions at each timestep, then dynamically interacts with the historical observation-action sequence, consolidating it into fixed-length behavior tokens, and (2) an MLLM that aligns behavior tokens with open-ended language instructions to predict actions auto-regressively. Moreover, we introduce a high-quality Minecraft Goal-Observation-Action (MGOA)} dataset, which contains 25,000 videos across 8 atomic tasks, providing about 30M goal-observation-action pairs. The automated construction method, along with the MGOA dataset, can contribute to the community's efforts to train Minecraft agents. Extensive experimental results demonstrate that Optimus-2 exhibits superior performance across atomic tasks, long-horizon tasks, and open-ended instruction tasks in Minecraft.

[Arxiv](https://arxiv.org/abs/2502.19902)