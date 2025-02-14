# ImageRAG：动态图像检索助力基于参考的图像生成

发布时间：2025年02月13日

`RAG` `计算机视觉` `图像生成`

> ImageRAG: Dynamic Image Retrieval for Reference-Guided Image Generation

# 摘要

> 扩散模型擅长生成高质量且多样的视觉内容，但在处理罕见或前所未见的概念时往往力不从心。为突破这一局限，我们探索了将检索增强生成（RAG）技术与图像生成模型相结合的可能性，提出了ImageRAG这一创新方法。ImageRAG能够根据给定的文本提示，动态检索相关图像，并将其作为生成过程的上下文引导。与传统方法需要为检索生成专门训练模型不同，ImageRAG巧妙地利用现有图像条件模型的能力，无需额外的RAG训练。这种高度适应性的方法能够轻松应用于各类模型，并在生成罕见和细粒度概念方面展现出显著优势。
我们的项目页面地址为：https://rotem-shalev.github.io/ImageRAG

> Diffusion models enable high-quality and diverse visual content synthesis. However, they struggle to generate rare or unseen concepts. To address this challenge, we explore the usage of Retrieval-Augmented Generation (RAG) with image generation models. We propose ImageRAG, a method that dynamically retrieves relevant images based on a given text prompt, and uses them as context to guide the generation process. Prior approaches that used retrieved images to improve generation, trained models specifically for retrieval-based generation. In contrast, ImageRAG leverages the capabilities of existing image conditioning models, and does not require RAG-specific training. Our approach is highly adaptable and can be applied across different model types, showing significant improvement in generating rare and fine-grained concepts using different base models.
  Our project page is available at: https://rotem-shalev.github.io/ImageRAG

[Arxiv](https://arxiv.org/abs/2502.09411)