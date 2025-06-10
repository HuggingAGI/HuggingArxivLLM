# # WebUIBench：专为评估多模态大型语言模型在 Web UI 到代码生成能力设计的全面基准测试。

发布时间：2025年06月09日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在Web应用开发中的应用，并提出了一种评估框架来测试模型在不同子任务中的表现。这属于将大型语言模型应用于特定领域，因此归类为LLM应用。` `Web应用开发` `软件工程`

> WebUIBench: A Comprehensive Benchmark for Evaluating Multimodal Large Language Models in WebUI-to-Code

# 摘要

> 生成式 AI 技术的飞速发展，使多模态大型语言模型 (MLLMs) 有望成为具备复杂 Web 应用开发能力的 AI 软件工程师。由于模型需融合多维度子能力以应对开发各阶段的挑战，构建多维度评估框架对于提升开发效率至关重要。然而，现有基准测试通常仅关注网页生成结果，未能评估子能力。为此，我们从软件工程原则中汲取灵感，提出 WebUIBench——一个系统设计的基准测试，旨在从 WebUI 感知、HTML 编程、WebUI-HTML 理解和 WebUI 到代码转换这四个关键领域全面评估 MLLMs。WebUIBench 包含了从 0.7K 个真实网站中提取的 21K 高质量问答对。通过对 29 个主流 MLLMs 的全面评估，我们揭示了模型在开发过程中展现的技能特征及其面临的各种弱点。


> With the rapid advancement of Generative AI technology, Multimodal Large Language Models(MLLMs) have the potential to act as AI software engineers capable of executing complex web application development. Considering that the model requires a confluence of multidimensional sub-capabilities to address the challenges of various development phases, constructing a multi-view evaluation framework is crucial for accurately guiding the enhancement of development efficiency. However, existing benchmarks usually fail to provide an assessment of sub-capabilities and focus solely on webpage generation outcomes. In this work, we draw inspiration from the principles of software engineering and further propose WebUIBench, a benchmark systematically designed to evaluate MLLMs in four key areas: WebUI Perception, HTML Programming,WebUI-HTML Understanding, and WebUI-to-Code. WebUIBench comprises 21K high-quality question-answer pairs derived from over 0.7K real-world websites. The extensive evaluation of 29 mainstream MLLMs uncovers the skill characteristics and various weakness that models encountered during the development process.

[Arxiv](https://arxiv.org/abs/2506.07818)