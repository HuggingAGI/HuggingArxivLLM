# 推理时几乎确保大型语言模型的安全对齐

发布时间：2025年02月03日

`LLM理论

理由：这篇论文提出了一种新的推理时对齐方法，旨在确保大型语言模型（LLMs）生成安全的响应。该方法通过将安全生成框架化为LLM潜在空间中的约束马尔可夫决策过程，并提供正式的安全保证。论文的核心在于理论上的创新和方法论的提出，而不是具体的应用或实现。因此，它更适合归类为“LLM理论”。` `人工智能`

> Almost Surely Safe Alignment of Large Language Models at Inference-Time

# 摘要

> 即使是强大的大型语言模型（LLMs）也可能产生有偏见或不安全的响应，而像RLHF这样的对齐技术虽然能缓解这一问题，但成本高且容易过拟合，因为它们需要重新训练LLM。本文提出了一种新颖的推理时对齐方法，确保LLMs几乎肯定生成安全的响应（概率接近1）。我们将推理时响应的安全生成框架化为LLM潜在空间中的约束马尔可夫决策过程，并通过增加一个安全状态来跟踪安全约束的演变，从而在潜在空间中解决MDP时提供正式的安全保证。基于此，我们提出了InferenceGuard，这是一种无需修改模型权重即可安全对齐LLMs的实用方法。实验表明，InferenceGuard在平衡安全性和任务性能方面表现出色，生成的安全和对齐响应优于现有推理时对齐方法。

> Even highly capable large language models (LLMs) can produce biased or unsafe responses, and alignment techniques, such as RLHF, aimed at mitigating this issue, are expensive and prone to overfitting as they retrain the LLM. This paper introduces a novel inference-time alignment approach that ensures LLMs generate safe responses almost surely, i.e., with a probability approaching one. We achieve this by framing the safe generation of inference-time responses as a constrained Markov decision process within the LLM's latent space. Crucially, we augment a safety state that tracks the evolution of safety constraints and enables us to demonstrate formal safety guarantees upon solving the MDP in the latent space. Building on this foundation, we propose InferenceGuard, a practical implementation that safely aligns LLMs without modifying the model weights. Empirically, we demonstrate InferenceGuard effectively balances safety and task performance, outperforming existing inference-time alignment methods in generating safe and aligned responses.

[Arxiv](https://arxiv.org/abs/2502.01208)