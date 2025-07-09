# # 潜在推理综述
关于潜在推理的研究综述

发布时间：2025年07月08日

`LLM理论` `大型语言模型` `认知推理`

> A Survey on Latent Reasoning

# 摘要

> 大型语言模型（LLMs）在推理能力方面表现卓越，尤其在显式链式思维（CoT）推理的引导下，能够清晰展示中间推理步骤。虽然CoT推理提升了模型的可解释性和准确性，但其依赖于自然语言推理的特性限制了模型的表达范围。潜在推理通过在模型的连续隐藏状态中完成多步推理，从而突破了这一限制，无需逐个标记的监督。为了推动潜在推理研究的发展，本综述对这一新兴领域进行了全面概述。我们首先探讨了神经网络层在推理中的基础性作用，强调了层级化表示如何支持复杂转换。接着，我们深入研究了多种潜在推理方法，包括基于激活的递归、隐藏状态传播，以及通过压缩或内化显式推理轨迹的微调策略。最后，我们讨论了先进范式，如通过掩码扩散模型实现的无限深度潜在推理，这使得推理过程具备全局一致性和可逆性。通过整合这些视角，我们旨在阐明潜在推理的概念框架，并为大型语言模型认知领域的前沿研究指明未来方向。相关GitHub仓库，收集了最新的论文和资源，可访问：https://github.com/multimodal-art-projection/LatentCoT-Horizon/。

> Large Language Models (LLMs) have demonstrated impressive reasoning capabilities, especially when guided by explicit chain-of-thought (CoT) reasoning that verbalizes intermediate steps. While CoT improves both interpretability and accuracy, its dependence on natural language reasoning limits the model's expressive bandwidth. Latent reasoning tackles this bottleneck by performing multi-step inference entirely in the model's continuous hidden state, eliminating token-level supervision. To advance latent reasoning research, this survey provides a comprehensive overview of the emerging field of latent reasoning. We begin by examining the foundational role of neural network layers as the computational substrate for reasoning, highlighting how hierarchical representations support complex transformations. Next, we explore diverse latent reasoning methodologies, including activation-based recurrence, hidden state propagation, and fine-tuning strategies that compress or internalize explicit reasoning traces. Finally, we discuss advanced paradigms such as infinite-depth latent reasoning via masked diffusion models, which enable globally consistent and reversible reasoning processes. By unifying these perspectives, we aim to clarify the conceptual landscape of latent reasoning and chart future directions for research at the frontier of LLM cognition. An associated GitHub repository collecting the latest papers and repos is available at: https://github.com/multimodal-art-projection/LatentCoT-Horizon/.

[Arxiv](https://arxiv.org/abs/2507.06203)