# 大型语言模型：端到端组合优化求解器

发布时间：2025年09月20日

`LLM应用` `工业与制造` `交通运输`

> Large Language Models as End-to-end Combinatorial Optimization Solvers

# 摘要

> 组合优化（CO）问题是物流、制造等决策场景的核心，传统上需依赖特定问题算法解决，而这些算法往往需要深厚的领域专业知识。尽管大型语言模型（LLMs）在自动化CO问题求解上展现出潜力，但现有方法依赖代码生成或求解器调用等中间步骤，限制了其通用性和易用性。本文提出了一种全新框架，让LLMs能够直接将自然语言问题描述映射为解，从而成为端到端的CO求解器。我们设计了两阶段训练策略：首先通过监督微调（SFT）让LLMs学习特定领域求解器的解生成模式，然后通过可行性与最优性感知强化学习（FOARL）过程，明确减少约束违反并提升解的质量。在七个NP难CO问题上的评估显示，通过调优70亿参数的LLM，我们的方法不仅可行性率高，还将平均最优性差距缩小至1.03%-8.20%，性能超越了通用LLMs（如GPT-4o）、推理模型（如DeepSeek-R1）以及特定领域启发式方法。该方法为CO构建了统一的语言驱动管道，无需针对不同问题执行大量代码或手动调整架构，既提供了一种通用的语言驱动型替代方案，取代传统求解器设计，又能保持相对的可行性保证。

> Combinatorial optimization (CO) problems, central to decision-making scenarios like logistics and manufacturing, are traditionally solved using problem-specific algorithms requiring significant domain expertise. While large language models (LLMs) have shown promise in automating CO problem solving, existing approaches rely on intermediate steps such as code generation or solver invocation, limiting their generality and accessibility. This paper introduces a novel framework that empowers LLMs to serve as end-to-end CO solvers by directly mapping natural language problem descriptions to solutions. We propose a two-stage training strategy: supervised fine-tuning (SFT) imparts LLMs with solution generation patterns from domain-specific solvers, while a feasibility-and-optimality-aware reinforcement learning (FOARL) process explicitly mitigates constraint violations and refines solution quality. Evaluation across seven NP-hard CO problems shows that our method achieves a high feasibility rate and reduces the average optimality gap to 1.03-8.20% by tuning a 7B-parameter LLM, surpassing both general-purpose LLMs (e.g., GPT-4o), reasoning models (e.g., DeepSeek-R1), and domain-specific heuristics. Our method establishes a unified language-based pipeline for CO without extensive code execution or manual architectural adjustments for different problems, offering a general and language-driven alternative to traditional solver design while maintaining relative feasibility guarantees.

[Arxiv](https://arxiv.org/abs/2509.16865)