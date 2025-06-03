# TurnBench-MS: 评估大型语言模型多轮多步骤推理能力的基准测试

发布时间：2025年06月02日

`LLM应用` `人工智能` `人机交互`

> TurnBench-MS: A Benchmark for Evaluating Multi-Turn, Multi-Step Reasoning in Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，现有基准测试多聚焦于单轮或单步任务，难以反映真实场景所需的迭代推理能力。为此，我们提出了 TurnBench——一个基于“图灵机棋盘游戏”理念的交互式破译任务，用于评估多轮、多步推理能力。在每个 episode 中，模型需通过逐步猜测、接收结构化反馈并整合多轮线索，揭示隐藏的逻辑或算术规则。这种动态设置要求模型在时间维度上进行推理，根据历史信息调整策略，并在各步骤间保持一致性——这些能力在现有基准中尚未得到充分挖掘。TurnBench 设有 Classic 和 Nightmare 两种模式，分别测试标准推理与复杂推理。为支持深入分析，我们提供了中间推理步骤的 ground-truth 注释。对当前先进 LLMs 的评估显示，模型在 Classic 模式中最佳准确率为 81.5%，但在 Nightmare 模式中骤降至 17.8%。相比之下，人类参与者在两种模式中均达到 100% 的准确率，凸显了 TurnBench 对现有模型的挑战性。通过引入反馈循环并隐藏任务规则，TurnBench 有效降低了污染风险，为诊断和提升 LLMs 的多步、多轮推理能力提供了一个严格的测试平台。

> Despite impressive advances in large language models (LLMs), existing benchmarks often focus on single-turn or single-step tasks, failing to capture the kind of iterative reasoning required in real-world settings. To address this limitation, we introduce TurnBench, a novel benchmark that evaluates multi-turn, multi-step reasoning through an interactive code-breaking task inspired by a "Turing Machine Board Game." In each episode, a model must uncover hidden logical or arithmetic rules by making sequential guesses, receiving structured feedback, and integrating clues across multiple rounds. This dynamic setup requires models to reason over time, adapt based on past information, and maintain consistency across steps-capabilities underexplored in current benchmarks. TurnBench includes two modes: Classic, which tests standard reasoning, and Nightmare, which introduces increased complexity and requires robust inferential chains. To support fine-grained analysis, we provide ground-truth annotations for intermediate reasoning steps. Our evaluation of state-of-the-art LLMs reveals significant gaps: the best model achieves 81.5% accuracy in Classic mode, but performance drops to 17.8% in Nightmare mode. In contrast, human participants achieve 100% in both, underscoring the challenge TurnBench poses to current models. By incorporating feedback loops and hiding task rules, TurnBench reduces contamination risks and provides a rigorous testbed for diagnosing and advancing multi-step, multi-turn reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2506.01341)