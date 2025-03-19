# TextInVision：基于文本与提示复杂度驱动的视觉文本生成基准测试

发布时间：2025年03月17日

`其他` `视觉生成` `多模态内容`

> TextInVision: Text and Prompt Complexity Driven Visual Text Generation Benchmark

# 摘要

> 生成带有嵌入文本的图像对于自动生产视觉和多模态文档（如教育材料和广告）至关重要。然而，现有的基于扩散模型的文本到图像生成模型往往难以准确将文本嵌入图像中，面临着拼写准确性、上下文相关性和视觉连贯性等方面的挑战。由于缺乏全面的基准测试，评估这些模型在生成图像中嵌入文本的能力变得复杂。在本研究中，我们引入了TextInVision，这是一个大规模、由文本和提示复杂性驱动的基准测试，旨在评估扩散模型将视觉文本有效集成到图像中的能力。我们设计了一组多样化的提示和文本，考虑了各种属性和文本特征。此外，我们准备了一个图像数据集，用于测试变分自编码器（VAE）模型在不同字符表示下的表现，强调了VAE架构在扩散框架中文本生成方面也可能带来挑战。通过对多个模型的广泛分析，我们识别出常见的错误，并突出了如拼写不准确和上下文不匹配等问题。通过定位不同提示和文本中的失败点，我们的研究为未来在AI生成的多模态内容方面的进展奠定了基础。

> Generating images with embedded text is crucial for the automatic production of visual and multimodal documents, such as educational materials and advertisements. However, existing diffusion-based text-to-image models often struggle to accurately embed text within images, facing challenges in spelling accuracy, contextual relevance, and visual coherence. Evaluating the ability of such models to embed text within a generated image is complicated due to the lack of comprehensive benchmarks. In this work, we introduce TextInVision, a large-scale, text and prompt complexity driven benchmark designed to evaluate the ability of diffusion models to effectively integrate visual text into images. We crafted a diverse set of prompts and texts that consider various attributes and text characteristics. Additionally, we prepared an image dataset to test Variational Autoencoder (VAE) models across different character representations, highlighting that VAE architectures can also pose challenges in text generation within diffusion frameworks. Through extensive analysis of multiple models, we identify common errors and highlight issues such as spelling inaccuracies and contextual mismatches. By pinpointing the failure points across different prompts and texts, our research lays the foundation for future advancements in AI-generated multimodal content.

[Arxiv](https://arxiv.org/abs/2503.13730)