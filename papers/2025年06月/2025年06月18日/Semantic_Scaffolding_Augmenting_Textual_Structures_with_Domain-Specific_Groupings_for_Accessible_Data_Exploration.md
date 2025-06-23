# 语义支架：通过构建语义框架并结合领域分组方法，提升数据探索的可及性与易用性

发布时间：2025年06月18日

`LLM应用` `数据可视化` `辅助技术`

> Semantic Scaffolding: Augmenting Textual Structures with Domain-Specific Groupings for Accessible Data Exploration

# 摘要

> 探索新数据集时，将数据的有趣分组与其现实意义联系起来是一项既重要又具挑战性的任务。普通读者可能在图表中发现有趣的视觉模式，却缺乏领域知识来解释其含义。或者，读者可能熟悉某个现实概念，却难以用数据集字段来表达。为解决这一问题，我们开发了语义支架技术，该技术利用大型语言模型（LLMs）的领域特定信息，识别、解释和形式化具有语义意义的数据分组。我们以两种方式呈现这些分组：作为语义箱，将字段划分为领域特定的区间和类别；以及数据亮点，为数据记录子集标注其现实含义。我们在Olli中演示和评估了这项技术，这是一款易于使用的可视化工具，展示了在尊重读者独立探索数据的能力的同时，明确定义分组所面临的挑战。我们与15名盲人和低视力（BLV）用户进行了研究，发现读者使用语义支架快速理解数据含义，但同时也清楚地意识到其对自身解释的影响。

> Drawing connections between interesting groupings of data and their real-world meaning is an important, yet difficult, part of encountering a new dataset. A lay reader might see an interesting visual pattern in a chart but lack the domain expertise to explain its meaning. Or, a reader might be familiar with a real-world concept but struggle to express it in terms of a dataset's fields. In response, we developed semantic scaffolding, a technique for using domain-specific information from large language models (LLMs) to identify, explain, and formalize semantically meaningful data groupings. We present groupings in two ways: as semantic bins, which segment a field into domain-specific intervals and categories; and data highlights, which annotate subsets of data records with their real-world meaning. We demonstrate and evaluate this technique in Olli, an accessible visualization tool that exemplifies tensions around explicitly defining groupings while respecting the agency of readers to conduct independent data exploration. We conducted a study with 15 blind and low-vision (BLV) users and found that readers used semantic scaffolds to quickly understand the meaning of the data, but were often also critically aware of its influence on their interpretation.

[Arxiv](https://arxiv.org/abs/2506.15883)