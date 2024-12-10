# 训练大型语言模型于连续潜在空间里展开推理

发布时间：2024年12月09日

`LLM应用`

> Training Large Language Models to Reason in a Continuous Latent Space

# 摘要

> 大型语言模型（LLMs）受限于在“语言空间”中推理，通常会用思维链（CoT）来展现推理过程，以解决复杂推理问题。但我们觉得，语言空间对推理而言未必总是最佳选择。比如，多数单词标记主要是为了文本的连贯性，并非推理必需，而有些关键标记需要复杂规划，给 LLMs 带来巨大挑战。为探索 LLMs 在不受限的潜在空间中推理的潜力，而非运用自然语言，我们引入了新范式 Coconut（连续思维链）。我们把 LLMs 的最后一个隐藏状态当作推理状态的表示（称为“连续思维”）。不是将其解码为单词标记，而是在连续空间中直接把它作为后续输入嵌入反馈给 LLMs。实验表明，Coconut 能在若干推理任务上有效增强 LLMs。这种新颖的潜在推理范式催生了先进的推理模式：连续思维能够编码多个替代的下一步推理步骤，让模型进行广度优先搜索（BFS）来解决问题，而非像 CoT 那样过早锁定单个确定性路径。在某些规划时需要大量回溯的逻辑推理任务中，Coconut 比 CoT 表现更优，推理时使用的思考标记更少。这些发现彰显了潜在推理的前景，为未来研究提供了宝贵的见解。

> Large language models (LLMs) are restricted to reason in the "language space", where they typically express the reasoning process with a chain-of-thought (CoT) to solve a complex reasoning problem. However, we argue that language space may not always be optimal for reasoning. For example, most word tokens are primarily for textual coherence and not essential for reasoning, while some critical tokens require complex planning and pose huge challenges to LLMs. To explore the potential of LLM reasoning in an unrestricted latent space instead of using natural language, we introduce a new paradigm Coconut (Chain of Continuous Thought). We utilize the last hidden state of the LLM as a representation of the reasoning state (termed "continuous thought"). Rather than decoding this into a word token, we feed it back to the LLM as the subsequent input embedding directly in the continuous space. Experiments show that Coconut can effectively augment the LLM on several reasoning tasks. This novel latent reasoning paradigm leads to emergent advanced reasoning patterns: the continuous thought can encode multiple alternative next reasoning steps, allowing the model to perform a breadth-first search (BFS) to solve the problem, rather than prematurely committing to a single deterministic path like CoT. Coconut outperforms CoT in certain logical reasoning tasks that require substantial backtracking during planning, with fewer thinking tokens during inference. These findings demonstrate the promise of latent reasoning and offer valuable insights for future research.

[Arxiv](https://arxiv.org/abs/2412.06769)