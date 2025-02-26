# # **LR${}^{2}$Bench**：利用约束满足问题评估大型语言模型的长链反思推理能力

发布时间：2025年02月24日

`LLM理论` `人工智能`

> LR${}^{2}$Bench: Evaluating Long-chain Reflective Reasoning Capabilities of Large Language Models via Constraint Satisfaction Problems

# 摘要

> 近期，o1-like 模型的突破显著提升了大型语言模型 (LLMs) 的推理能力，赋予其通过假设、回溯和自我完善等反思能力处理复杂任务的能力。然而，由于缺乏合适的评估基准，准确衡量这些反思能力仍具挑战。为此，我们推出了 LR²Bench，一个专为评估 LLMs 长链反思推理能力设计的全新基准测试。该基准包含 850 个样本，覆盖六个关键约束满足问题 (CSPs)，其中反思推理是获得满足所有约束解决方案的核心。每种任务类型聚焦于不同类型的约束模式，包括知识、逻辑和空间约束，从而全面评估多样化的解决问题场景。我们对传统模型和 o1-like 模型进行了全面评估。实验结果揭示，即使是专注于推理的先进模型，如 DeepSeek-R1 和 OpenAI o1-preview，在 LR²Bench 任务中表现仍显不足，Exact Match 分数分别仅为 20.0% 和 23.6%。这一结果凸显了当前 LLMs 反思推理能力的提升空间。我们的基准测试排行榜现已开放，详情请访问 https://huggingface.co/spaces/UltraRonin/LR2Bench。

> Recent progress in o1-like models has significantly enhanced the reasoning abilities of Large Language Models (LLMs), empowering them to tackle increasingly complex tasks through reflection capabilities, such as making assumptions, backtracking, and self-refinement. However, effectively evaluating such reflection capabilities remains challenging due to the lack of appropriate benchmarks. To bridge this gap, we introduce LR${}^{2}$Bench, a novel benchmark designed to evaluate the Long-chain Reflective Reasoning capabilities of LLMs. LR${}^{2}$Bench comprises 850 samples across six Constraint Satisfaction Problems (CSPs) where reflective reasoning is crucial for deriving solutions that meet all given constraints. Each type of task focuses on distinct constraint patterns, such as knowledge-based, logical, and spatial constraints, providing a comprehensive evaluation of diverse problem-solving scenarios. We conduct extensive evaluation on both conventional models and o1-like models. Our experimental results reveal that even the most advanced reasoning-specific models, such as DeepSeek-R1 and OpenAI o1-preview, struggle with tasks in LR${}^{2}$Bench, achieving an average Exact Match score of only 20.0% and 23.6%, respectively. These findings underscore the significant room for improvement in the reflective reasoning capabilities of current LLMs. The leaderboard of our benchmark is available at https://huggingface.co/spaces/UltraRonin/LR2Bench

[Arxiv](https://arxiv.org/abs/2502.17848)