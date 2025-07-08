# 基于大型语言模型的多智能体动态策略调整

发布时间：2025年07月01日

`Agent

摘要中的论文主要研究基于LLM的智能体在动态、实时、多智能体场景中的推理能力，结合博弈论原则进行策略推理和实时适应。虽然涉及LLM，但核心是智能体的协作和动态适应，属于Agent领域。` `人工智能` `博弈论`

> Dynamic Strategy Adaptation in Multi-Agent Environments with Large Language Models

# 摘要

> 大型语言模型（LLMs）在数学、战略和语言任务中表现出色，但在动态、实时、多智能体场景中的推理能力尚待探索，例如智能体在协作环境中持续适应彼此行为的合作游戏设置。本文结合基于LLM的智能体与基于博弈论原则（如信念一致性和纳什均衡）的策略推理和实时适应，填补了这一研究空白。我们的框架广泛适用于动态场景，其中智能体在持续变化的条件下进行协调、沟通和决策。与以往在静态或回合制环境中评估LLM能力的研究不同，我们提供了实时策略优化和自适应反馈机制，使智能体能够根据即时上下文互动动态调整策略。实证结果表明，在高噪声环境下，我们的方法在回报方面比PPO基线提高了26%，同时保持了低于1.05毫秒的实时延迟。我们的方法显著提高了协作效率、任务完成率和灵活性，证明将博弈论指导与实时反馈相结合可以显著提升LLM性能，最终促进更具韧性和灵活的战略多智能体系统的发展。

> Large language models (LLMs) demonstrate strong reasoning abilities across mathematical, strategic, and linguistic tasks, yet little is known about how well they reason in dynamic, real-time, multi-agent scenarios, such as collaborative environments in which agents continuously adapt to each other's behavior, as in cooperative gameplay settings. In this paper, we bridge this gap by combining LLM-driven agents with strategic reasoning and real-time adaptation in cooperative, multi-agent environments grounded in game-theoretic principles such as belief consistency and Nash equilibrium. The proposed framework applies broadly to dynamic scenarios in which agents coordinate, communicate, and make decisions in response to continuously changing conditions. We provide real-time strategy refinement and adaptive feedback mechanisms that enable agents to dynamically adjust policies based on immediate contextual interactions, in contrast to previous efforts that evaluate LLM capabilities in static or turn-based settings. Empirical results show that our method achieves up to a 26\% improvement in return over PPO baselines in high-noise environments, while maintaining real-time latency under 1.05 milliseconds. Our approach improves collaboration efficiency, task completion rates, and flexibility, illustrating that game-theoretic guidance integrated with real-time feedback enhances LLM performance, ultimately fostering more resilient and flexible strategic multi-agent systems.

[Arxiv](https://arxiv.org/abs/2507.02002)