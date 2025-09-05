# EvoEmo：面向LLM智能体多轮谈判的进化情感策略

发布时间：2025年09月04日

`Agent` `基础理论`

> EvoEmo: Towards Evolved Emotional Policies for LLM Agents in Multi-Turn Negotiation

# 摘要

> 近期关于大型语言模型（LLMs）中思维链（CoT）推理的研究显示，智能体已能参与复杂的多轮谈判，为智能体AI开辟了全新可能。然而，现有LLM智能体往往忽略情绪在谈判中的功能性作用，而是生成被动的、由偏好主导的情绪回应，这使其易被对手操纵和策略性利用。为填补这一空白，我们提出EvoEmo——一种进化强化学习框架，旨在优化谈判中的动态情绪表达。EvoEmo将情绪状态转换建模为马尔可夫决策过程，并通过基于种群的遗传优化，在多样的谈判场景中进化出高回报的情绪策略。我们还进一步提出了包含两个基线（基础策略和固定情绪策略）的评估框架，为情绪感知谈判提供了基准测试。大量实验和消融研究结果显示，EvoEmo均持续优于两个基线，不仅成功率更高、效率更佳，还为买方节省了更多成本。这一发现凸显了适应性情绪表达对于提升LLM智能体多轮谈判效果的重要性。

> Recent research on Chain-of-Thought (CoT) reasoning in Large Language Models (LLMs) has demonstrated that agents can engage in \textit{complex}, \textit{multi-turn} negotiations, opening new avenues for agentic AI. However, existing LLM agents largely overlook the functional role of emotions in such negotiations, instead generating passive, preference-driven emotional responses that make them vulnerable to manipulation and strategic exploitation by adversarial counterparts. To address this gap, we present EvoEmo, an evolutionary reinforcement learning framework that optimizes dynamic emotional expression in negotiations. EvoEmo models emotional state transitions as a Markov Decision Process and employs population-based genetic optimization to evolve high-reward emotion policies across diverse negotiation scenarios. We further propose an evaluation framework with two baselines -- vanilla strategies and fixed-emotion strategies -- for benchmarking emotion-aware negotiation. Extensive experiments and ablation studies show that EvoEmo consistently outperforms both baselines, achieving higher success rates, higher efficiency, and increased buyer savings. This findings highlight the importance of adaptive emotional expression in enabling more effective LLM agents for multi-turn negotiation.

[Arxiv](https://arxiv.org/abs/2509.04310)