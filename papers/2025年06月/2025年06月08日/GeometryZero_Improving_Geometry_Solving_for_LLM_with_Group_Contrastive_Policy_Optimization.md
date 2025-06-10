# GeometryZero：采用基于组对比的策略优化，提升大型语言模型的几何解题能力

发布时间：2025年06月08日

`LLM应用` `数学推理`

> GeometryZero: Improving Geometry Solving for LLM with Group Contrastive Policy Optimization

# 摘要

> 大型语言模型（LLMs）在数学推理领域展现了卓越能力，尤其在几何问题求解这一挑战性领域，辅助构造发挥着关键作用。现有方法要么表现不佳，要么依赖于庞大模型（如GPT-4o），带来高昂计算成本。我们提出，通过具有可验证奖励的强化学习（如GRPO）训练小型模型，是结合辅助构造与稳健几何推理的潜力方向。然而，直接应用GRPO于几何推理存在根本性限制，因其依赖无条件奖励，导致盲目且低效的辅助构造。为解决这一难题，我们推出群对比策略优化（GCPO），一个创新强化学习框架，包含两大核心创新：（1）群对比掩码，根据上下文效用自适应提供辅助构造的正负奖励信号；（2）长度奖励，促进更长推理链。基于GCPO，我们开发了GeometryZero，一系列经济实惠的几何推理模型，能够明智决定何时使用辅助构造。在Geometry3K和MathVista等流行基准测试中的广泛实证评估表明，GeometryZero模型始终优于现有方法（如GRPO），在所有基准上平均提升了4.29%。

> Recent advances in large language models (LLMs) have demonstrated remarkable capabilities across diverse domains, particularly in mathematical reasoning, amid which geometry problem solving remains a challenging area where auxiliary construction plays a enssential role. Existing approaches either achieve suboptimal performance or rely on massive LLMs (e.g., GPT-4o), incurring massive computational costs. We posit that reinforcement learning with verifiable reward (e.g., GRPO) offers a promising direction for training smaller models that effectively combine auxiliary construction with robust geometric reasoning. However, directly applying GRPO to geometric reasoning presents fundamental limitations due to its dependence on unconditional rewards, which leads to indiscriminate and counterproductive auxiliary constructions. To address these challenges, we propose Group Contrastive Policy Optimization (GCPO), a novel reinforcement learning framework featuring two key innovations: (1) Group Contrastive Masking, which adaptively provides positive or negative reward signals for auxiliary construction based on contextual utility, and a (2) length reward that promotes longer reasoning chains. Building on GCPO, we develop GeometryZero, a family of affordable-size geometric reasoning models that judiciously determine when to employ auxiliary construction. Our extensive empirical evaluation across popular geometric benchmarks (Geometry3K, MathVista) demonstrates that GeometryZero models consistently outperform baselines (e.g. GRPO), achieving an average improvement of 4.29% across all benchmarks.

[Arxiv](https://arxiv.org/abs/2506.07160)