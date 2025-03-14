# # 组合式子空间表示微调的自适应大型语言模型

发布时间：2025年03月13日

`LLM理论` `人工智能`

> Compositional Subspace Representation Fine-tuning for Adaptive Large Language Models

# 摘要

> 将大型语言模型应用于多任务时，往往会出现跨技能干扰，即提升一项技能可能削弱另一项技能的表现。虽然像LoRA这样的方法在权重级别引入了正交性约束，但它们并未完全解决隐藏状态表示中的干扰问题。为此，我们提出了一种基于表示的新方法——组合子空间表示微调（CS-ReFT）。该方法通过学习多个正交子空间变换，每个变换专注于特定技能，并借助轻量级路由器进行组合。与传统方法在权重矩阵中进行修改不同，CS-ReFT将子空间修改隔离在隐藏状态中，从而更有效地避免了跨任务冲突。在AlpacaEval基准测试中，CS-ReFT应用于Llama-2-7B模型，取得了93.94%的胜率，超越了GPT-3.5 Turbo（86.30%），同时仅占模型参数的0.0098%。这一结果表明，通过简单路由器组合的专用表示编辑，能够在几乎不增加额外开销的情况下，显著提升多任务指令遵循能力。

> Adapting large language models to multiple tasks can cause cross-skill interference, where improvements for one skill degrade another. While methods such as LoRA impose orthogonality constraints at the weight level, they do not fully address interference in hidden-state representations. We propose Compositional Subspace Representation Fine-tuning (CS-ReFT), a novel representation-based approach that learns multiple orthonormal subspace transformations, each specializing in a distinct skill, and composes them via a lightweight router. By isolating these subspace edits in the hidden state, rather than weight matrices, CS-ReFT prevents cross-task conflicts more effectively. On the AlpacaEval benchmark, applying CS-ReFT to Llama-2-7B achieves a 93.94% win rate, surpassing GPT-3.5 Turbo (86.30%) while requiring only 0.0098% of model parameters. These findings show that specialized representation edits, composed via a simple router, significantly enhance multi-task instruction following with minimal overhead.

[Arxiv](https://arxiv.org/abs/2503.10617)