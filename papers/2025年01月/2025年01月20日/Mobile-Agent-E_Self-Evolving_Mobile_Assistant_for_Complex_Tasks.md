# Mobile-Agent-E：复杂任务的自我进化移动助手

发布时间：2025年01月20日

`Agent

理由：这篇论文主要介绍了一个名为Mobile-Agent-E的分层多代理框架，旨在通过经验自我进化来提升移动设备上的复杂任务处理能力。论文的核心内容围绕代理的设计、功能及其在移动环境中的应用展开，符合“Agent”分类的定义。` `移动设备` `人工智能`

> Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks

# 摘要

> 智能手机已成为现代生活的必需品，但在移动设备上处理复杂任务时，用户常常感到不便。最近，基于大型多模态模型（LMM）的移动代理取得了显著进展，展示了其在移动环境中的感知和行动能力。然而，现有方法存在明显不足：无法充分满足现实需求，难以应对复杂推理和长期规划任务，且缺乏从经验中学习和改进的机制。为此，我们提出了Mobile-Agent-E，一个通过经验自我进化的分层多代理框架。分层设计明确区分了高级规划和低级执行。框架包括一个Manager，负责将复杂任务分解为子目标并制定总体计划，以及四个下属代理——Perceptor、Operator、Action Reflector和Notetaker——分别负责视觉感知、行动执行、错误验证和信息聚合。Mobile-Agent-E还引入了自我进化模块，维护包含Tips和Shortcuts的长期记忆。Tips是从以往任务中总结的环境互动经验，Shortcuts则是为特定任务定制的可重用操作序列。这些机制有助于持续提升性能和效率。此外，我们还推出了Mobile-Eval-E基准测试，包含需要长期规划和多应用交互的复杂任务。实验表明，Mobile-Agent-E在三个基础模型上比现有最佳方法提升了22%。项目页面：https://x-plug.github.io/MobileAgent。

> Smartphones have become indispensable in modern life, yet navigating complex tasks on mobile devices often remains frustrating. Recent advancements in large multimodal model (LMM)-based mobile agents have demonstrated the ability to perceive and act in mobile environments. However, current approaches face significant limitations: they fall short in addressing real-world human needs, struggle with reasoning-intensive and long-horizon tasks, and lack mechanisms to learn and improve from prior experiences. To overcome these challenges, we introduce Mobile-Agent-E, a hierarchical multi-agent framework capable of self-evolution through past experience. By hierarchical, we mean an explicit separation of high-level planning and low-level action execution. The framework comprises a Manager, responsible for devising overall plans by breaking down complex tasks into subgoals, and four subordinate agents--Perceptor, Operator, Action Reflector, and Notetaker--which handle fine-grained visual perception, immediate action execution, error verification, and information aggregation, respectively. Mobile-Agent-E also features a novel self-evolution module which maintains a persistent long-term memory comprising Tips and Shortcuts. Tips are general guidance and lessons learned from prior tasks on how to effectively interact with the environment. Shortcuts are reusable, executable sequences of atomic operations tailored for specific subroutines. The inclusion of Tips and Shortcuts facilitates continuous refinement in performance and efficiency. Alongside this framework, we introduce Mobile-Eval-E, a new benchmark featuring complex mobile tasks requiring long-horizon, multi-app interactions. Empirical results show that Mobile-Agent-E achieves a 22% absolute improvement over previous state-of-the-art approaches across three foundation model backbones. Project page: https://x-plug.github.io/MobileAgent.

[Arxiv](https://arxiv.org/abs/2501.11733)