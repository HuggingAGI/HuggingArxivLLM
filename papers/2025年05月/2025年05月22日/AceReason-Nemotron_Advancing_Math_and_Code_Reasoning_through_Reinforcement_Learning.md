# AceReason-Nemotron：强化学习助力数学与代码推理能力的突破

发布时间：2025年05月22日

`LLM理论` `人工智能`

> AceReason-Nemotron: Advancing Math and Code Reasoning through Reinforcement Learning

# 摘要

> 尽管大规模强化学习（RL）在推理领域取得了 recent progress，但构建高性能推理模型的训练配方仍不明确。前沿模型如DeepSeek-R1的关键实现细节，包括数据整理策略和RL训练配方，往往未被详细公开。此外，最新研究指出，蒸馏技术对于小型模型而言仍优于RL。在本研究中，我们证实大规模RL能显著提升小型和中型模型的推理能力，超越现有蒸馏模型的性能。通过广泛消融实验，我们系统研究了RL训练过程，并提出了一种简单有效的策略：先训练数学提示，再训练代码提示。值得注意的是，仅数学RL不仅显著提升了数学基准上的性能（如7B/14B模型在AIME 2025上分别提升14.6%和17.2%），还改善了代码推理任务（如7B/14B模型在LiveCodeBench上分别提升6.8%和5.8%）。延长代码RL迭代进一步优化了代码基准性能，同时数学结果几乎未受影响。我们开发了一个高效的数据整理管道，收集具有高质量答案和测试用例的挑战性提示，支持跨领域的验证式RL。最后，我们总结了关键见解，包括响应长度逐步增加的课程学习和on-policy更新的稳定效应。我们发现，RL不仅激发了模型在预训练和监督微调中的推理能力，还将其推理能力推向极限，解决以往无法处理的问题。


> Despite recent progress in large-scale reinforcement learning (RL) for reasoning, the training recipe for building high-performing reasoning models remains elusive. Key implementation details of frontier models, such as DeepSeek-R1, including data curation strategies and RL training recipe, are often omitted. Moreover, recent research indicates distillation remains more effective than RL for smaller models. In this work, we demonstrate that large-scale RL can significantly enhance the reasoning capabilities of strong, small- and mid-sized models, achieving results that surpass those of state-of-the-art distillation-based models. We systematically study the RL training process through extensive ablations and propose a simple yet effective approach: first training on math-only prompts, then on code-only prompts. Notably, we find that math-only RL not only significantly enhances the performance of strong distilled models on math benchmarks (e.g., +14.6% / +17.2% on AIME 2025 for the 7B / 14B models), but also code reasoning tasks (e.g., +6.8% / +5.8% on LiveCodeBench for the 7B / 14B models). In addition, extended code-only RL iterations further improve performance on code benchmarks with minimal or no degradation in math results. We develop a robust data curation pipeline to collect challenging prompts with high-quality, verifiable answers and test cases to enable verification-based RL across both domains. Finally, we identify key experimental insights, including curriculum learning with progressively increasing response lengths and the stabilizing effect of on-policy parameter updates. We find that RL not only elicits the foundational reasoning capabilities acquired during pretraining and supervised fine-tuning (e.g., distillation), but also pushes the limits of the model's reasoning ability, enabling it to solve problems that were previously unsolvable.

[Arxiv](https://arxiv.org/abs/2505.16400)