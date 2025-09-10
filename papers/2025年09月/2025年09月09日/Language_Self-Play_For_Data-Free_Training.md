# 语言自对弈：面向无数据训练

发布时间：2025年09月09日

`强化学习` `基础理论`

> Language Self-Play For Data-Free Training

# 摘要

> 大型语言模型（LLMs）近年来在规模、高质量训练数据及强化学习的驱动下发展迅猛，但这一进展面临根本性瓶颈：模型持续学习需依赖海量数据。为此，本研究提出一种强化学习方法，无需额外数据即可提升模型性能，从而打破这一依赖。该方法基于自博弈的博弈论框架，将模型能力转化为竞争性博弈中的表现，通过模型与自身博弈生成更强策略——我们称之为语言自博弈（LSP）。在指令遵循基准测试中，基于Llama-3.2-3B-Instruct的实验显示：预训练模型仅通过自博弈就能提升挑战性任务的性能，且效果优于数据驱动的基线方法。

> Large language models (LLMs) have advanced rapidly in recent years, driven by scale, abundant high-quality training data, and reinforcement learning. Yet this progress faces a fundamental bottleneck: the need for ever more data from which models can continue to learn. In this work, we propose a reinforcement learning approach that removes this dependency by enabling models to improve without additional data. Our method leverages a game-theoretic framework of self-play, where a model's capabilities are cast as performance in a competitive game and stronger policies emerge by having the model play against itself - a process we call Language Self-Play (LSP). Experiments with Llama-3.2-3B-Instruct on instruction-following benchmarks show that pretrained models can not only enhance their performance on challenging tasks through self-play alone, but can also do so more effectively than data-driven baselines.

[Arxiv](https://arxiv.org/abs/2509.07414)