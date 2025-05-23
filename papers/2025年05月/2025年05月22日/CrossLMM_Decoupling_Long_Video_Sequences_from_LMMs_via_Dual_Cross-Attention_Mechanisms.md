# CrossLMM：利用双交叉注意力机制从 LMMs 中分离长视频序列

发布时间：2025年05月22日

`LLM应用` `视频处理` `多模态模型`

> CrossLMM: Decoupling Long Video Sequences from LMMs via Dual Cross-Attention Mechanisms

# 摘要

> 大规模多模态模型（LMMs）的出现极大地提升了大型语言模型（LLMs）处理和解释多种数据模态（例如图像和视频）的能力。然而，随着输入复杂度的增加，尤其是面对长视频序列时，所需令牌的数量显著增加，导致计算成本呈二次增长。这使得在LMMs中高效压缩视频令牌同时保持性能完整性的研究变得迫切。本文中，我们引入了CrossLMM，通过一种双交叉注意力机制将长视频序列与LMMs解耦，从而在性能下降极小的情况下大幅减少视觉令牌数量。具体而言，我们首先通过池化方法从预训练的视觉编码器中实现显著的令牌减少。然后，在LLM层中，我们采用视觉到视觉的交叉注意力机制，其中池化的视觉令牌作为查询与原始视觉令牌集进行对比。这一模块实现了更高效的令牌利用，同时保留了细粒度的信息保真度。此外，我们还引入了文本到视觉的交叉注意力机制，其中文本令牌通过与原始视觉令牌的交互得到增强，从而丰富了文本令牌对视觉的理解。综合实证评估表明，尽管我们的方法使用的计算资源大幅减少，但在各种基于视频的LMM基准测试中，我们的方法实现了相当或更优的性能。

> The advent of Large Multimodal Models (LMMs) has significantly enhanced Large Language Models (LLMs) to process and interpret diverse data modalities (e.g., image and video). However, as input complexity increases, particularly with long video sequences, the number of required tokens has grown significantly, leading to quadratically computational costs. This has made the efficient compression of video tokens in LMMs, while maintaining performance integrity, a pressing research challenge. In this paper, we introduce CrossLMM, decoupling long video sequences from LMMs via a dual cross-attention mechanism, which substantially reduces visual token quantity with minimal performance degradation. Specifically, we first implement a significant token reduction from pretrained visual encoders through a pooling methodology. Then, within LLM layers, we employ a visual-to-visual cross-attention mechanism, wherein the pooled visual tokens function as queries against the original visual token set. This module enables more efficient token utilization while retaining fine-grained informational fidelity. In addition, we introduce a text-to-visual cross-attention mechanism, for which the text tokens are enhanced through interaction with the original visual tokens, enriching the visual comprehension of the text tokens. Comprehensive empirical evaluation demonstrates that our approach achieves comparable or superior performance across diverse video-based LMM benchmarks, despite utilizing substantially fewer computational resources.

[Arxiv](https://arxiv.org/abs/2505.17020)