# Doc2Chart：基于意图驱动的文档零样本图表生成

发布时间：2025年07月20日

`LLM应用`

> Doc2Chart: Intent-Driven Zero-Shot Chart Generation from Documents

# 摘要

> 大型语言模型（LLMs）在通过指令微调方法将文本描述或表格转换为数据可视化方面表现突出。然而，与用户手动预选相关内容不同，将其直接应用于根据用户意图从长文档中进行数据可视化的现实场景并不简单。我们提出了一种基于意图的文档图表生成任务：给定用户意图和文档，在零-shot设置下生成符合意图并基于文档的图表。我们提出了一种无监督的两阶段框架，LLM首先通过分解意图并迭代验证和细化数据从文档中提取相关信息。随后，一个基于启发式的模块选择合适的图表类型并在最终生成代码。为评估图表数据准确性，我们提出了一种基于归因的指标，使用图表的结构化文本表示，而非依赖通常无法有效捕获数据的视觉解码指标。我们从金融和科学领域整理了包含1,242个$<$意图，文档，图表$>$元组的数据集，而现有数据集大多局限于平行文本描述/表格及其对应图表。与使用LLM的单-shot生成和基于查询的检索方法相比，我们在图表数据准确性和类型方面分别领先最佳基线9个和17个点。

> Large Language Models (LLMs) have demonstrated strong capabilities in transforming text descriptions or tables to data visualizations via instruction-tuning methods. However, it is not straightforward to apply these methods directly for a more real-world use case of visualizing data from long documents based on user-given intents, as opposed to the user pre-selecting the relevant content manually. We introduce the task of intent-based chart generation from documents: given a user-specified intent and document(s), the goal is to generate a chart adhering to the intent and grounded on the document(s) in a zero-shot setting. We propose an unsupervised, two-staged framework in which an LLM first extracts relevant information from the document(s) by decomposing the intent and iteratively validates and refines this data. Next, a heuristic-guided module selects an appropriate chart type before final code generation. To assess the data accuracy of the generated charts, we propose an attribution-based metric that uses a structured textual representation of charts, instead of relying on visual decoding metrics that often fail to capture the chart data effectively. To validate our approach, we curate a dataset comprising of 1,242 $<$intent, document, charts$>$ tuples from two domains, finance and scientific, in contrast to the existing datasets that are largely limited to parallel text descriptions/ tables and their corresponding charts. We compare our approach with baselines using single-shot chart generation using LLMs and query-based retrieval methods; our method outperforms by upto $9$ points and $17$ points in terms of chart data accuracy and chart type respectively over the best baselines.

[Arxiv](https://arxiv.org/abs/2507.14819)