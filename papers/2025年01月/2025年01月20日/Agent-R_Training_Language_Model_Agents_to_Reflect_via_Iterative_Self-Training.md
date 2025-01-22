# Agent-R: 通过迭代自我训练让语言模型代理学会反思

发布时间：2025年01月20日

`Agent

理由：这篇论文主要讨论了如何通过迭代自我训练框架（Agent-R）来提升大型语言模型（LLMs）代理在交互环境中处理复杂任务的能力。论文的核心是让语言代理能够即时反思并从错误中恢复，这与“Agent”分类中的智能代理和自我改进能力密切相关。论文提出的方法（如MCTS构建训练数据、模型引导的批评构建机制等）都是为了增强代理的自主性和适应性，因此更适合归类为“Agent”。` `人工智能` `交互系统`

> Agent-R: Training Language Model Agents to Reflect via Iterative Self-Training

# 摘要

> # 摘要
大型语言模型（LLMs）代理在交互环境中处理复杂任务的作用日益凸显。现有研究多通过模仿更强专家的行为来提升性能，但这种方法在现实中常因无法从错误中恢复而失效。由于步骤级批评数据难以获取且成本高，自动化和动态构建自我批评数据集成为赋予模型智能代理能力的关键。为此，我们提出了迭代自我训练框架Agent-R，使语言代理能够即时反思。与传统方法不同，Agent-R利用MCTS构建训练数据，从错误轨迹中恢复正确轨迹。代理反思的核心挑战在于需要及时修正，而非等到任务结束。为此，我们引入了模型引导的批评构建机制：演员模型在失败轨迹中识别出第一个错误步骤（在其当前能力范围内），并将其与树中共享相同父节点的相邻正确路径拼接。这一策略使模型能基于当前策略学习反思，提升学习效率。为进一步探索这一自我改进范式的可扩展性，我们研究了错误纠正能力和数据集构建的迭代改进。实验表明，Agent-R持续提升了模型从错误中恢复的能力，并实现了及时的错误纠正。在三个交互环境中的实验显示，Agent-R使代理能有效纠正错误行动，避免循环，性能显著优于基线方法（+5.59%）。

> Large Language Models (LLMs) agents are increasingly pivotal for addressing complex tasks in interactive environments. Existing work mainly focuses on enhancing performance through behavior cloning from stronger experts, yet such approaches often falter in real-world applications, mainly due to the inability to recover from errors. However, step-level critique data is difficult and expensive to collect. Automating and dynamically constructing self-critique datasets is thus crucial to empowering models with intelligent agent capabilities. In this work, we propose an iterative self-training framework, Agent-R, that enables language Agent to Reflect on the fly. Unlike traditional methods that reward or penalize actions based on correctness, Agent-R leverages MCTS to construct training data that recover correct trajectories from erroneous ones. A key challenge of agent reflection lies in the necessity for timely revision rather than waiting until the end of a rollout. To address this, we introduce a model-guided critique construction mechanism: the actor model identifies the first error step (within its current capability) in a failed trajectory. Starting from it, we splice it with the adjacent correct path, which shares the same parent node in the tree. This strategy enables the model to learn reflection based on its current policy, therefore yielding better learning efficiency. To further explore the scalability of this self-improvement paradigm, we investigate iterative refinement of both error correction capabilities and dataset construction. Our findings demonstrate that Agent-R continuously improves the model's ability to recover from errors and enables timely error correction. Experiments on three interactive environments show that Agent-R effectively equips agents to correct erroneous actions while avoiding loops, achieving superior performance compared to baseline methods (+5.59%).

[Arxiv](https://arxiv.org/abs/2501.11425)