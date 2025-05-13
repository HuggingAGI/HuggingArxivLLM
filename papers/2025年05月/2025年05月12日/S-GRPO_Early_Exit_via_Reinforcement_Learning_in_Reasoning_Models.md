# # S-GRPO：基于强化学习的推理模型提前退出机制

发布时间：2025年05月12日

`LLM应用` `人工智能` `推理模型`

> S-GRPO: Early Exit via Reinforcement Learning in Reasoning Models

# 摘要

> 随着测试时间缩放 (Test-Time Scaling) 成为大型语言模型领域的研究热点，研究者们致力于通过延长链式思维 (CoT) 生成长度来提升模型的推理能力，以达到接近 Deepseek R1 等推理模型的效果。然而，近期研究表明，包括 Qwen3 在内的推理模型在 CoT 生成过程中普遍存在过度冗余的思考链问题。这一“过度思考”现象的根源在于传统基于结果奖励的强化学习方法忽视了对中间推理步骤的系统性调控。针对这一问题，本研究提出了一种新型强化学习方法——串行-组衰减奖励策略优化 (S-GRPO)，旨在赋予模型判断推理步骤充分性的能力，从而触发 CoT 生成的早期退出机制。具体而言，与传统的 GRPO 方法并行采样多个可能完成 (并行组) 不同，我们采用串行方式，在一个 CoT 生成过程中选择多个时间点，分别允许模型在不同时间点退出思考并直接生成答案 (串行组)。对于串行组中的正确答案，我们根据其生成时间点赋予衰减奖励，即后期位置的奖励较低，以此强化模型在早期阶段生成高质量答案并提前退出思考的行为。实验结果表明，S-GRPO 方法与现有主流推理模型（如 Qwen3 和 Deepseek-distill 模型）具有良好的兼容性，在 GSM8K、AIME 2024、AMC 2023、MATH-500 和 GPQA Diamond 等基准测试中，实现了 35.4% ~ 61.1% 的序列长度缩减，同时将推理准确率提升了 0.72% ~ 6.08%。

> As Test-Time Scaling emerges as an active research focus in the large language model community, advanced post-training methods increasingly emphasize extending chain-of-thought (CoT) generation length, thereby enhancing reasoning capabilities to approach Deepseek R1-like reasoning models. However, recent studies reveal that reasoning models (even Qwen3) consistently exhibit excessive thought redundancy in CoT generation. This overthinking problem stems from conventional outcome-reward reinforcement learning's systematic neglect in regulating intermediate reasoning steps. This paper proposes Serial-Group Decaying-Reward Policy Optimization (namely S-GRPO), a novel reinforcement learning method that empowers models with the capability to determine the sufficiency of reasoning steps, subsequently triggering early exit of CoT generation. Specifically, unlike GRPO, which samples multiple possible completions (parallel group) in parallel, we select multiple temporal positions in the generation of one CoT to allow the model to exit thinking and instead generate answers (serial group), respectively. For the correct answers in a serial group, we assign rewards that decay according to positions, with lower rewards towards the later ones, thereby reinforcing the model's behavior to generate higher-quality answers at earlier phases with earlier exits of thinking. Empirical evaluations demonstrate compatibility with state-of-the-art reasoning models, including Qwen3 and Deepseek-distill models, achieving 35.4% ~ 61.1\% sequence length reduction with 0.72% ~ 6.08% accuracy improvements across GSM8K, AIME 2024, AMC 2023, MATH-500, and GPQA Diamond benchmarks.

[Arxiv](https://arxiv.org/abs/2505.07686)