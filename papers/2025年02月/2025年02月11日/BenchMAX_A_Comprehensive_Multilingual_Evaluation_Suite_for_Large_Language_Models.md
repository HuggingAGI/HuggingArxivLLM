# BenchMAX: 多语言大型语言模型的全面评估套件

发布时间：2025年02月11日

`LLM理论

摘要讨论了多语言大型语言模型的能力评估，提出了一个新的基准测试框架BenchMAX，用于评估模型的高级能力。这属于LLM理论，因为它涉及模型能力的分析和评估方法的开发。` `多语言技术`

> BenchMAX: A Comprehensive Multilingual Evaluation Suite for Large Language Models

# 摘要

> # 引言  
传统多语言基准测试主要聚焦于基础理解任务，但对于大型语言模型（LLMs），我们更关注其指令遵循、推理、长上下文理解、代码生成等高级能力。然而，跨语言评估这些能力的研究仍显不足。为此，我们推出了BenchMAX——一个多维度多语言评估基准，旨在公平比较不同语言在这些关键能力上的表现。为了确保数据质量，我们对从英语翻译到16种其他语言的数据进行了严格的母语标注流程，由三位独立的母语标注员完成标注工作。此外，我们在数据集构建过程中发现了一个全新的翻译挑战。通过在BenchMAX上的广泛实验，我们发现不同语言的核心能力表现存在显著差异，揭示了仅靠模型规模的扩展无法解决的性能差距。BenchMAX作为一个全面的多语言评估平台，为推动多语言语言模型的发展提供了一个极具潜力的测试环境。目前，该数据集和代码已向公众开放。

> Previous multilingual benchmarks focus primarily on simple understanding tasks, but for large language models(LLMs), we emphasize proficiency in instruction following, reasoning, long context understanding, code generation, and so on. However, measuring these advanced capabilities across languages is underexplored. To address the disparity, we introduce BenchMAX, a multi-way multilingual evaluation benchmark that allows for fair comparisons of these important abilities across languages. To maintain high quality, three distinct native-speaking annotators independently annotate each sample within all tasks after the data was machine-translated from English into 16 other languages. Additionally, we present a novel translation challenge stemming from dataset construction. Extensive experiments on BenchMAX reveal varying effectiveness of core capabilities across languages, highlighting performance gaps that cannot be bridged by simply scaling up model size. BenchMAX serves as a comprehensive multilingual evaluation platform, providing a promising test bed to promote the development of multilingual language models. The dataset and code are publicly accessible.

[Arxiv](https://arxiv.org/abs/2502.07346)