# RuleArena：现实场景中针对具有 LLMs 的规则引导推理的基准

发布时间：2024年12月12日

`LLM应用`

> RuleArena: A Benchmark for Rule-Guided Reasoning with LLMs in Real-World Scenarios

# 摘要

> 这篇论文引入了RuleArena，这是一个新颖且颇具挑战性的基准，旨在测评大型语言模型（LLMs）在推理时遵循复杂现实规则的能力。它涵盖了三个实际领域——航空公司行李费、NBA交易和税收法规，评估了LLMs处理需要长上下文理解、逻辑推理以及精确数学计算的复杂自然语言指令的水平。RuleArena与传统基于规则的推理基准有两个关键不同点：（1）它超越了标准的一阶逻辑表述；（2）它基于真实实用的场景，为LLMs在现实世界应用中的适用性和可靠性提供了参考。我们的发现揭示了LLMs的几个显著缺陷：（1）难以识别和运用恰当的规则，常被相似但有别的法规搞得晕头转向；（2）即便正确识别了相关规则，也不能一直进行准确的数学运算；（3）总体而言，在基准测试中表现欠佳。这些结果凸显了在现实应用中增强LLMs规则引导推理能力所面临的重大挑战。

> This paper introduces RuleArena, a novel and challenging benchmark designed to evaluate the ability of large language models (LLMs) to follow complex, real-world rules in reasoning. Covering three practical domains -- airline baggage fees, NBA transactions, and tax regulations -- RuleArena assesses LLMs' proficiency in handling intricate natural language instructions that demand long-context understanding, logical reasoning, and accurate mathematical computation. Two key attributes distinguish RuleArena from traditional rule-based reasoning benchmarks: (1) it extends beyond standard first-order logic representations, and (2) it is grounded in authentic, practical scenarios, providing insights into the suitability and reliability of LLMs for real-world applications. Our findings reveal several notable limitations in LLMs: (1) they struggle to identify and apply the appropriate rules, frequently becoming confused by similar but distinct regulations, (2) they cannot consistently perform accurate mathematical computations, even when they correctly identify the relevant rules, and (3) in general, they perform poorly in the benchmark. These results highlight significant challenges in advancing LLMs' rule-guided reasoning capabilities in real-life applications.

[Arxiv](https://arxiv.org/abs/2412.08972)