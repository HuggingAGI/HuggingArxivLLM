# # Leanabell-Prover：形式化推理中的训练后扩展研究

发布时间：2025年04月08日

`LLM应用` `自动定理证明`

> Leanabell-Prover: Posttraining Scaling in Formal Reasoning

# 摘要

> # 摘要
近期，大型语言模型 (LLMs) 在自动定理证明 (ATP) 领域的突破性进展，展现了利用 Lean 4 代码进行形式推理的潜力。然而，与 Open AI O1/O3 和 Deepseek R1 的革命性变化不同，ATP 尚未因近期的后训练扩展而发生根本性变革。本研究全面探索了 ATP 的后训练过程，旨在使其与自然语言推理模型的突破性进展相接轨。首先，我们采用包含大量陈述-证明对的混合数据集，对当前的 ATP 模型进行持续训练，并加入旨在模拟人类推理和假设优化的认知行为数据。其次，我们借助 Lean 4 编译器返回的结果奖励，探索强化学习的应用。通过我们的持续训练和强化学习流程，我们成功提升了现有的形式证明器，包括 DeepSeek-Prover-v1.5 和 Goedel-Prover，使其在全证明生成领域达到了业界领先水平。例如，在 MiniF2F 上，我们实现了 59.8% 的通过率 (pass@32)。这是一个正在进行的项目，我们将逐步更新我们的研究成果，并发布我们的数据和训练细节。

> Recent advances in automated theorem proving (ATP) through LLMs have highlighted the potential of formal reasoning with Lean 4 codes. However, ATP has not yet be revolutionized by the recent posttraining scaling as demonstrated by Open AI O1/O3 and Deepseek R1. In this work, we investigate the entire posttraining of ATP, aiming to align it with breakthroughs in reasoning models in natural languages.To begin, we continual train current ATP models with a hybrid dataset, which consists of numerous statement-proof pairs, and additional data aimed at incorporating cognitive behaviors that emulate human reasoning and hypothesis refinement. Next, we explore reinforcement learning with the use of outcome reward returned by Lean 4 compiler. Through our designed continual training and reinforcement learning processes, we have successfully improved existing formal provers, including both DeepSeek-Prover-v1.5 and Goedel-Prover, achieving state-of-the-art performance in the field of whole-proof generation. For example, we achieve a 59.8% pass rate (pass@32) on MiniF2F. This is an on-going project and we will progressively update our findings, release our data and training details.

[Arxiv](https://arxiv.org/abs/2504.06122)