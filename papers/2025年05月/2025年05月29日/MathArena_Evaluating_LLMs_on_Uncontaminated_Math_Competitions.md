# # 数学竞技场：评估大型语言模型在未被污染的数学竞赛中的表现

发布时间：2025年05月29日

`LLM应用

论文摘要：大型语言模型（LLMs）推理能力的突飞猛进推动了数学基准测试的进步。然而，现有常用数据集（如AIME 2024）的广泛流通使得区分真实推理与记忆变得困难。此外，这些基准未能评估证明撰写能力，而这对于数学任务至关重要。为解决这一问题，我们推出MathArena，一个基于以下核心理念的新基准：重复举办的数学竞赛提供了持续的高质量、高难度题目，为实时评估LLMs提供了理想场景。通过在新问题发布后立即进行评估，我们有效避免了数据泄露风险。基于此框架，我们在AIME 2024中发现了显著的数据泄露迹象。然而，对难度更大的竞赛（如SMT 2025——在模型发布后许久才公布）的评估显示，顶尖模型依然展现了强大的推理能力。值得注意的是，MathArena是首个专注于证明撰写能力的基准。在USAMO 2025中，即使是最顶级的模型得分也低于25%，远逊于其在最终答案任务上的表现。截至目前，我们已在五项竞赛中评估了30种模型，总问题数达149道。作为不断发展的基准，MathArena将持续追踪LLMs在新发布竞赛中的表现，确保对其数学推理能力进行严格且最新的评估。

LLM应用` `数学推理`

> MathArena: Evaluating LLMs on Uncontaminated Math Competitions

# 摘要

> 大型语言模型（LLMs）推理能力的突飞猛进推动了数学基准测试的进步。然而，现有常用数据集（如AIME 2024）的广泛流通使得区分真实推理与记忆变得困难。此外，这些基准未能评估证明撰写能力，而这对于数学任务至关重要。为解决这一问题，我们推出MathArena，一个基于以下核心理念的新基准：重复举办的数学竞赛提供了持续的高质量、高难度题目，为实时评估LLMs提供了理想场景。通过在新问题发布后立即进行评估，我们有效避免了数据泄露风险。基于此框架，我们在AIME 2024中发现了显著的数据泄露迹象。然而，对难度更大的竞赛（如SMT 2025——在模型发布后许久才公布）的评估显示，顶尖模型依然展现了强大的推理能力。值得注意的是，MathArena是首个专注于证明撰写能力的基准。在USAMO 2025中，即使是最顶级的模型得分也低于25%，远逊于其在最终答案任务上的表现。截至目前，我们已在五项竞赛中评估了30种模型，总问题数达149道。作为不断发展的基准，MathArena将持续追踪LLMs在新发布竞赛中的表现，确保对其数学推理能力进行严格且最新的评估。

> The rapid advancement of reasoning capabilities in large language models (LLMs) has led to notable improvements on mathematical benchmarks. However, many of the most commonly used evaluation datasets (e.g., AIME 2024) are widely available online, making it difficult to disentangle genuine reasoning from potential memorization. Furthermore, these benchmarks do not evaluate proof-writing capabilities, which are crucial for many mathematical tasks. To address this, we introduce MathArena, a new benchmark based on the following key insight: recurring math competitions provide a stream of high-quality, challenging problems that can be used for real-time evaluation of LLMs. By evaluating models as soon as new problems are released, we effectively eliminate the risk of contamination. Using this framework, we find strong signs of contamination in AIME 2024. Nonetheless, evaluations on harder competitions, such as SMT 2025 -- published well after model release dates -- demonstrate impressive reasoning capabilities in top-performing models. MathArena is also the first benchmark for proof-writing capabilities. On USAMO 2025, even top models score below 25%, far behind their performance on final-answer tasks. So far, we have evaluated 30 models across five competitions, totaling 149 problems. As an evolving benchmark, MathArena will continue to track the progress of LLMs on newly released competitions, ensuring rigorous and up-to-date evaluation of mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2505.23281)