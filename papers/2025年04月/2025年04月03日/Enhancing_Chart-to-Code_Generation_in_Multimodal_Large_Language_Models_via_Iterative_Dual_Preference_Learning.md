# 通过迭代双偏好学习方法提升多模态大型语言模型的图表转代码生成能力

发布时间：2025年04月03日

`LLM应用` `软件开发`

> Enhancing Chart-to-Code Generation in Multimodal Large Language Models via Iterative Dual Preference Learning

# 摘要

> 图表到代码生成（Chart-to-code generation）是一种将图表图像转换为可执行绘图脚本的过程，它能无损地呈现图表信息，要求模型精准捕捉并总结所有视觉与结构元素。然而，这对多模态大型语言模型（MLLMs）仍是一个重大挑战，因为它们与代码生成任务的契合度并不高。为此，我们提出了Chart2Code——一个创新的迭代式双偏好学习框架，通过结构化代码变体生成和精细的双奖励信号，显著提升了MLLMs的图表到代码生成能力。我们在三种MLLMs上进行了验证，发现迭代式偏好学习能持续改善图表生成质量。我们的双评分方法从代码结构和视觉呈现两个维度进行评估，即使在数据集规模较小的情况下，仍能带来显著的性能提升。进一步的分析揭示了我们框架的核心组件，并阐明了图表到代码生成与更广泛图表推理之间的相互作用，为未来图表理解技术的发展奠定了基础。

> Chart-to-code generation, the process of converting chart images into executable plotting scripts, provides a lossless representation of chart information, requiring models to accurately capture and summarize all visual and structural elements. However, this remains a significant challenge for multimodal large language models (MLLMs), which are not inherently well-aligned with code generation tasks. To bridge this gap, we introduce Chart2Code, a novel iterative dual preference learning framework designed to enhance MLLMs' chart-to-code generation capabilities through structured code variant generation and fine-grained dual reward signals. We validate Chart2Code across three MLLMs and find that iterative preference learning consistently improves out-of-distribution chart-to-code generation quality. Throughout this process, our dual scoring method, which evaluates both the textual code structure and its visual representation, leads to greater performance improvements, even with a reduced preference dataset size. Further analysis explores the key components of our framework and highlights the interplay between chart-to-code generation and broader chart reasoning, paving the way for future advancements in chart comprehension.

[Arxiv](https://arxiv.org/abs/2504.02906)