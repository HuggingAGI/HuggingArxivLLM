# 随心布局：基于扩散式变压器的自然场景布局生成方法

发布时间：2025年05月07日

`其他` `图像生成` `图像编辑`

> Lay-Your-Scene: Natural Scene Layout Generation with Diffusion Transformers

# 摘要

> 我们推出了一款名为 Lay-Your-Scene（简称 LayouSyn）的创新文本到布局生成工具，专为自然场景设计。与以往方法不同，LayouSyn 不受封闭词汇的限制，也无需依赖专有的大型语言模型，从而在可控图像生成领域展现出更广泛的应用前景。我们的解决方案基于轻量级开源语言模型，能够从文本提示中精准提取场景元素，并结合一种全新的基于扩散的Transformer架构，通过开放词汇训练实现条件布局生成。实验证明，LayouSyn 不仅超越了现有方法，还在复杂的空间和数值推理基准测试中达到了顶尖水准。此外，我们展示了 LayouSyn 的两大实用功能：首先，它能与大型语言模型的粗初始化无缝衔接，进一步提升生成效果；其次，我们开发了一套向图像中添加物体的流程，充分体现了 LayouSyn 在图像编辑领域的巨大潜力。

> We present Lay-Your-Scene (shorthand LayouSyn), a novel text-to-layout generation pipeline for natural scenes. Prior scene layout generation methods are either closed-vocabulary or use proprietary large language models for open-vocabulary generation, limiting their modeling capabilities and broader applicability in controllable image generation. In this work, we propose to use lightweight open-source language models to obtain scene elements from text prompts and a novel aspect-aware diffusion Transformer architecture trained in an open-vocabulary manner for conditional layout generation. Extensive experiments demonstrate that LayouSyn outperforms existing methods and achieves state-of-the-art performance on challenging spatial and numerical reasoning benchmarks. Additionally, we present two applications of LayouSyn. First, we show that coarse initialization from large language models can be seamlessly combined with our method to achieve better results. Second, we present a pipeline for adding objects to images, demonstrating the potential of LayouSyn in image editing applications.

[Arxiv](https://arxiv.org/abs/2505.04718)