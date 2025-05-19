# 掌握思考时机：利用多阶段强化学习培养R1风格模型的自适应推理能力

发布时间：2025年05月16日

`LLM应用

理由：这篇论文探讨了如何优化大型语言模型（LLM）在推理过程中的效率和准确性，提出了一种自适应思考框架AutoThink，通过多阶段强化学习动态调整推理策略。这属于将LLM应用于实际任务并优化其性能的范畴，因此归类为LLM应用。` `人工智能` `模型优化`

> Learning When to Think: Shaping Adaptive Reasoning in R1-Style Models via Multi-Stage RL

# 摘要

> 大型推理模型（LRMs）擅长生成明确的分步推理序列，但在处理简单问题时，这种详细的推理方式可能带来显著的计算开销和延迟。为了解决这一“过度思考”问题，我们探索了如何赋予LRMs自适应思考能力：即根据问题复杂度动态决定是否进行显式推理。基于R1风格的蒸馏模型，我们发现，在提示中插入一个简单的省略号（"..."）可以随机触发思考模式或无思考模式，揭示了推理行为中潜在的可控性。利用这一特性，我们提出了AutoThink，这是一个多阶段强化学习（RL）框架，通过分阶段奖励塑造逐步优化推理策略。AutoThink学会了仅在必要时调用显式推理，而对于更简单的任务则默认生成简洁的回答。在五个主流数学基准上的实验表明，与近期的提示和基于RL的剪枝方法相比，AutoThink在准确性和效率之间实现了更好的平衡。它可以无缝集成到任何R1风格的模型中，包括蒸馏和进一步微调的变体。值得注意的是，在DeepSeek-R1-Distill-Qwen-1.5B上，AutoThink将相对准确性提高了6.4%，同时将token使用量减少了52%，为LRMs建立了一个可扩展且自适应的推理范式。

> Large reasoning models (LRMs) are proficient at generating explicit, step-by-step reasoning sequences before producing final answers. However, such detailed reasoning can introduce substantial computational overhead and latency, particularly for simple problems. To address this over-thinking problem, we explore how to equip LRMs with adaptive thinking capabilities: enabling them to dynamically decide whether or not to engage in explicit reasoning based on problem complexity. Building on R1-style distilled models, we observe that inserting a simple ellipsis ("...") into the prompt can stochastically trigger either a thinking or no-thinking mode, revealing a latent controllability in the reasoning behavior. Leveraging this property, we propose AutoThink, a multi-stage reinforcement learning (RL) framework that progressively optimizes reasoning policies via stage-wise reward shaping. AutoThink learns to invoke explicit reasoning only when necessary, while defaulting to succinct responses for simpler tasks. Experiments on five mainstream mathematical benchmarks demonstrate that AutoThink achieves favorable accuracy-efficiency trade-offs compared to recent prompting and RL-based pruning methods. It can be seamlessly integrated into any R1-style model, including both distilled and further fine-tuned variants. Notably, AutoThink improves relative accuracy by 6.4 percent while reducing token usage by 52 percent on DeepSeek-R1-Distill-Qwen-1.5B, establishing a scalable and adaptive reasoning paradigm for LRMs.

[Arxiv](https://arxiv.org/abs/2505.10832)