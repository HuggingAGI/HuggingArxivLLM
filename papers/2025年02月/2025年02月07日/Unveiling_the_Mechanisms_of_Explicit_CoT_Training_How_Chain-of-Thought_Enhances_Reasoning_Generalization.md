# 显式CoT训练机制揭秘：链式思维如何提升推理泛化能力

发布时间：2025年02月07日

`LLM理论` `人工智能`

> Unveiling the Mechanisms of Explicit CoT Training: How Chain-of-Thought Enhances Reasoning Generalization

# 摘要

> # 摘要
通过高质量的思维链（Chain-of-Thought, CoT）标注训练大型语言模型（LLMs）已成为一种广泛应用的策略，因其显著提升了模型的推理能力。为了全面理解这一方法，我们提出了两个关键问题：(Q1) 使用CoT进行训练相较于不使用CoT训练有何优势？(Q2) 如果存在优势，显式CoT训练背后的作用机制是什么？由于涉及众多因素，分析CoT训练的优势与机制颇具挑战性。为解决这一问题，我们采用清晰且可控的数据分布进行了详细分析，并首次揭示了CoT训练的以下优势：(1) 使用CoT进行训练显著提升了推理的泛化能力，使其从分布内（ID）扩展至分布内（ID）与分布外（OOD）场景，同时加快了收敛速度；(2) 即使CoT训练包含一定范围的错误推理步骤，仍能使模型学习到推理模式，从而实现系统性泛化。我们进一步从电路视角探索其潜在机制：(1) 数据分布（如比率$λ$和模式）在影响模型的系统性泛化中起着关键作用；(2) CoT训练（结合两跳事实）将推理内化为一个两阶段的泛化电路，其中阶段数对应于训练期间的显式推理步骤。我们的发现不仅阐明了显式CoT训练的内在机制，更为调优策略提供了关键见解，以实现LLMs的稳健泛化。


> Training large language models (LLMs) with high-quality Chain-of-Thought (CoT) annotations has become a widely adopted strategy due to its significant enhancement of reasoning capabilities. To fully comprehend this approach, two questions naturally arise: (Q1) What advantages does training with CoT offer compared to training without CoT? (Q2) If there are advantages, what are the underlying mechanisms of explicit CoT training? Analyzing the advantages and mechanisms of CoT training is challenging due to the many factors involved. To address this, we conduct a detailed analysis using clear and controllable data distributions and, for the first time, reveal that CoT training offers the following advantages: (1) Training with CoT markedly improves reasoning generalization, extending it from in-distribution (ID) to both ID and out-of-distribution (OOD) scenarios, while also speeding up convergence; (2) Even when training with CoT includes a certain range of erroneous reasoning steps, it still enables the model to learn reasoning patterns, leading to systematic generalization. We further explore the underlying mechanisms from a circuit perspective: (1) The data distribution (e.g., ratio $λ$ and pattern) plays a crucial role in influencing the model's systematic generalization; (2) CoT training (with two-hop facts) internalizes reasoning into a two-stage generalizing circuit, where the number of stages corresponds to the explicit reasoning steps during training. Our findings elucidate the mechanisms underlying explicit CoT training and offer critical insights into tuning strategies for LLMs to achieve robust generalization.

[Arxiv](https://arxiv.org/abs/2502.04667)