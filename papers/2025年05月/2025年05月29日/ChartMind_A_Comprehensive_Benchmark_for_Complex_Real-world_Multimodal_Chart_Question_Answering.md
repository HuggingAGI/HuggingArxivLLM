# ChartMind：面向复杂真实场景的多模态图表问答全面基准测试

发布时间：2025年05月29日

`LLM应用` `图表分析` `多模态模型`

> ChartMind: A Comprehensive Benchmark for Complex Real-world Multimodal Chart Question Answering

# 摘要

> 图表问答（CQA）已成为评估视觉语言模型推理能力的关键多模态任务。尽管早期方法通过专注于视觉特征或利用大规模预训练展示了有前景的表现，但大多数现有评估依赖于 rigid output formats 和客观指标，从而忽略了实际图表分析中复杂、现实的需求。本文引入 ChartMind，这是一个专为真实场景下的复杂 CQA 任务设计的新基准。ChartMind 覆盖七种任务类别，融入多语言上下文，支持开放域文本输出，并兼容多种图表格式，弥合了现实应用与传统学术基准之间的差距。此外，我们提出了一种感知上下文且模型不可知的框架 ChartLLM，专注于提取关键上下文元素、降低噪声并增强多模态大语言模型的推理准确性。在 ChartMind 以及三个代表性公共基准上，使用 14 种主流多模态模型进行的广泛评估表明，我们的框架显著优于先前的三种常见 CQA 方法：遵循指令、OCR 增强和思维链。这凸显了灵活图表理解在现实 CQA 中的重要性。这些发现为未来研究中开发更强大的图表推理能力指明了新方向。

> Chart question answering (CQA) has become a critical multimodal task for evaluating the reasoning capabilities of vision-language models. While early approaches have shown promising performance by focusing on visual features or leveraging large-scale pre-training, most existing evaluations rely on rigid output formats and objective metrics, thus ignoring the complex, real-world demands of practical chart analysis. In this paper, we introduce ChartMind, a new benchmark designed for complex CQA tasks in real-world settings. ChartMind covers seven task categories, incorporates multilingual contexts, supports open-domain textual outputs, and accommodates diverse chart formats, bridging the gap between real-world applications and traditional academic benchmarks. Furthermore, we propose a context-aware yet model-agnostic framework, ChartLLM, that focuses on extracting key contextual elements, reducing noise, and enhancing the reasoning accuracy of multimodal large language models. Extensive evaluations on ChartMind and three representative public benchmarks with 14 mainstream multimodal models show our framework significantly outperforms the previous three common CQA paradigms: instruction-following, OCR-enhanced, and chain-of-thought, highlighting the importance of flexible chart understanding for real-world CQA. These findings suggest new directions for developing more robust chart reasoning in future research.

[Arxiv](https://arxiv.org/abs/2505.23242)