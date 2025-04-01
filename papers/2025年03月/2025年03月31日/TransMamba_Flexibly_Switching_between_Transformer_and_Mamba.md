# TransMamba：灵活切换Transformer与Mamba

发布时间：2025年03月31日

`LLM理论`

> TransMamba: Flexibly Switching between Transformer and Mamba

# 摘要

> Transformer是现代大型语言模型的基石，但其二次计算复杂度限制了其在长序列处理中的效率。近期，Mamba（一种具有线性复杂度的状态空间模型（SSM））的进展带来了令人鼓舞的效率提升，但其上下文学习和多任务泛化能力不稳定。本文提出了一种名为TransMamba的新框架，通过共享参数矩阵（例如QKV和CBx）将Transformer和Mamba统一起来，因此可以在不同令牌长度和层之间动态切换注意力机制和SSM机制。我们设计了记忆转换器（Memory converter），通过将注意力输出转换为与SSM兼容的状态，实现了Transformer和Mamba之间的无缝衔接，确保在转换点（TransPoints）处信息流的连续性。我们还深入探讨了TransPoint的调度策略，以进一步改进模型性能。通过广泛的实验，我们证明了TransMamba在训练效率和性能上优于基线模型，并验证了Transformer和Mamba范式之间更深层次的一致性，为下一代序列建模提供了一种可扩展的解决方案。


> Transformers are the cornerstone of modern large language models, but their quadratic computational complexity limits efficiency in long-sequence processing. Recent advancements in Mamba, a state space model (SSM) with linear complexity, offer promising efficiency gains but suffer from unstable contextual learning and multitask generalization. This paper proposes TransMamba, a novel framework that unifies Transformer and Mamba through shared parameter matrices (e.g., QKV and CBx), and thus could dynamically switch between attention and SSM mechanisms at different token lengths and layers. We design the Memory converter to bridge Transformer and Mamba by converting attention outputs into SSM-compatible states, ensuring seamless information flow at TransPoints where the transformation happens. The TransPoint scheduling is also thoroughly explored for further improvements. We conducted extensive experiments demonstrating that TransMamba achieves superior training efficiency and performance compared to baselines, and validated the deeper consistency between Transformer and Mamba paradigms, offering a scalable solution for next-generation sequence modeling.

[Arxiv](https://arxiv.org/abs/2503.24067)