# 强化学习新方法：GRPO-CARE——感知一致性的多模态推理

发布时间：2025年06月19日

`LLM理论` `视频理解` `多模态`

> GRPO-CARE: Consistency-Aware Reinforcement Learning for Multimodal Reasoning

# 摘要

> 近年来，强化学习方法在大型语言模型（LLMs）中引领了思维链推理的显著进步，但其在多模态LLMs（MLLMs）中的应用尚未得到探索。针对现有MLLM后训练方法缺乏严格评估的问题，我们提出了SEED-Bench-R1基准测试，该基准包含复杂的现实世界视频，要求模型具备感知与推理能力的均衡发展。SEED-Bench-R1提供了大规模训练集，并通过三个逐步升高的挑战场景——同分布、跨环境和跨环境-任务场景——来评估模型的泛化能力。

基于SEED-Bench-R1的研究发现，标准GRPO虽能提升答案准确性，却常常削弱推理步骤与答案之间的逻辑连贯性，仅有57.9%的连贯性达成率。这一现象源于奖励信号仅关注最终答案，鼓励模型采取捷径，同时严格的KL惩罚项限制了模型的探索空间。为解决这一问题，我们提出了GRPO-CARE，一种注重一致性强化学习的框架，在无需显式监督的情况下同时优化答案正确性和推理连贯性。

GRPO-CARE采用双层奖励机制：（1）基于答案正确性的基础奖励，（2）自适应一致性奖励，通过比较模型的推理到答案的似然（借助缓慢演进的参考模型）与群体同侪来计算。这一双重机制放大了对既正确又逻辑连贯的推理路径的奖励。通过将KL惩罚项替换为自适应奖励，GRPO-CARE在SEED-Bench-R1上超越了标准GRPO，最难评估级别的性能提升了6.7%，连贯性提升了24.5%。此外，该框架展现出强大的迁移能力，显著提升了模型在各类视频理解基准测试中的表现。

我们的工作贡献了一个系统性设计的基准测试和一个可泛化的后训练框架，推动了更可解释和更稳健的MLLMs的发展。

> Recent reinforcement learning approaches, such as outcome-supervised GRPO, have advanced Chain-of-Thought reasoning in large language models (LLMs), yet their adaptation to multimodal LLMs (MLLMs) is unexplored. To address the lack of rigorous evaluation for MLLM post-training methods, we introduce SEED-Bench-R1, a benchmark with complex real-world videos requiring balanced perception and reasoning. It offers a large training set and evaluates generalization across three escalating challenges: in-distribution, cross-environment, and cross-environment-task scenarios. Using SEED-Bench-R1, we find that standard GRPO, while improving answer accuracy, often reduces logical coherence between reasoning steps and answers, with only a 57.9% consistency rate. This stems from reward signals focusing solely on final answers, encouraging shortcuts, and strict KL penalties limiting exploration.To address this, we propose GRPO-CARE, a consistency-aware RL framework optimizing both answer correctness and reasoning coherence without explicit supervision. GRPO-CARE introduces a two-tiered reward: (1) a base reward for answer correctness, and (2) an adaptive consistency bonus, computed by comparing the model's reasoning-to-answer likelihood (via a slowly-evolving reference model) against group peers.This dual mechanism amplifies rewards for reasoning paths that are both correct and logically consistent. Replacing KL penalties with this adaptive bonus, GRPO-CARE outperforms standard GRPO on SEED-Bench-R1, achieving a 6.7% performance gain on the hardest evaluation level and a 24.5% improvement in consistency. It also shows strong transferability, improving model performance across diverse video understanding benchmarks. Our work contributes a systematically designed benchmark and a generalizable post-training framework, advancing the development of more interpretable and robust MLLMs.

[Arxiv](https://arxiv.org/abs/2506.16141)