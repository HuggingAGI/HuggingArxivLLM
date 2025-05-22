# ChartCards：图表元数据生成框架，助力多任务图表理解

发布时间：2025年05月20日

`LLM应用` `数据分析` `数据可视化`

> ChartCards: A Chart-Metadata Generation Framework for Multi-Task Chart Understanding

# 摘要

> 多模态大型语言模型（MLLMs）的横空出世为图表理解领域注入了新的活力。然而，这类任务的复杂性和精细度使得直接应用MLLMs面临挑战——通常需要大规模、高质量的数据集进行特定任务的微调，这大大增加了数据收集和训练的成本。为了解决这一难题，我们提出了ChartCards，一个统一的图表元数据生成框架，专为多任务图表理解而设计。ChartCards巧妙地整合了各类图表信息，包括数据表格、可视化代码、视觉元素以及多维度的语义描述。通过将这些信息结构化为有组织的元数据，ChartCards使一个图表能够支持多种下游任务，如文本到图表检索、图表摘要、图表转表格、图表描述以及图表问答。基于ChartCards，我们构建了MetaChart，一个大规模高质量的数据集，包含10,862个数据表格、85,000个图表以及170,000个高质量的图表描述。通过定性众包评估和定量微调实验，我们验证了MetaChart在各种图表理解任务中的有效性。在MetaChart上对六种不同模型进行微调后，所有任务的平均性能提升了5%。其中，文本到图表检索和图表转表格任务的提升尤为显著，Long-CLIP和Llama 3.2-11B分别实现了17%和28%的性能飞跃。

> The emergence of Multi-modal Large Language Models (MLLMs) presents new opportunities for chart understanding. However, due to the fine-grained nature of these tasks, applying MLLMs typically requires large, high-quality datasets for task-specific fine-tuning, leading to high data collection and training costs. To address this, we propose ChartCards, a unified chart-metadata generation framework for multi-task chart understanding. ChartCards systematically synthesizes various chart information, including data tables, visualization code, visual elements, and multi-dimensional semantic captions. By structuring this information into organized metadata, ChartCards enables a single chart to support multiple downstream tasks, such as text-to-chart retrieval, chart summarization, chart-to-table conversion, chart description, and chart question answering. Using ChartCards, we further construct MetaChart, a large-scale high-quality dataset containing 10,862 data tables, 85K charts, and 170 K high-quality chart captions. We validate the dataset through qualitative crowdsourcing evaluations and quantitative fine-tuning experiments across various chart understanding tasks. Fine-tuning six different models on MetaChart resulted in an average performance improvement of 5% across all tasks. The most notable improvements are seen in text-to-chart retrieval and chart-to-table tasks, with Long-CLIP and Llama 3.2-11B achieving improvements of 17% and 28%, respectively.

[Arxiv](https://arxiv.org/abs/2505.15046)