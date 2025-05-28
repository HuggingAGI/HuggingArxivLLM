# MangaVQA 与 MangaLMM：多模态漫画理解的基准与专用模型

发布时间：2025年05月26日

`LLM应用` `多模态`

> MangaVQA and MangaLMM: A Benchmark and Specialized Model for Multimodal Manga Understanding

# 摘要

> 漫画，即日本连环画，是一种将图像与文字巧妙结合的多模态叙事形式。教会大规模多模态模型（LMMs）像人类一样理解这些叙事，将有助于漫画创作者反思并完善他们的故事。为此，我们提出了两个用于多模态漫画理解的基准测试：MangaOCR专注于页面内文字识别，而MangaVQA则通过视觉问答评估语境理解能力。MangaVQA包含526个高质量的人工构建的问题-答案对，能够在多种叙事和视觉场景下进行可靠评估。基于这些基准测试，我们开发了MangaLMM，这是一个专为漫画设计的模型，通过微调开源的LMM Qwen2.5-VL，使其能够同时处理这两个任务。通过广泛的实验，包括与GPT-4o和Gemini 2.5等专有模型的对比，我们评估了LMMs对漫画的理解能力。我们的基准测试和模型为在漫画这一叙事丰富的领域中评估和提升LMMs提供了全面的基础。

> Manga, or Japanese comics, is a richly multimodal narrative form that blends images and text in complex ways. Teaching large multimodal models (LMMs) to understand such narratives at a human-like level could help manga creators reflect on and refine their stories. To this end, we introduce two benchmarks for multimodal manga understanding: MangaOCR, which targets in-page text recognition, and MangaVQA, a novel benchmark designed to evaluate contextual understanding through visual question answering. MangaVQA consists of 526 high-quality, manually constructed question-answer pairs, enabling reliable evaluation across diverse narrative and visual scenarios. Building on these benchmarks, we develop MangaLMM, a manga-specialized model finetuned from the open-source LMM Qwen2.5-VL to jointly handle both tasks. Through extensive experiments, including comparisons with proprietary models such as GPT-4o and Gemini 2.5, we assess how well LMMs understand manga. Our benchmark and model provide a comprehensive foundation for evaluating and advancing LMMs in the richly narrative domain of manga.

[Arxiv](https://arxiv.org/abs/2505.20298)