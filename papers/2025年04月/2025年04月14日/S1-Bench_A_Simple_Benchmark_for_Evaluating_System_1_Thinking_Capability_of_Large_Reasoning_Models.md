# S1-Bench：简单易用的基准测试，专为评估大型推理模型的直觉思维能力而设计

发布时间：2025年04月14日

`LLM应用

理由：这篇论文主要讨论了大型推理模型（LRMs）在简单任务中的表现，提出了一个新的基准测试S1-Bench，并评估了22个LRMs的表现。这属于对大型语言模型应用的评估和分析，因此归类为LLM应用。` `推理评估` `模型评估`

> S1-Bench: A Simple Benchmark for Evaluating System 1 Thinking Capability of Large Reasoning Models

# 摘要

> 我们推出 S1-Bench，一个全新的基准测试，专注于评估大型推理模型（LRMs）在简单任务中的表现，这些任务更依赖直觉的系统1思维，而非深思熟虑的系统2推理。尽管LRMs在复杂推理任务中通过明确的思维链取得了显著突破，但它们对深度分析思维的依赖可能限制了其系统1思维的能力。目前，评估LRMs在需要此类能力的任务中的表现缺乏合适的基准。为此，S1-Bench提供了一系列简单、多样化且自然清晰的问题，涵盖多个领域和语言，特别设计用于评估LRMs在这些任务中的表现。我们对22个LRMs的全面评估显示了显著的效率偏低趋势，其输出平均比传统小型LLMs长15.5倍。此外，LRMs通常在早期就能识别出正确答案，但会继续不必要的思考，有些模型甚至产生大量错误。这些发现凸显了当前LRMs推理模式的僵化，并强调了实现平衡的双系统思维能力以适应任务复杂度所需的重大发展。

> We introduce S1-Bench, a novel benchmark designed to evaluate Large Reasoning Models' (LRMs) performance on simple tasks that favor intuitive system 1 thinking rather than deliberative system 2 reasoning. While LRMs have achieved significant breakthroughs in complex reasoning tasks through explicit chains of thought, their reliance on deep analytical thinking may limit their system 1 thinking capabilities. Moreover, a lack of benchmark currently exists to evaluate LRMs' performance in tasks that require such capabilities. To fill this gap, S1-Bench presents a set of simple, diverse, and naturally clear questions across multiple domains and languages, specifically designed to assess LRMs' performance in such tasks. Our comprehensive evaluation of 22 LRMs reveals significant lower efficiency tendencies, with outputs averaging 15.5 times longer than those of traditional small LLMs. Additionally, LRMs often identify correct answers early but continue unnecessary deliberation, with some models even producing numerous errors. These findings highlight the rigid reasoning patterns of current LRMs and underscore the substantial development needed to achieve balanced dual-system thinking capabilities that can adapt appropriately to task complexity.

[Arxiv](https://arxiv.org/abs/2504.10368)