# Ask-to-Clarify：多轮对话消解指令歧义

发布时间：2025年09月18日

`Agent` `基础理论`

> Ask-to-Clarify: Resolving Instruction Ambiguity through Multi-turn Dialogue

# 摘要

> 具身智能体的终极目标是成为能与人类互动的协作者，而非只会被动执行指令的工具。这需要智能体具备基于人类反馈进行沟通、协作与行动调整的能力。近年来，视觉语言智能体（VLAs）的发展为实现这一目标指明了方向。但目前多数基于VLA的具身智能体仍采用单向模式：接收指令后直接执行，缺乏反馈机制。在指令常含歧义的真实场景中，这种模式难以奏效。为此，本文提出“询问澄清”（Ask-to-Clarify）框架以应对这一挑战。该框架先通过多轮对话提问澄清模糊指令，再端到端生成具体动作。具体来说，“询问澄清”框架包含两个核心组件：负责协作的视觉语言模型（VLM）与生成动作的扩散模型。我们还设计了连接模块，根据VLM的输出为扩散模型生成条件——该模块通过指令校准观察信息，生成可靠的条件约束。训练阶段采用两阶段知识隔离策略：第一阶段，利用歧义消解对话数据微调协作组件，使其具备处理模糊指令的能力；第二阶段，冻结协作组件并集成动作组件，在保留交互能力的同时微调扩散模型以生成动作。这种训练策略确保框架能先完成提问，再执行动作生成。推理时，信号检测器作为路由机制，引导框架在提问与动作执行间灵活切换。我们在8项现实任务中对“询问澄清”框架进行评估，结果表明其性能超越了现有最先进的VLAs。研究证实，我们提出的框架与训练策略为构建协作式具身智能体开辟了新路径。

> The ultimate goal of embodied agents is to create collaborators that can interact with humans, not mere executors that passively follow instructions. This requires agents to communicate, coordinate, and adapt their actions based on human feedback. Recently, advances in VLAs have offered a path toward this goal. However, most current VLA-based embodied agents operate in a one-way mode: they receive an instruction and execute it without feedback. This approach fails in real-world scenarios where instructions are often ambiguous. In this paper, we address this problem with the Ask-to-Clarify framework. Our framework first resolves ambiguous instructions by asking questions in a multi-turn dialogue. Then it generates low-level actions end-to-end. Specifically, the Ask-to-Clarify framework consists of two components, one VLM for collaboration and one diffusion for action. We also introduce a connection module that generates conditions for the diffusion based on the output of the VLM. This module adjusts the observation by instructions to create reliable conditions. We train our framework with a two-stage knowledge-insulation strategy. First, we fine-tune the collaboration component using ambiguity-solving dialogue data to handle ambiguity. Then, we integrate the action component while freezing the collaboration one. This preserves the interaction abilities while fine-tuning the diffusion to generate actions. The training strategy guarantees our framework can first ask questions, then generate actions. During inference, a signal detector functions as a router that helps our framework switch between asking questions and taking actions. We evaluate the Ask-to-Clarify framework in 8 real-world tasks, where it outperforms existing state-of-the-art VLAs. The results suggest that our proposed framework, along with the training strategy, provides a path toward collaborative embodied agents.

[Arxiv](https://arxiv.org/abs/2509.15061)