# Open-Reasoner-Zero：开源实现基础模型强化学习规模化的创新方案

发布时间：2025年03月31日

`LLM应用`

> Open-Reasoner-Zero: An Open Source Approach to Scaling Up Reinforcement Learning on the Base Model

# 摘要

> 我们很高兴推出 Open-Reasoner-Zero，首个专注于大规模推理的RL训练开源实现，致力于打造高效、简洁且易于使用的解决方案。通过大量实验，我们发现，采用 vanilla PPO 结合 GAE（λ=1，γ=1）和简单的基于规则的奖励机制，无需任何 KL 正则化，即可实现响应长度和基准性能的显著提升，与 DeepSeek-R1-Zero 中的现象相似。基于与 DeepSeek-R1-Zero-Qwen-32B 相同的基模型，我们的实现不仅在 AIME2024、MATH500 和 GPQA 钻石基准测试中表现优异，更在效率上实现了重大突破——仅需 DeepSeek-R1-Zero 管道十分之一的训练步骤。秉承开源精神，我们公开了完整的源代码、参数设置、训练数据和各种规模的模型权重，以期为社区贡献更多价值。

> We introduce Open-Reasoner-Zero, the first open source implementation of large-scale reasoning-oriented RL training focusing on scalability, simplicity and accessibility. Through extensive experiments, we demonstrate that a minimalist approach, vanilla PPO with GAE ($λ=1$, $γ=1$) and straightforward rule-based rewards, without any KL regularization, is sufficient to scale up both response length and benchmark performance, similar to the phenomenon observed in DeepSeek-R1-Zero. Using the same base model as DeepSeek-R1-Zero-Qwen-32B, our implementation achieves superior performance on AIME2024, MATH500, and the GPQA Diamond benchmark while demonstrating remarkable efficiency -- requiring only a tenth of the training steps, compared to DeepSeek-R1-Zero pipeline. In the spirit of open source, we release our source code, parameter settings, training data, and model weights across various sizes.

[Arxiv](https://arxiv.org/abs/2503.24290)