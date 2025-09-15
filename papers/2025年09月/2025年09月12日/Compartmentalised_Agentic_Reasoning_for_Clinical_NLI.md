# 针对临床NLI的分块智能体推理

发布时间：2025年09月12日

`Agent` `医疗健康`

> Compartmentalised Agentic Reasoning for Clinical NLI

# 摘要

> 人们普遍认为，扩大数据和参数规模能产生结构更清晰、泛化能力更强的内部表征。为验证这一假设，我们在临床自然语言推理（NLI）领域展开研究：采用了一个分解为四个推理家族的基准——因果归因、组合接地、认知验证与风险状态抽象，并提出了CARENLI（临床NLI模块化智能体推理方法）。该方法创新性地将知识获取与原则性推理分离，会将每个前提-陈述对分配给特定推理家族的求解器，并通过规划器、验证器和优化器确保推理过程的可审计性。
  在四个LLM上的实验显示，CARENLI将保真度提升了多达42个百分点，其中因果归因任务准确率达98.0%，风险状态抽象任务达81.2%。验证器能以近乎完美的可靠性识别违规情况，优化器则可纠正大量认知错误。剩余错误主要集中在路由环节，说明推理家族分类是主要瓶颈。这些结果揭示：LLM往往能保留相关事实，但在推理任务不明确时会默认采用启发式策略；而CARENLI不仅清晰揭示了这种矛盾，还提供了一个更安全、可审计的推理框架。

> A common assumption holds that scaling data and parameters yields increasingly structured, generalisable internal representations. We interrogate this assumption in clinical natural language inference (NLI) by adopting a benchmark decomposed into four reasoning families, Causal Attribution, Compositional Grounding, Epistemic Verification, and Risk State Abstraction, and introducing CARENLI, a Compartmentalised Agentic Reasoning for Clinical NLI that separates knowledge access from principled inference. CARENLI routes each premise, statement pair to a family specific solver and enforces auditable procedures via a planner, verifier, and refiner.
  Across four LLMs, CARENLI improves fidelity by up to 42 points, reaching 98.0% in Causal Attribution and 81.2% in Risk State Abstraction. Verifiers flag violations with near-ceiling reliability, while refiners correct a substantial share of epistemic errors. Remaining failures cluster in routing, identifying family classification as the main bottleneck. These results show that LLMs often retain relevant facts but default to heuristics when inference is underspecified, a dissociation CARENLI makes explicit while offering a framework for safer, auditable reasoning.

[Arxiv](https://arxiv.org/abs/2509.10222)