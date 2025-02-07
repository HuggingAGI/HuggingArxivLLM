# 超越 Token 压缩：MLLMs 中高效视觉处理的无训练减少框架

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）的架构优化问题，特别是如何在不牺牲性能的情况下减少计算资源的需求。论文提出了新的分析框架和方法（如空心注意力和动态FFN），并进行了实验验证。这些工作属于对大型语言模型的理论研究和架构改进，因此归类为“LLM理论”。` `计算机视觉`

> Beyond Token Compression: A Training-Free Reduction Framework for Efficient Visual Processing in MLLMs

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）通常采用仅解码器或交叉注意力架构。尽管仅解码器模型在性能上优于交叉注意力模型，但由于对视觉标记进行大量自注意力和FFN操作，其计算资源需求显著更高。这引发了一个问题：能否在保持性能的同时，消除这些高成本操作？为此，我们提出了一种新颖的分析框架，旨在探究仅解码器MLLMs中这些高成本操作的必要性。该框架引入了两大创新：（1）空心注意力，将视觉标记的交互限制在局部注意力范围内，同时保持视觉-文本关联；（2）探针激活的动态FFN，选择性地激活视觉标记的FFN参数。这两种方法无需微调，极大提升了分析效率。为评估在不同比例层中应用这些减少的影响，我们开发了一种贪婪搜索方法，显著缩小了搜索空间。实验表明，将我们的减少应用于约一半的层，不仅保持了模型性能，有时甚至有所提升，揭示了当前架构中存在显著的计算冗余。此外，我们的方法与现有标记压缩技术正交，可进一步结合以实现更大的计算减少。这些发现为设计更高效的未来MLLMs提供了宝贵见解。代码将在https://github.com/L-Hugh/Beyond-Token-Compression公开。

> Multimodal Large Language Models (MLLMs) are typically based on decoder-only or cross-attention architectures. While decoder-only MLLMs outperform their cross-attention counterparts, they require significantly higher computational resources due to extensive self-attention and FFN operations on visual tokens. This raises the question: can we eliminate these expensive operations while maintaining the performance? To this end, we present a novel analysis framework to investigate the necessity of these costly operations in decoder-only MLLMs. Our framework introduces two key innovations: (1) Hollow Attention, which limits visual token interactions to local attention while maintaining visual-text associations, and (2) Probe-Activated Dynamic FFN, which selectively activates FFN parameters for visual tokens. Both methods do not require fine-tuning, which significantly enhances analysis efficiency. To assess the impact of applying these reductions across different proportions of layers, we developed a greedy search method that significantly narrows the search space. Experiments on state-of-the-art MLLMs reveal that applying our reductions to approximately half of the layers not only maintains but sometimes improves model performance, indicating significant computational redundancy in current architectures. Additionally, our method is orthogonal to existing token compression techniques, allowing for further combination to achieve greater computational reduction. Our findings may provide valuable insights for the design of more efficient future MLLMs. Our code will be publicly available at https://github.com/L-Hugh/Beyond-Token-Compression.

[Arxiv](https://arxiv.org/abs/2501.19036)