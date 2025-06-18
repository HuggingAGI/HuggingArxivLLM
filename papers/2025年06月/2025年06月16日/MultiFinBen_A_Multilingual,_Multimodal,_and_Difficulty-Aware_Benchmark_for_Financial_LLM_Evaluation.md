# MultiFinBen：一个多语言、多模态且难度感知的金融LLM评估基准

发布时间：2025年06月16日

`LLM应用

摘要主要讨论了大型语言模型在金融领域的应用，特别是开发了一个多语言多模态的基准测试MultiFinBen，用于评估LLMs在复杂金融任务中的表现。这属于将LLMs应用于具体领域的研究，因此归类为LLM应用。` `NLP`

> MultiFinBen: A Multilingual, Multimodal, and Difficulty-Aware Benchmark for Financial LLM Evaluation

# 摘要

> 大型语言模型（LLMs）的突破推动了金融NLP和应用的快速发展，但现有基准测试仍局限于单语和单模态环境，往往过于依赖简单任务，难以反映真实金融交流的复杂性。我们推出MultiFinBen，首个专为全球金融领域设计的多语言多模态基准测试，通过跨模态（文本、视觉、音频）和跨语言设置（单语、双语、多语）评估LLMs在特定任务中的表现。我们引入了两个全新任务，包括PolyFiQA-Easy和PolyFiQA-Expert，这是首个要求模型处理混合语言输入进行复杂推理的多语言金融基准测试；以及EnglishOCR和SpanishOCR，这是首批嵌入OCR的金融问答任务，考验模型从视觉文本财务文件中提取和推理信息的能力。此外，我们提出了一种动态、难度感知的选择机制，并精心整理了一个紧凑、平衡的基准测试，而非简单聚合现有数据集。对22个最先进的模型进行的广泛评估表明，即使是最强大的模型，尽管具备通用的多模态和多语言能力，但在面对复杂的跨语言和多模态金融任务时仍会遇到巨大挑战。MultiFinBen现已公开发布，旨在推动金融研究和应用的透明、可重复和包容性进展。

> Recent advances in large language models (LLMs) have accelerated progress in financial NLP and applications, yet existing benchmarks remain limited to monolingual and unimodal settings, often over-relying on simple tasks and failing to reflect the complexity of real-world financial communication. We introduce MultiFinBen, the first multilingual and multimodal benchmark tailored to the global financial domain, evaluating LLMs across modalities (text, vision, audio) and linguistic settings (monolingual, bilingual, multilingual) on domain-specific tasks. We introduce two novel tasks, including PolyFiQA-Easy and PolyFiQA-Expert, the first multilingual financial benchmarks requiring models to perform complex reasoning over mixed-language inputs; and EnglishOCR and SpanishOCR, the first OCR-embedded financial QA tasks challenging models to extract and reason over information from visual-text financial documents. Moreover, we propose a dynamic, difficulty-aware selection mechanism and curate a compact, balanced benchmark rather than simple aggregation existing datasets. Extensive evaluation of 22 state-of-the-art models reveals that even the strongest models, despite their general multimodal and multilingual capabilities, struggle dramatically when faced with complex cross-lingual and multimodal tasks in financial domain. MultiFinBen is publicly released to foster transparent, reproducible, and inclusive progress in financial studies and applications.

[Arxiv](https://arxiv.org/abs/2506.14028)