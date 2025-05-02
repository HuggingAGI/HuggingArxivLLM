# T2I-R1：通过协作的语义级和词元级CoT机制强化图像生成

发布时间：2025年05月01日

`LLM应用` `视觉生成`

> T2I-R1: Reinforcing Image Generation with Collaborative Semantic-level and Token-level CoT

# 摘要

> 近期大型语言模型的进展展示了链式推理（CoT）和强化学习（RL）如何提升性能。然而，将此类推理策略应用于视觉生成领域仍鲜有探索。本文中，我们提出了T2I-R1，一款创新的增强推理文本到图像生成模型，该模型由强化学习驱动，并采用双层链式推理过程。具体而言，我们识别出可用于增强生成不同阶段的两个层次的CoT：(1) 语义层次的CoT，用于提示的高层规划；(2) 令牌层次的CoT，用于基于补丁的生成过程中低层像素处理。为了更好地协调这两个层次的CoT，我们引入了BiCoT-GRPO，它结合了生成奖励的集成，在同一训练步骤中无缝优化两种生成CoT。通过将我们的推理策略应用于基线模型Janus-Pro，我们在T2I-CompBench上实现了13%的性能提升，在WISE基准上实现了19%的提升，甚至超越了最先进的模型FLUX。代码可在：https://github.com/CaraJ7/T2I-R1获取

> Recent advancements in large language models have demonstrated how chain-of-thought (CoT) and reinforcement learning (RL) can improve performance. However, applying such reasoning strategies to the visual generation domain remains largely unexplored. In this paper, we present T2I-R1, a novel reasoning-enhanced text-to-image generation model, powered by RL with a bi-level CoT reasoning process. Specifically, we identify two levels of CoT that can be utilized to enhance different stages of generation: (1) the semantic-level CoT for high-level planning of the prompt and (2) the token-level CoT for low-level pixel processing during patch-by-patch generation. To better coordinate these two levels of CoT, we introduce BiCoT-GRPO with an ensemble of generation rewards, which seamlessly optimizes both generation CoTs within the same training step. By applying our reasoning strategies to the baseline model, Janus-Pro, we achieve superior performance with 13% improvement on T2I-CompBench and 19% improvement on the WISE benchmark, even surpassing the state-of-the-art model FLUX.1. Code is available at: https://github.com/CaraJ7/T2I-R1

[Arxiv](https://arxiv.org/abs/2505.00703)