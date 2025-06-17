# # CFBenchmark-MM：中文金融助理基准测试，针对多模态大型语言模型

发布时间：2025年06月15日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在金融领域的应用，特别是如何处理多模态数据（如文本、图表和表格）以支持金融决策。论文介绍了一个中文多模态金融基准（CFBenchmark-MM）及其评估系统，并分析了MLLMs在金融分析中的表现和潜力。这些内容属于大型语言模型在特定领域的应用和评估，因此归类为LLM应用。` `金融分析`

> CFBenchmark-MM: Chinese Financial Assistant Benchmark for Multimodal Large Language Model

# 摘要

> 多模态大型语言模型 (MLLMs) 随着大型语言模型 (LLMs) 的发展迅速演变，并在多个领域得到广泛应用。在金融领域，整合文本、图表和表格等多种数据形式对于准确和高效的决策至关重要。因此，为了推进金融应用的发展，建立一个能够涵盖这些数据类型的高效评估系统至关重要。本文介绍了 CFBenchmark-MM，这是一个包含超过 9,000 个图-问配对的中文多模态金融基准，涵盖表格、柱状图、折线图、饼图和结构图等多种图表形式。此外，我们开发了一个分阶段的评估系统，通过逐步提供不同的视觉内容来评估 MLLMs 处理多模态信息的能力。尽管 MLLMs 本身具备金融知识，但实验结果仍显示在处理多模态金融上下文方面效率和鲁棒性有限。进一步分析错误回答发现，对视觉内容的误读和对金融概念的误解是主要问题。我们的研究验证了 MLLMs 在金融分析中具有重要但尚未充分挖掘的潜力，强调了进一步开发和领域特定优化的必要性，以鼓励在金融领域的更广泛应用。

> Multimodal Large Language Models (MLLMs) have rapidly evolved with the growth of Large Language Models (LLMs) and are now applied in various fields. In finance, the integration of diverse modalities such as text, charts, and tables is crucial for accurate and efficient decision-making. Therefore, an effective evaluation system that incorporates these data types is essential for advancing financial application. In this paper, we introduce CFBenchmark-MM, a Chinese multimodal financial benchmark with over 9,000 image-question pairs featuring tables, histogram charts, line charts, pie charts, and structural diagrams. Additionally, we develop a staged evaluation system to assess MLLMs in handling multimodal information by providing different visual content step by step. Despite MLLMs having inherent financial knowledge, experimental results still show limited efficiency and robustness in handling multimodal financial context. Further analysis on incorrect responses reveals the misinterpretation of visual content and the misunderstanding of financial concepts are the primary issues. Our research validates the significant, yet underexploited, potential of MLLMs in financial analysis, highlighting the need for further development and domain-specific optimization to encourage the enhanced use in financial domain.

[Arxiv](https://arxiv.org/abs/2506.13055)