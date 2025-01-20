# 特征引导激活添加：驾驭大型语言模型的新方法

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要探讨了如何通过激活引导方法来控制大型语言模型（LLM）的行为，并提出了一种新的方法（FGAA）来改进现有的技术。论文的核心在于理论上的创新和方法论的改进，涉及对模型内部机制的理解和优化，因此属于“LLM理论”范畴。` `人工智能`

> Steering Large Language Models with Feature Guided Activation Additions

# 摘要

> # 摘要
有效且可靠地控制大型语言模型（LLM）的行为是一个重大挑战。尽管激活引导方法（通过向模型的隐藏状态添加引导向量）颇具潜力，但现有技术在影响模型输出时往往缺乏精确性和可解释性。我们提出了特征引导激活添加（FGAA），这是一种新颖的激活引导方法，结合了对比激活添加（CAA）和稀疏自编码器目标引导（SAE-TS）的见解。FGAA通过在稀疏自编码器（SAE）的潜在空间中操作，并利用优化技术选择所需的SAE特征，构建了精确的引导向量，从而在保持模型输出一致性的同时，提供了更优的引导效果。在Gemma-2-2B和Gemma-2-9B模型上的多任务评估表明，FGAA在引导效果上优于现有的CAA、SAE解码器引导和SAE-TS方法。此外，我们的研究还揭示了引导规模与模型通用能力之间的重要权衡，这一现象在所有测试的引导方法中均保持一致。

> Effective and reliable control over large language model (LLM) behavior is a significant challenge. While activation steering methods, which add steering vectors to a model's hidden states, are a promising approach, existing techniques often lack precision and interpretability in how they influence model outputs. We introduce Feature Guided Activation Additions (FGAA), a novel activation steering method that leverages insights from Contrastive Activation Addition (CAA) and Sparse Autoencoder-Targeted Steering (SAE-TS). By operating in the latent space of a Sparse Autoencoder (SAE) and employing optimization techniques to select desired SAE features, FGAA constructs precise steering vectors that provide better steering effects while maintaining coherence of steered model outputs. In this regard, evaluations on Gemma-2-2B and Gemma-2-9B models across various steering tasks demonstrate that FGAA outperforms existing steering methods of CAA, SAE decoder steering, and SAE-TS. Our results also highlight important trade-offs between steering scale and general model capabilities that are consistent across all tested steering methods.

[Arxiv](https://arxiv.org/abs/2501.09929)