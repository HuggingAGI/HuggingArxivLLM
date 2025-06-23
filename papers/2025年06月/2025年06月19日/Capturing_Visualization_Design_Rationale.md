# # 解析可视化设计背后的逻辑

发布时间：2025年06月19日

`其他` `数据可视化`

> Capturing Visualization Design Rationale

# 摘要

> 现有的自然语言数据集主要集中在数据可视化任务上，如可视化素养评估、见解生成以及根据自然语言指令生成可视化。这些研究往往依赖于受控实验环境，使用专门设计的可视化和人工构造的问题，因此更关注对可视化的解读，专注于解码可视化本身，而非理解其编码过程。本文中，我们提出了一种新的数据集和方法，旨在通过自然语言探究可视化设计的思路。我们利用了一种独特的真实世界可视化和自然语言叙述的来源：学生在数据可视化课程中创建的可视化素养笔记本。这些笔记本将视觉元素与设计说明相结合，学生在其中明确阐述了其设计决策背后的思路。我们还利用大型语言模型（LLMs）从笔记本中的叙述和阐述生成并分类问题-答案-原因三元组。随后，我们对这些三元组进行了仔细的验证，并整理出一个数据集，该数据集捕捉并提炼了学生的可视化设计选择及其对应的设计思路。

> Prior natural language datasets for data visualization have focused on tasks such as visualization literacy assessment, insight generation, and visualization generation from natural language instructions. These studies often rely on controlled setups with purpose-built visualizations and artificially constructed questions. As a result, they tend to prioritize the interpretation of visualizations, focusing on decoding visualizations rather than understanding their encoding. In this paper, we present a new dataset and methodology for probing visualization design rationale through natural language. We leverage a unique source of real-world visualizations and natural language narratives: literate visualization notebooks created by students as part of a data visualization course. These notebooks combine visual artifacts with design exposition, in which students make explicit the rationale behind their design decisions. We also use large language models (LLMs) to generate and categorize question-answer-rationale triples from the narratives and articulations in the notebooks. We then carefully validate the triples and curate a dataset that captures and distills the visualization design choices and corresponding rationales of the students.

[Arxiv](https://arxiv.org/abs/2506.16571)