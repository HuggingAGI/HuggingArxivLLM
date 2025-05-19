# TCC-Bench：评测多语言大规模模型对传统文化理解能力的基准

发布时间：2025年05月16日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型在传统中文文化理解中的应用，提出了一个评估基准测试（TCC-Bench），属于模型应用的评估和改进，因此归类为LLM应用。` `人工智能`

> TCC-Bench: Benchmarking the Traditional Chinese Culture Understanding Capabilities of MLLMs

# 摘要

> 多模态大型语言模型的最新进展显著提升了人工智能系统对多模态内容的理解与生成能力。然而，这些模型在非西方文化背景下的应用效果往往不尽如人意，这引发了对其更广泛应用性的担忧。为了解决这一问题，我们提出了	extbf{T}raditional 	extbf{C}hinese 	extbf{C}ulture理解	extbf{Bench}mark（	extbf{TCC-Bench}），这是一个专为评估多模态大型语言模型对传统中文文化理解能力设计的双语（中文和英文）视觉问答（VQA）基准测试。TCC-Bench包含文化丰富且视觉多样的数据，涵盖了博物馆 artifacts、日常生活场景、漫画以及其他具有文化意义的背景图像。我们采用了一种半自动化的流程，首先利用GPT-4o以纯文本模式生成候选问题，随后通过人工筛选确保数据质量和避免潜在的数据泄露。该基准测试还通过避免在问题文本中直接披露文化概念来防止语言偏见。对一系列多模态大型语言模型的实验评估表明，当前模型在推理基于文化背景的视觉内容时仍面临重大挑战。这一结果突显了开发更具文化包容性和语境感知的多模态系统的需求。代码和数据可在以下链接找到：https://github.com/Morty-Xu/TCC-Bench。

> Recent progress in Multimodal Large Language Models (MLLMs) have significantly enhanced the ability of artificial intelligence systems to understand and generate multimodal content. However, these models often exhibit limited effectiveness when applied to non-Western cultural contexts, which raises concerns about their wider applicability. To address this limitation, we propose the \textbf{T}raditional \textbf{C}hinese \textbf{C}ulture understanding \textbf{Bench}mark (\textbf{TCC-Bench}), a bilingual (\textit{i.e.}, Chinese and English) Visual Question Answering (VQA) benchmark specifically designed for assessing the understanding of traditional Chinese culture by MLLMs. TCC-Bench comprises culturally rich and visually diverse data, incorporating images from museum artifacts, everyday life scenes, comics, and other culturally significant contexts. We adopt a semi-automated pipeline that utilizes GPT-4o in text-only mode to generate candidate questions, followed by human curation to ensure data quality and avoid potential data leakage. The benchmark also avoids language bias by preventing direct disclosure of cultural concepts within question texts. Experimental evaluations across a wide range of MLLMs demonstrate that current models still face significant challenges when reasoning about culturally grounded visual content. The results highlight the need for further research in developing culturally inclusive and context-aware multimodal systems. The code and data can be found at: https://github.com/Morty-Xu/TCC-Bench.

[Arxiv](https://arxiv.org/abs/2505.11275)