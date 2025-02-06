# Satori: 链式动作思维强化学习，通过自回归搜索提升LLM推理能力

发布时间：2025年02月04日

`LLM理论

**理由**：这篇论文主要探讨了如何通过内化搜索能力来增强单个大型语言模型（LLM）的推理能力，提出了新的推理方法（Chain-of-Action-Thought）和训练范式。这些内容属于对LLM的理论改进和优化，因此归类为LLM理论。` `人工智能`

> Satori: Reinforcement Learning with Chain-of-Action-Thought Enhances LLM Reasoning via Autoregressive Search

# 摘要

> 大型语言模型（LLMs）在多个领域展现了卓越的推理能力。最新研究表明，增加测试时的计算量能显著提升LLMs的推理能力。这通常需要在推理时由外部LLM验证器指导进行大量采样，形成一个双玩家系统。尽管有外部指导，该系统的有效性证明了单个LLM处理复杂任务的潜力。因此，我们提出了一个新研究问题：能否将搜索能力内化，从根本上增强单个LLM的推理能力？本研究探索了一个新方向，专注于后训练LLMs进行自回归搜索（即扩展的推理过程，包括自我反思和新策略的自我探索）。为此，我们提出了Chain-of-Action-Thought（COAT）推理和两阶段训练范式：1）小规模格式调整阶段，内化COAT推理格式；2）大规模自改进阶段，利用强化学习。我们的方法产生了Satori，一个基于开源模型和数据训练的7B LLM。广泛的实证评估表明，Satori在数学推理基准上达到了最先进的性能，同时展现出对域外任务的强大泛化能力。代码、数据和模型将完全开源。

> Large language models (LLMs) have demonstrated remarkable reasoning capabilities across diverse domains. Recent studies have shown that increasing test-time computation enhances LLMs' reasoning capabilities. This typically involves extensive sampling at inference time guided by an external LLM verifier, resulting in a two-player system. Despite external guidance, the effectiveness of this system demonstrates the potential of a single LLM to tackle complex tasks. Thus, we pose a new research problem: Can we internalize the searching capabilities to fundamentally enhance the reasoning abilities of a single LLM? This work explores an orthogonal direction focusing on post-training LLMs for autoregressive searching (i.e., an extended reasoning process with self-reflection and self-exploration of new strategies). To achieve this, we propose the Chain-of-Action-Thought (COAT) reasoning and a two-stage training paradigm: 1) a small-scale format tuning stage to internalize the COAT reasoning format and 2) a large-scale self-improvement stage leveraging reinforcement learning. Our approach results in Satori, a 7B LLM trained on open-source models and data. Extensive empirical evaluations demonstrate that Satori achieves state-of-the-art performance on mathematical reasoning benchmarks while exhibits strong generalization to out-of-domain tasks. Code, data, and models will be fully open-sourced.

[Arxiv](https://arxiv.org/abs/2502.02508)