# Vintix: 基于上下文强化学习的动作模型

发布时间：2025年01月31日

`Agent

理由：这篇论文主要讨论的是 In-Context Reinforcement Learning (ICRL) 范式，旨在开发通用智能体（Agent），这些智能体通过试错交互进行学习，类似于大型语言模型的上下文适应能力，但专注于奖励最大化。研究重点在于智能体的学习和决策能力，因此应归类为Agent。` `人工智能`

> Vintix: Action Model via In-Context Reinforcement Learning

# 摘要

> # 摘要
In-Context Reinforcement Learning (ICRL) 是一种极具潜力的范式，旨在开发通用智能体，这些智能体在推理时通过试错交互进行学习，类似于大型语言模型的上下文适应能力，但专注于奖励最大化。然而，ICRL 在玩具任务和单一领域之外的可扩展性仍是一个未解难题。本研究通过引入一个固定的跨领域模型，迈出了扩展 ICRL 的第一步，该模型能够通过上下文强化学习来学习行为。我们的结果表明，Algorithm Distillation 框架为构建多功能动作模型提供了一个极具竞争力的替代方案，超越了传统的专家蒸馏方法。这些发现凸显了 ICRL 作为通用决策系统可扩展方法的巨大潜力。代码将在 https://github.com/dunnolab/vintix 发布。

> In-Context Reinforcement Learning (ICRL) represents a promising paradigm for developing generalist agents that learn at inference time through trial-and-error interactions, analogous to how large language models adapt contextually, but with a focus on reward maximization. However, the scalability of ICRL beyond toy tasks and single-domain settings remains an open challenge. In this work, we present the first steps toward scaling ICRL by introducing a fixed, cross-domain model capable of learning behaviors through in-context reinforcement learning. Our results demonstrate that Algorithm Distillation, a framework designed to facilitate ICRL, offers a compelling and competitive alternative to expert distillation to construct versatile action models. These findings highlight the potential of ICRL as a scalable approach for generalist decision-making systems. Code to be released at https://github.com/dunnolab/vintix

[Arxiv](https://arxiv.org/abs/2501.19400)