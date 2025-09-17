# 迈向借助环境扩展的通用智能体

发布时间：2025年09月16日

`Agent` `基础理论`

> Towards General Agentic Intelligence via Environment Scaling

# 摘要

> 高级智能体智能是大型语言模型在实际应用场景落地的先决条件。现实世界中的API五花八门，这就要求函数调用智能既精准又稳健，而智能体需要在多样环境中交互才能培养出这些能力。函数调用能力的广度，与智能体训练环境的多样性息息相关。为此，本研究将环境规模化，作为提升通用智能体智能的重要一步。这随之带来两个核心难题：（i）如何科学地规模化环境；（ii）如何从与这些环境交互的经验中，高效训练智能体能力。为应对这些挑战，我们设计了一个可扩展框架，它能自动构建全模拟的异构环境，从而系统性地拓展函数调用场景的覆盖范围。我们还采用了两阶段智能体微调策略：先让智能体掌握基础智能体能力，再针对特定领域场景进行专项优化。在tau-bench、tau2-Bench和ACEBench等智能体基准测试中，大量实验证实，我们训练的模型AgentScaler能显著提升模型的函数调用能力。

> Advanced agentic intelligence is a prerequisite for deploying Large Language Models in practical, real-world applications. Diverse real-world APIs demand precise, robust function-calling intelligence, which needs agents to develop these capabilities through interaction in varied environments. The breadth of function-calling competence is closely tied to the diversity of environments in which agents are trained. In this work, we scale up environments as a step towards advancing general agentic intelligence. This gives rise to two central challenges: (i) how to scale environments in a principled manner, and (ii) how to effectively train agentic capabilities from experiences derived through interactions with these environments. To address these, we design a scalable framework that automatically constructs heterogeneous environments that are fully simulated, systematically broadening the space of function-calling scenarios. We further adapt a two-phase agent fine-tuning strategy: first endowing agents with fundamental agentic capabilities, then specializing them for domain-specific contexts. Extensive experiments on agentic benchmarks, tau-bench, tau2-Bench, and ACEBench, demonstrate that our trained model, AgentScaler, significantly enhances the function-calling capability of models.

[Arxiv](https://arxiv.org/abs/2509.13311)