# 通用令牌压缩在多模态大型语言模型中的应用：从可解释性的角度

发布时间：2025年06月01日

`LLM应用

这篇论文主要探讨了如何优化多模态大型语言模型（MLLMs）的计算效率，特别是通过视觉标记的压缩和选择来提升性能。研究内容涉及模型的应用层面，如标记压缩和推理效率提升，因此归类为LLM应用。` `多模态` `计算机视觉`

> Generic Token Compression in Multimodal Large Language Models from an Explainability Perspective

# 摘要

> 现有的多模态大型语言模型（MLLMs）因处理大量视觉标记而导致计算成本高昂且效率低下。以往研究普遍假设所有视觉标记在LLMs的浅层必不可少，因此标记压缩通常发生在中间层。然而，我们发现了一个有趣的现象：通过合理选择，标记压缩甚至可以在LLM的输入阶段实现，且几乎不影响性能。具体而言，解释性方法能够有效评估每个视觉标记相对于给定指令的重要性，从而为标记压缩提供有力指导。此外，我们提出了一种创新方法：通过学习LLM第一层注意力图到解释结果的映射，避免了完整的推理过程，从而提升实际部署效率。令人惊喜的是，这种映射可以通过一个简单轻量的卷积网络实现，训练高效且无需依赖MLLMs。在涵盖10个图像和视频基准数据集的全面实验中，我们的方法在Qwen2-VL、LLaVA-OneVision 和 VILA1.5 这三个领先MLLMs上均表现出色，例如在剪枝50%视觉标记的同时，仍能保持超过96%的原始性能。此外，该方法展现出强大的泛化能力，即使推理中的标记数量远超训练时的数量，依然表现优异。

> Existing Multimodal Large Language Models (MLLMs) process a large number of visual tokens, leading to significant computational costs and inefficiency. Previous works generally assume that all visual tokens are necessary in the shallow layers of LLMs, and therefore token compression typically occurs in intermediate layers. In contrast, our study reveals an interesting insight: with proper selection, token compression is feasible at the input stage of LLM with negligible performance loss. Specifically, we reveal that explainability methods can effectively evaluate the importance of each visual token with respect to the given instruction, which can well guide the token compression. Furthermore, we propose to learn a mapping from the attention map of the first LLM layer to the explanation results, thereby avoiding the need for a full inference pass and facilitating practical deployment. Interestingly, this mapping can be learned using a simple and lightweight convolutional network, whose training is efficient and independent of MLLMs. Extensive experiments on 10 image and video benchmarks across three leading MLLMs (Qwen2-VL, LLaVA-OneVision, and VILA1.5) demonstrate the effectiveness of our approach, e.g., pruning 50% visual tokens while retaining more than 96% of the original performance across all benchmarks for all these three MLLMs. It also exhibits strong generalization, even when the number of tokens in inference far exceeds that used in training.

[Arxiv](https://arxiv.org/abs/2506.01097)