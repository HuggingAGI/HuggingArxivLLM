# 揭示LLM生成代码中的低效：构建全面分类体系

发布时间：2025年03月08日

`LLM应用` `软件开发` `代码生成`

> Unveiling Inefficiencies in LLM-Generated Code: Toward a Comprehensive Taxonomy

# 摘要

> 大型语言模型 (LLMs) 在代码自动生成领域得到了广泛应用，并取得了令人鼓舞的结果。然而，尽管先前研究发现 LLM 生成的代码存在冗余、维护性差及性能不佳等问题，但目前仍缺乏对这些问题的系统性理解和分类。这种知识的缺失使得从业者难以优化 LLM 生成的代码以满足实际需求，限制了其应用。本研究旨在通过改进代码 LLM，提升代码生成的质量和效率。

因此，我们对 CodeLlama、DeepSeek-Coder 和 CodeGemma 等先进模型生成的代码低效问题进行了实证研究。通过对 HumanEval++ 数据集中 492 个代码片段的分析，我们构建了一个包含 5 个类别（通用逻辑、性能、可读性、维护性和错误）和 19 个子类别的低效问题分类法。通过 58 名 LLM 实践者和研究人员的在线调查验证，我们发现逻辑和性能相关的低效问题最常见、最相关，且常共同发生，对整体代码质量影响最大。我们的分类法为评估 LLM 生成代码的质量提供了结构化基础，为未来提高代码生成效率的研究指明了方向。

> Large Language Models (LLMs) are widely adopted for automated code generation with promising results. Although prior research has assessed LLM-generated code and identified various quality issues -- such as redundancy, poor maintainability, and sub-optimal performance a systematic understanding and categorization of these inefficiencies remain unexplored. Without such knowledge, practitioners struggle to optimize LLM-generated code for real-world applications, limiting its adoption. This study can also guide improving code LLMs, enhancing the quality and efficiency of code generation. Therefore, in this study, we empirically investigate inefficiencies in LLM-generated code by state-of-the-art models, i.e., CodeLlama, DeepSeek-Coder, and CodeGemma. To do so, we analyze 492 generated code snippets in the HumanEval++ dataset. We then construct a taxonomy of inefficiencies in LLM-generated code that includes 5 categories General Logic, Performance, Readability, Maintainability, and Errors) and 19 subcategories of inefficiencies. We then validate the proposed taxonomy through an online survey with 58 LLM practitioners and researchers. Our study indicates that logic and performance-related inefficiencies are the most popular, relevant, and frequently co-occur and impact overall code quality inefficiency. Our taxonomy provides a structured basis for evaluating the quality LLM-generated code and guiding future research to improve code generation efficiency.

[Arxiv](https://arxiv.org/abs/2503.06327)