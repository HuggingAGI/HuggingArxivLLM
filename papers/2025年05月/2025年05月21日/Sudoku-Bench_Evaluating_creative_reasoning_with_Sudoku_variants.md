# 数独基准：通过数独变种评估创造性推理能力

发布时间：2025年05月21日

`LLM应用` `逻辑推理` `问题解决`

> Sudoku-Bench: Evaluating creative reasoning with Sudoku variants

# 摘要

> 现有的大型语言模型（LLMs）推理基准测试往往难以捕捉真实的创造力，常常只是奖励对之前观察到的模式的记忆。为了解决这一问题，我们推出了 Sudoku-Bench，这是一个经过精心策划的数独变体基准测试，旨在评估创造性的、多步骤的逻辑推理能力。数独变体在推理研究中具有独特的优势：每个谜题都引入了独特的或微妙相互作用的约束，使得单纯依靠记忆变得不可行，要求解题者必须找到新的逻辑突破口（“突破点”）。尽管数独变体种类繁多，但它们都保持了一个共同且紧凑的结构，从而确保了评估的清晰和一致性。Sudoku-Bench 包含一个精心挑选的谜题集、一个标准化的基于文本的谜题表示以及与数千个公开可用谜题兼容的灵活工具——使其能够轻松扩展到通用的研究环境。基线实验结果显示，即使是最先进的 LLMs 在没有帮助的情况下也只能解决不到 15% 的谜题，这凸显了进一步提升长期、战略性推理能力的巨大潜力。

> Existing reasoning benchmarks for large language models (LLMs) frequently fail to capture authentic creativity, often rewarding memorization of previously observed patterns. We address this shortcoming with Sudoku-Bench, a curated benchmark of challenging and unconventional Sudoku variants specifically selected to evaluate creative, multi-step logical reasoning. Sudoku variants form an unusually effective domain for reasoning research: each puzzle introduces unique or subtly interacting constraints, making memorization infeasible and requiring solvers to identify novel logical breakthroughs (``break-ins''). Despite their diversity, Sudoku variants maintain a common and compact structure, enabling clear and consistent evaluation. Sudoku-Bench includes a carefully chosen puzzle set, a standardized text-based puzzle representation, and flexible tools compatible with thousands of publicly available puzzles -- making it easy to extend into a general research environment. Baseline experiments show that state-of-the-art LLMs solve fewer than 15\% of puzzles unaided, highlighting significant opportunities to advance long-horizon, strategic reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2505.16135)