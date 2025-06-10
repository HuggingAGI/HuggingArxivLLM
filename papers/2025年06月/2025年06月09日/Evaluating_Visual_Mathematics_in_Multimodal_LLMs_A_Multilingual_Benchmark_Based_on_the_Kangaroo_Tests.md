# 探索多模态大语言模型中的视觉数学：基于袋鼠测试构建的多语言基准测试

发布时间：2025年06月09日

`LLM应用

摘要讨论了多模态大型语言模型在数学问题解决中的应用，评估了多个模型在不同任务中的表现。这属于将LLM应用于特定领域（数学问题解决）的研究，因此归类为LLM应用。`

> Evaluating Visual Mathematics in Multimodal LLMs: A Multilingual Benchmark Based on the Kangaroo Tests

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在视觉语言能力方面展现出强大的潜力，但在视觉呈现的数学问题上仍存在未被充分探索的有效性。本文分析了MLLMs在数学问题解决中的发展与评估，重点关注图形、多语言文本和符号表示。我们随后评估了多个模型，包括GPT 4o、Pixtral、Qwen VL、Llama 3.2 Vision变体和Gemini 2.0 Flash，使用一种多语言袋鼠风格基准测试，涵盖英语、法语、西班牙语和加泰罗尼亚语。我们的实验揭示了四个关键发现。

首先，整体精度在几何、视觉代数、逻辑、模式和组合数学方面仍处于中等水平：没有单一模型能在每个主题上都表现出色。其次，尽管大多数模型在没有图像的问题上准确率有所提升，但增益通常有限；某些模型在没有视觉输入的情况下表现几乎不变，表明对图形信息的利用率不足。第三，不同语言和难度水平之间存在显著差异：模型通常能处理较简单的题目，但在高级几何和组合推理上表现困难。值得注意的是，Gemini 2.0 Flash在基于图像的任务中实现了最高精度，其次是Qwen VL 2.5 72B和GPT 4o，但均未达到人类水平。第四，一项补充分析旨在区分模型是进行推理还是简单背诵，结果显示Gemini和GPT 4o在结构化推理和一致准确性方面脱颖而出。相比之下，Pixtral和Llama的推理一致性较低，常常在无法使其输出与给定答案选项对齐时诉诸于启发式或随机性。

> Multimodal Large Language Models (MLLMs) promise advanced vision language capabilities, yet their effectiveness in visually presented mathematics remains underexplored. This paper analyzes the development and evaluation of MLLMs for mathematical problem solving, focusing on diagrams, multilingual text, and symbolic notation. We then assess several models, including GPT 4o, Pixtral, Qwen VL, Llama 3.2 Vision variants, and Gemini 2.0 Flash in a multilingual Kangaroo style benchmark spanning English, French, Spanish, and Catalan. Our experiments reveal four key findings. First, overall precision remains moderate across geometry, visual algebra, logic, patterns, and combinatorics: no single model excels in every topic. Second, while most models see improved accuracy with questions that do not have images, the gain is often limited; performance for some remains nearly unchanged without visual input, indicating underutilization of diagrammatic information. Third, substantial variation exists across languages and difficulty levels: models frequently handle easier items but struggle with advanced geometry and combinatorial reasoning. Notably, Gemini 2.0 Flash achieves the highest precision on image based tasks, followed by Qwen VL 2.5 72B and GPT 4o, though none approach human level performance. Fourth, a complementary analysis aimed at distinguishing whether models reason or simply recite reveals that Gemini and GPT 4o stand out for their structured reasoning and consistent accuracy. In contrast, Pixtral and Llama exhibit less consistent reasoning, often defaulting to heuristics or randomness when unable to align their outputs with the given answer options.

[Arxiv](https://arxiv.org/abs/2506.07418)