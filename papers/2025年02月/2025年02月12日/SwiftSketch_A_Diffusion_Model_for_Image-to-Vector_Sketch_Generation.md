# SwiftSketch：用于图像到矢量素描生成的扩散模型

发布时间：2025年02月12日

`LLM应用` `创意设计`

> SwiftSketch: A Diffusion Model for Image-to-Vector Sketch Generation

# 摘要

> 大型视觉语言模型的最新进展为生成多样化且富有表现力的矢量素描开辟了新可能。然而，现有方法依赖于耗时的优化流程，需反复借助预训练模型反馈来定位笔触，导致实际应用受限。为此，我们推出SwiftSketch——一款基于图像的矢量素描生成扩散模型，能在不到一秒钟内生成高质量素描。SwiftSketch通过逐步去噪高斯分布采样的笔触控制点实现创作。其独特的Transformer解码器架构专为矢量表示的离散特性和笔触间的全局依赖关系而设计。为训练SwiftSketch，我们创建了一个图像-素描配对的合成数据集，弥补现有数据集由非专业人士制作、缺乏专业水准的不足。在生成合成素描时，我们引入ControlSketch，通过深度感知的ControlNet实现精确空间控制，进一步提升SDS技术。实验表明，SwiftSketch具备跨多概念的泛化能力，能高效生成兼具高保真度与自然美感的素描作品。

> Recent advancements in large vision-language models have enabled highly expressive and diverse vector sketch generation. However, state-of-the-art methods rely on a time-consuming optimization process involving repeated feedback from a pretrained model to determine stroke placement. Consequently, despite producing impressive sketches, these methods are limited in practical applications. In this work, we introduce SwiftSketch, a diffusion model for image-conditioned vector sketch generation that can produce high-quality sketches in less than a second. SwiftSketch operates by progressively denoising stroke control points sampled from a Gaussian distribution. Its transformer-decoder architecture is designed to effectively handle the discrete nature of vector representation and capture the inherent global dependencies between strokes. To train SwiftSketch, we construct a synthetic dataset of image-sketch pairs, addressing the limitations of existing sketch datasets, which are often created by non-artists and lack professional quality. For generating these synthetic sketches, we introduce ControlSketch, a method that enhances SDS-based techniques by incorporating precise spatial control through a depth-aware ControlNet. We demonstrate that SwiftSketch generalizes across diverse concepts, efficiently producing sketches that combine high fidelity with a natural and visually appealing style.

[Arxiv](https://arxiv.org/abs/2502.08642)