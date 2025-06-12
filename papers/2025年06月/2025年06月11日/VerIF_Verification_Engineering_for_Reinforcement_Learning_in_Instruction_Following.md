# VerIF：强化学习在指令遵循中的验证工程

发布时间：2025年06月11日

`LLM应用

理由：这篇论文探讨了强化学习（RL）在提升大型语言模型（LLMs）指令遵循任务性能中的应用，特别是通过提出一种新的验证方法VerIF。它展示了如何将强化学习应用于模型训练，以提高模型在特定任务中的表现，属于LLM应用的范畴。` `人工智能`

> VerIF: Verification Engineering for Reinforcement Learning in Instruction Following

# 摘要

> 基于可验证奖励的强化学习（RLVR）已成为提升大型语言模型（LLMs）性能的关键技术，其中验证工程发挥着核心作用。然而，指令遵循任务中强化学习的最佳实践仍然未被充分探索。本研究针对强化学习在指令遵循中的验证挑战，提出了一种名为VerIF的验证方法，该方法结合了基于规则的代码验证和来自大型推理模型（如QwQ-32B）的基于LLM的验证。为了支持这一方法，我们构建了一个高质量的指令遵循数据集VerInstruct，其中包含约22,000个实例及其相关的验证信号。我们将VerIF应用于强化学习训练中，对两个模型进行了实验，结果在多个代表性的指令遵循基准测试中取得了显著提升。经过训练的模型在与同类规模模型的对比中达到了最先进的性能，并且很好地泛化到未见过的约束条件。我们进一步观察到，这些模型的通用能力并未受到影响，表明结合VerIF的强化学习可以集成到现有的强化学习方案中，从而提升整体模型性能。我们已在https://github.com/THU-KEG/VerIF公开了数据集、代码和模型，以支持未来的相关研究。

> Reinforcement learning with verifiable rewards (RLVR) has become a key technique for enhancing large language models (LLMs), with verification engineering playing a central role. However, best practices for RL in instruction following remain underexplored. In this work, we explore the verification challenge in RL for instruction following and propose VerIF, a verification method that combines rule-based code verification with LLM-based verification from a large reasoning model (e.g., QwQ-32B). To support this approach, we construct a high-quality instruction-following dataset, VerInstruct, containing approximately 22,000 instances with associated verification signals. We apply RL training with VerIF to two models, achieving significant improvements across several representative instruction-following benchmarks. The trained models reach state-of-the-art performance among models of comparable size and generalize well to unseen constraints. We further observe that their general capabilities remain unaffected, suggesting that RL with VerIF can be integrated into existing RL recipes to enhance overall model performance. We have released our datasets, codes, and models to facilitate future research at https://github.com/THU-KEG/VerIF.

[Arxiv](https://arxiv.org/abs/2506.09942)