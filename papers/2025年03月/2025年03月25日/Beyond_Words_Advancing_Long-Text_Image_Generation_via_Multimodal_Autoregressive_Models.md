# 超越文字：通过多模态自回归模型推进长文本图像生成

发布时间：2025年03月25日

`其他` `文档处理` `办公软件`

> Beyond Words: Advancing Long-Text Image Generation via Multimodal Autoregressive Models

# 摘要

> 自回归模型和扩散模型的最新进展在基于短场景文本的图像生成中表现出色。然而，生成图像中连贯的长文本内容，如幻灯片或文档中的段落，仍是现有生成模型的难题。我们首次专注于长文本图像生成的研究，填补了现有文本到图像系统通常只能处理简短短语或单个句子的空白。

通过对最先进的自回归生成模型进行全面分析，我们发现图像分词器是影响文本生成质量的关键瓶颈。为此，我们引入了一种新型文本专用二进制分词器，优化了对详细场景文本特征的捕捉。基于此，我们开发了\ModelName，一个多模态自回归模型，能够以前所未有的保真度生成高质量的长文本图像。

\ModelName提供了强大的控制能力，支持自定义文本属性，如字体样式、大小、颜色和对齐方式。大量实验表明，\ModelName在准确、一致和灵活地生成长文本方面显著优于SD3.5 Large~\cite{sd3}和GPT4o~\cite{gpt4o}与DALL-E 3~\cite{dalle3}。

除了技术上的突破，\ModelName还为创新应用如交错文档和PowerPoint生成开辟了令人兴奋的可能性，确立了长文本图像生成的新前沿。

> Recent advancements in autoregressive and diffusion models have led to strong performance in image generation with short scene text words. However, generating coherent, long-form text in images, such as paragraphs in slides or documents, remains a major challenge for current generative models. We present the first work specifically focused on long text image generation, addressing a critical gap in existing text-to-image systems that typically handle only brief phrases or single sentences. Through comprehensive analysis of state-of-the-art autoregressive generation models, we identify the image tokenizer as a critical bottleneck in text generating quality. To address this, we introduce a novel text-focused, binary tokenizer optimized for capturing detailed scene text features. Leveraging our tokenizer, we develop \ModelName, a multimodal autoregressive model that excels in generating high-quality long-text images with unprecedented fidelity. Our model offers robust controllability, enabling customization of text properties such as font style, size, color, and alignment. Extensive experiments demonstrate that \ModelName~significantly outperforms SD3.5 Large~\cite{sd3} and GPT4o~\cite{gpt4o} with DALL-E 3~\cite{dalle3} in generating long text accurately, consistently, and flexibly. Beyond its technical achievements, \ModelName~opens up exciting opportunities for innovative applications like interleaved document and PowerPoint generation, establishing a new frontier in long-text image generating.

[Arxiv](https://arxiv.org/abs/2503.20198)