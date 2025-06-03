# 用于推测解码的 Mamba Drafters

发布时间：2025年06月01日

`LLM应用`

> Mamba Drafters for Speculative Decoding

# 摘要

> 投机解码已成为加速大语言模型生成的有力工具，它通过快速草稿生成器实现加速，同时保持与目标模型分布的一致性。然而，现有方法面临一个关键挑战：外部草稿生成器虽然灵活，但草稿生成速度较慢；而自我推测方法虽然针对目标模型进行了优化，但需要重新训练。在本文中，我们提出了一种基于Mamba的新型草稿生成器，Mamba是一种先进的状态空间模型（SSM），它巧妙地结合了两种方法的优点。通过充分利用SSM的线性结构，我们的方法成功规避了传统基于Transformer方法中固有的二次复杂度，从而实现了更快的草稿生成和更低的内存消耗，同时保持了与多种目标模型的兼容性。此外，我们还开发了一种创新的测试时间树搜索算法，进一步提升了生成高质量草稿候选的效率。实验结果表明，基于Mamba的生成器不仅超越了现有外部生成方法的性能，而且在内存占用更低的情况下，其表现可与最先进的自我推测方法相媲美，同时保持了跨模型的适应能力。

> Speculative decoding has emerged as a promising approach to accelerating large language model (LLM) generation using a fast drafter while maintaining alignment with the target model's distribution. However, existing approaches face a trade-off: external drafters offer flexibility but can suffer from slower drafting, while self-speculation methods use drafters tailored to the target model but require re-training. In this paper, we introduce novel drafters based on Mamba, a state-of-the-art state space model (SSM), as a solution that combines the best aspects of both approaches. By leveraging the linear structure of SSMs, our approach avoids the quadratic complexity inherent in traditional Transformer-based methods, enabling faster drafting and lower memory usage while maintaining the flexibility to work across different target models. We further enhance efficiency with a novel test-time tree search algorithm for generating high-quality draft candidates. Our empirical evaluation demonstrates that Mamba-based drafters not only outperform existing external drafting methods but are also comparable to state-of-the-art self-speculation approaches while using less memory and maintaining their cross-model adaptability.

[Arxiv](https://arxiv.org/abs/2506.01206)