# 指南森林：基于经验的多指南推理与逐步聚合

发布时间：2025年06月09日

`LLM理论` `数学推理` `程序推理`

> Guideline Forest: Experience-Induced Multi-Guideline Reasoning with Stepwise Aggregation

# 摘要

> 人类推理灵活、适应性强且基于先前经验，这些特性目前仍是大型语言模型（LLMs）难以完全模仿的。现有方法要么在推理时探索多种推理路径，要么通过昂贵的操作搜索最优工作流，但两者在以结构化、高效的方式利用多个可重用策略方面均表现不足。我们提出了一种名为“指导森林”（Guideline Forest）的框架，通过从验证过的示例中归纳结构化推理策略（称为指南）并以逐步聚合的方式执行这些策略，从而增强LLMs的推理能力。与测试时搜索或单路径蒸馏不同，我们的方法通过归纳可重用的指南并将其扩展为多样化变体，来利用验证过的推理经验。这些变体就像人类推理一样，反映了不同的思维模式，可以并行执行，通过自我修正进行优化，并逐步聚合——使模型能够自适应地解决不确定性并合成稳健的解决方案。我们在四个基准测试——GSM8K、MATH-500、MBPP和HumanEval——上评估了指导森林，涵盖了数学和程序推理领域。指导森林在所有测试中均显著超越了包括CoT、ReAct、ToT、FoT和AFlow在内的强基线模型。消融研究进一步凸显了多路径推理和逐步聚合的有效性，突显了指导森林的适应性和泛化潜力。

> Human reasoning is flexible, adaptive, and grounded in prior experience-qualities that large language models (LLMs) still struggle to emulate. Existing methods either explore diverse reasoning paths at inference time or search for optimal workflows through expensive operations, but both fall short in leveraging multiple reusable strategies in a structured, efficient manner. We propose Guideline Forest, a framework that enhances LLMs reasoning by inducing structured reasoning strategies-called guidelines-from verified examples and executing them via step-wise aggregation. Unlike test-time search or single-path distillation, our method draws on verified reasoning experiences by inducing reusable guidelines and expanding each into diverse variants. Much like human reasoning, these variants reflect alternative thought patterns, are executed in parallel, refined via self-correction, and aggregated step by step-enabling the model to adaptively resolve uncertainty and synthesize robust solutions.We evaluate Guideline Forest on four benchmarks-GSM8K, MATH-500, MBPP, and HumanEval-spanning mathematical and programmatic reasoning. Guideline Forest consistently outperforms strong baselines, including CoT, ReAct, ToT, FoT, and AFlow. Ablation studies further highlight the effectiveness of multi-path reasoning and stepwise aggregation, underscoring the Guideline Forest's adaptability and generalization potential.

[Arxiv](https://arxiv.org/abs/2506.07820)