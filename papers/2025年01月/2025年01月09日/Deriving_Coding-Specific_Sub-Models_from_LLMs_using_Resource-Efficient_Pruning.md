# 利用资源高效剪枝技术从LLMs中提取特定编码的子模型

发布时间：2025年01月09日

`LLM应用

**理由**：这篇论文主要讨论了如何通过模型剪枝技术来创建特定编程语言的紧凑模型，以降低大型语言模型的计算和资源需求，使其能够在消费级硬件上本地运行并加速推理时间。这属于将大型语言模型应用于实际场景（如代码生成）的优化和改进，因此归类为LLM应用。` `软件工程` `编程语言`

> Deriving Coding-Specific Sub-Models from LLMs using Resource-Efficient Pruning

# 摘要

> 大型语言模型（LLMs）在复杂代码生成任务中表现出色，但其广泛应用受限于高计算和资源需求。为缓解这一问题，模型剪枝技术被用于创建参数更少的紧凑模型。然而，现有方法未专注于高效提取特定编程语言的子模型。本研究通过非结构化剪枝（如Wanda）探索高效提取编码子模型的方法，并分析不同领域校准数据集对剪枝结果的影响，进一步提取了Python、Java、C++和JavaScript四种语言子模型。我们首次利用适当校准数据集高效提取特定编程语言子模型，同时保持与完整模型相当的准确性，并首次提供分析证据，证明领域特定任务激活LLMs的不同区域，支持通过非结构化剪枝创建专门子模型。我们相信，这项工作通过降低计算需求，使LLM能在消费级硬件上本地运行，并加速推理时间，对实时开发反馈至关重要，具有显著提升LLM编码可访问性的潜力。

> Large Language Models (LLMs) have demonstrated their exceptional performance in various complex code generation tasks. However, their broader adoption is limited by significant computational demands and high resource requirements, particularly memory and processing power. To mitigate such requirements, model pruning techniques are used to create more compact models with significantly fewer parameters. However, current approaches do not focus on the efficient extraction of programming-language-specific sub-models. In this work, we explore the idea of efficiently deriving coding-specific sub-models through unstructured pruning (i.e., Wanda). We investigate the impact of different domain-specific calibration datasets on pruning outcomes across three distinct domains and extend our analysis to extracting four language-specific sub-models: Python, Java, C++, and JavaScript. We are the first to efficiently extract programming-language-specific sub-models using appropriate calibration datasets while maintaining acceptable accuracy w.r.t. full models. We are also the first to provide analytical evidence that domain-specific tasks activate distinct regions within LLMs, supporting the creation of specialized sub-models through unstructured pruning. We believe that this work has significant potential to enhance LLM accessibility for coding by reducing computational requirements to enable local execution on consumer-grade hardware, and supporting faster inference times critical for real-time development feedback.

[Arxiv](https://arxiv.org/abs/2501.05248)