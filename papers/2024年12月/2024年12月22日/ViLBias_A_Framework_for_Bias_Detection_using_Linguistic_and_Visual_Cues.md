# ViLBias：一个借助语言和视觉线索来检测偏差的框架

发布时间：2024年12月22日

`LLM应用` `多模态分析`

> ViLBias: A Framework for Bias Detection using Linguistic and Visual Cues

# 摘要

> 大型语言模型（LLMs）与视觉语言模型（VLMs）的融合为应对多模态内容分析中的复杂难题，尤其是有偏见的新闻检测，开辟了新的道路。本研究推出了 ViLBias 框架，它借助前沿的 LLMs 和 VLMs 来检测新闻内容中的语言和视觉偏差，弥补了传统纯文本方法的不足。我们的贡献涵盖了一个全新的数据集，将来自不同新闻源的文本内容与配套的视觉内容相结合，还有一个混合标注框架，把基于 LLM 的标注和人工审核相融合，在提升质量的同时降低成本、增强可扩展性。我们评估了 LLMs 和 VLMs 在识别偏差方面的效果，展现了它们在检测细微框架和文本 - 视觉不一致性方面的长处。实证分析表明，将视觉线索与文本相结合能使偏差检测准确率提高 3%至 5%，凸显了 LLMs 在生成推理方面和小型语言模型（SLMs）在分类方面的互补优势。本研究对 LLMs 和 VLMs 作为检测新闻内容中多模态偏差的工具展开了全面探究，彰显了它们的潜力与局限。我们的研究为更强大、更具可扩展性和更精细的媒体偏差检测方法铺平了道路，为自然语言处理和多模态分析的更广泛领域作出了贡献。（数据和代码将用于研究目的而提供）。

> The integration of Large Language Models (LLMs) and Vision-Language Models (VLMs) opens new avenues for addressing complex challenges in multimodal content analysis, particularly in biased news detection. This study introduces ViLBias, a framework that leverages state of the art LLMs and VLMs to detect linguistic and visual biases in news content, addressing the limitations of traditional text-only approaches. Our contributions include a novel dataset pairing textual content with accompanying visuals from diverse news sources and a hybrid annotation framework, combining LLM-based annotations with human review to enhance quality while reducing costs and improving scalability. We evaluate the efficacy of LLMs and VLMs in identifying biases, revealing their strengths in detecting subtle framing and text-visual inconsistencies. Empirical analysis demonstrates that incorporating visual cues alongside text enhances bias detection accuracy by 3 to 5 %, showcasing the complementary strengths of LLMs in generative reasoning and Small Language Models (SLMs) in classification. This study offers a comprehensive exploration of LLMs and VLMs as tools for detecting multimodal biases in news content, highlighting both their potential and limitations. Our research paves the way for more robust, scalable, and nuanced approaches to media bias detection, contributing to the broader field of natural language processing and multimodal analysis. (The data and code will be made available for research purposes).

[Arxiv](https://arxiv.org/abs/2412.17052)