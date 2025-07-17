# 流式4D视觉几何变换器

发布时间：2025年07月15日

`其他` `计算机视觉` `流媒体`

> Streaming 4D Visual Geometry Transformer

# 摘要

> 从视频中感知和重建4D时空几何是一项基础而具挑战性的计算机视觉任务。为了支持交互式和实时应用，我们提出了一种流式4D视觉几何变换器，其设计理念与自回归大型语言模型相似。我们采用因果变换器结构以在线方式处理输入序列，并利用时序因果注意力，将历史键和值缓存作为隐式记忆，从而实现高效的流式长期4D重建。这种设计能够在逐步整合历史信息的同时，保持高质量的空间一致性，从而实现实时4D重建。为了提高训练效率，我们建议从密集的双向视觉几何接地变换器（VGGT）中蒸馏知识到我们的因果模型。在推理方面，我们的模型支持从大型语言模型领域迁移优化的高效注意力运算符（如FlashAttention）。在各种4D几何感知基准上的大量实验表明，我们的模型在在线场景中提高了推理速度，同时保持了具有竞争力的性能，为可扩展和交互式的4D视觉系统铺平了道路。代码可在以下位置获取：https://github.com/wzzheng/StreamVGGT。


> Perceiving and reconstructing 4D spatial-temporal geometry from videos is a fundamental yet challenging computer vision task. To facilitate interactive and real-time applications, we propose a streaming 4D visual geometry transformer that shares a similar philosophy with autoregressive large language models. We explore a simple and efficient design and employ a causal transformer architecture to process the input sequence in an online manner. We use temporal causal attention and cache the historical keys and values as implicit memory to enable efficient streaming long-term 4D reconstruction. This design can handle real-time 4D reconstruction by incrementally integrating historical information while maintaining high-quality spatial consistency. For efficient training, we propose to distill knowledge from the dense bidirectional visual geometry grounded transformer (VGGT) to our causal model. For inference, our model supports the migration of optimized efficient attention operator (e.g., FlashAttention) from the field of large language models. Extensive experiments on various 4D geometry perception benchmarks demonstrate that our model increases the inference speed in online scenarios while maintaining competitive performance, paving the way for scalable and interactive 4D vision systems. Code is available at: https://github.com/wzzheng/StreamVGGT.

[Arxiv](https://arxiv.org/abs/2507.11539)