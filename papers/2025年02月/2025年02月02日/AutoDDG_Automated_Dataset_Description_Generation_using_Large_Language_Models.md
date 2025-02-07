# AutoDDG：基于大型语言模型的数据集描述自动生成

发布时间：2025年02月02日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来生成数据集的描述，以提升数据集的可发现性和相关性评估。虽然论文涉及数据集搜索和描述生成，但其核心是利用LLMs来增强语义信息并生成人类可读的描述。因此，这篇论文应归类为LLM应用。` `数据管理`

> AutoDDG: Automated Dataset Description Generation using Large Language Models

# 摘要

> # 摘要
开放数据门户和企业数据湖中数据集的激增为数据驱动的洞察提供了机会。然而，现有的数据集搜索系统主要依赖对元数据（如描述）的关键字搜索来促进发现。当这些描述不完整、缺失或与内容不符时，数据集的发现性将大打折扣。本文聚焦于自动数据集描述生成问题：如何生成信息丰富的描述以提升数据集的可发现性和相关性评估。我们提出了AutoDDG框架，专为表格数据设计，通过数据驱动的方法总结数据集内容，并利用LLMs增强语义信息，生成人类可读的描述。评估这一问题的核心挑战在于如何衡量生成方法的有效性和描述质量。为此，我们提出了一种多维度评估策略：（1）衡量数据集搜索引擎中的检索改进，（2）与现有描述对比（如有），（3）评估可读性、数据忠实度和简洁性等内在质量指标。此外，我们还引入了两个新基准来支持评估。实验结果表明，AutoDDG生成的描述质量高、准确性强，并显著提升了跨多种用例的数据集检索性能。

> The proliferation of datasets across open data portals and enterprise data lakes presents an opportunity for deriving data-driven insights. However, widely-used dataset search systems rely on keyword searches over dataset metadata, including descriptions, to facilitate discovery. When these descriptions are incomplete, missing, or inconsistent with dataset contents, findability is severely hindered. In this paper, we address the problem of automatic dataset description generation: how to generate informative descriptions that enhance dataset discovery and support relevance assessment. We introduce AutoDDG, a framework for automated dataset description generation tailored for tabular data. To derive descriptions that are comprehensive, accurate, readable and concise, AutoDDG adopts a data-driven approach to summarize the contents of a dataset, and leverages LLMs to both enrich the summaries with semantic information and to derive human-readable descriptions. An important challenge for this problem is how to evaluate the effectiveness of methods for data description generation and the quality of the descriptions. We propose a multi-pronged evaluation strategy that: (1) measures the improvement in dataset retrieval within a dataset search engine, (2) compares generated descriptions to existing ones (when available), and (3) evaluates intrinsic quality metrics such as readability, faithfulness to the data, and conciseness. Additionally, we introduce two new benchmarks to support this evaluation. Our experimental results, using these benchmarks, demonstrate that AutoDDG generates high-quality, accurate descriptions and significantly improves dataset retrieval performance across diverse use cases.

[Arxiv](https://arxiv.org/abs/2502.01050)