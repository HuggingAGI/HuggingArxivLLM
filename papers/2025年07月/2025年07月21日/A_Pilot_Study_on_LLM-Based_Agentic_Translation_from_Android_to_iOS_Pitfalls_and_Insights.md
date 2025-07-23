# 从Android到iOS的智能翻译：基于大型语言模型的探索与实践

发布时间：2025年07月21日

`LLM应用` `软件工程` `人工智能`

> A Pilot Study on LLM-Based Agentic Translation from Android to iOS: Pitfalls and Insights

# 摘要

> 移动应用的快速发展催生了对跨平台兼容性的强烈需求，尤其是在 Android 和 iOS 平台之间。传统移动应用翻译方法多依赖人工干预或基于规则的系统，不仅耗时费力，还难以应对复杂场景。尽管机器学习的最新进展带来了自动化方法，但这些方法往往缺乏上下文理解和适应能力，导致翻译效果不尽如人意。近期，大型语言模型（LLMs）被用于提升不同粒度级别的代码翻译能力，包括方法、类和仓库级别。研究者们已深入探讨了常见错误、限制及改进策略。然而，跨平台应用翻译领域，如 Android 与 iOS 之间的应用迁移或不同框架间的软件适配，仍存在研究空白。理解 LLMs 在跨平台应用翻译中的性能、优势与局限性，对于推动软件工程自动化具有重要意义。本研究旨在通过评估基于 LLM 的智能体方法在移动应用翻译中的表现，识别关键失败点，并提出改进翻译性能的指南来填补这一空白。我们开发了一个智能体链，在将应用从 Android 转换为 iOS 时，综合考虑了依赖关系、规范、程序结构和控制流。为了评估性能，我们手动检查了翻译后的代码在句法正确性、语义准确性和功能性完整性方面的表现。对于翻译失败的情况，我们进一步进行了详细的根因分析，以深入理解智能体翻译过程中的潜在限制，并识别改进机会。

> The rapid advancement of mobile applications has led to a significant demand for cross-platform compatibility, particularly between the Android and iOS platforms. Traditional approaches to mobile application translation often rely on manual intervention or rule-based systems, which are labor-intensive and time-consuming. While recent advancements in machine learning have introduced automated methods, they often lack contextual understanding and adaptability, resulting in suboptimal translations. Large Language Models (LLMs) were recently leveraged to enhance code translation at different granularities, including the method, class, and repository levels. Researchers have investigated common errors, limitations, and potential strategies to improve these tasks. However, LLM-based application translation across different platforms, such as migrating mobile applications between Android and iOS or adapting software across diverse frameworks, remains underexplored. Understanding the performance, strengths, and limitations of LLMs in cross-platform application translation is critical for advancing software engineering automation. This study aims to fill this gap by evaluating LLM-based agentic approaches for mobile application translation, identifying key failure points, and proposing guidelines to improve translation performance. We developed a chain of agents that account for dependencies, specifications, program structure, and program control flow when translating applications from Android to iOS. To evaluate the performance, we manually examined the translated code for syntactic correctness, semantic accuracy, and functional completeness. For translation failures, we further conducted a detailed root cause analysis to understand the underlying limitations of the agentic translation process and identify opportunities for improvement.

[Arxiv](https://arxiv.org/abs/2507.16037)