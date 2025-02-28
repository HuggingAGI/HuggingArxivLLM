# # FINEREASON：通过反思性谜题解决评估与提升LLMs的刻意推理能力

发布时间：2025年02月27日

`LLM理论` `逻辑推理` `数学推理`

> FINEREASON: Evaluating and Improving LLMs' Deliberate Reasoning through Reflective Puzzle Solving

# 摘要

> 许多复杂推理任务不仅需要快速反应，更需要深思熟虑的多步骤解决方案。大型语言模型（LLMs）的最新进展体现了从直觉驱动的“系统1”思维向反思与修正型“系统2”问题解决方式的转变。然而，现有评估指标过分关注最终答案的准确性，忽视了推理过程中的中间步骤。这使得我们无法全面评估模型在推理过程中自我纠错的能力。为此，我们推出了FINEREASON——一个专为细粒度评估LLMs推理能力而设计的逻辑 puzzle 测试集。每个 puzzle 都被分解为独立的原子步骤，便于对推理过程中的每一步进行严格验证。在此基础上，我们设计了两个核心任务：状态检查与状态转换，全面考察模型对当前情境的评估能力和下一步行动的规划能力。为了推动更广泛的研究探索，我们还提供了一个 puzzle 训练集，旨在提升模型在通用数学任务上的表现。实验结果表明，经过状态检查与转换数据训练的模型在 GSM8K 数据集上的数学推理能力提升了高达5.1%。

> Many challenging reasoning tasks require not just rapid, intuitive responses, but a more deliberate, multi-step approach. Recent progress in large language models (LLMs) highlights an important shift from the "System 1" way of quick reactions to the "System 2" style of reflection-and-correction problem solving. However, current benchmarks heavily rely on the final-answer accuracy, leaving much of a model's intermediate reasoning steps unexamined. This fails to assess the model's ability to reflect and rectify mistakes within the reasoning process. To bridge this gap, we introduce FINEREASON, a logic-puzzle benchmark for fine-grained evaluation of LLMs' reasoning capabilities. Each puzzle can be decomposed into atomic steps, making it ideal for rigorous validation of intermediate correctness. Building on this, we introduce two tasks: state checking, and state transition, for a comprehensive evaluation of how models assess the current situation and plan the next move. To support broader research, we also provide a puzzle training set aimed at enhancing performance on general mathematical tasks. We show that models trained on our state checking and transition data demonstrate gains in math reasoning by up to 5.1% on GSM8K.

[Arxiv](https://arxiv.org/abs/2502.20238)