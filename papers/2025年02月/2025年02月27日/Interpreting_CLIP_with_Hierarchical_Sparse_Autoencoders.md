# 基于分层稀疏自动编码器的CLIP模型解释方法

发布时间：2025年02月27日

`其他` `计算机视觉` `多模态学习`

> Interpreting CLIP with Hierarchical Sparse Autoencoders

# 摘要

> 稀疏自动编码器（SAEs）在神经网络中能够有效检测和引导可解释特征，尤其在理解复杂的多模态表示方面具有独特潜力。由于其揭示可解释特征的能力，SAEs在分析大规模视觉-语言模型（如CLIP和SigLIP）时显得尤为重要。尽管这些模型是现代系统的核心组成部分，但它们的解释和控制仍具挑战性。然而，现有的SAE方法在同时优化重构质量和稀疏性方面存在局限，主要依赖于激活抑制或严格的稀疏性约束。针对这一问题，我们提出了名为Matryoshka SAE（MSAE）的创新架构，它能够同时学习多粒度的层次化表示，从而实现对重构质量和稀疏性的直接优化，无需在两者之间妥协。MSAE在CLIP上实现了重构质量和稀疏性之间的新最优Pareto前沿，达到了0.99的余弦相似度和小于0.1的未解释方差比例，同时保持约80%的稀疏性。最后，我们展示了MSAE作为解释和控制CLIP的强大工具，通过从其表示中提取超过120个语义概念，实现了下游任务（如CelebA）中的基于概念的相似性搜索和偏差分析。

> Sparse autoencoders (SAEs) are useful for detecting and steering interpretable features in neural networks, with particular potential for understanding complex multimodal representations. Given their ability to uncover interpretable features, SAEs are particularly valuable for analyzing large-scale vision-language models (e.g., CLIP and SigLIP), which are fundamental building blocks in modern systems yet remain challenging to interpret and control. However, current SAE methods are limited by optimizing both reconstruction quality and sparsity simultaneously, as they rely on either activation suppression or rigid sparsity constraints. To this end, we introduce Matryoshka SAE (MSAE), a new architecture that learns hierarchical representations at multiple granularities simultaneously, enabling a direct optimization of both metrics without compromise. MSAE establishes a new state-of-the-art Pareto frontier between reconstruction quality and sparsity for CLIP, achieving 0.99 cosine similarity and less than 0.1 fraction of variance unexplained while maintaining ~80% sparsity. Finally, we demonstrate the utility of MSAE as a tool for interpreting and controlling CLIP by extracting over 120 semantic concepts from its representation to perform concept-based similarity search and bias analysis in downstream tasks like CelebA.

[Arxiv](https://arxiv.org/abs/2502.20578)