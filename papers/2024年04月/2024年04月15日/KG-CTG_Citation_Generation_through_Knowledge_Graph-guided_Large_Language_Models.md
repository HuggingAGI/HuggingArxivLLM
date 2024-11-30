# KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成

发布时间：2024年04月15日

`LLM应用` `计算机科学`

> KG-CTG: Citation Generation through Knowledge Graph-guided Large Language Models

# 摘要

> 在自然语言处理领域，引用文本生成（CTG）致力于在原始文档中准确引用或参考其他文献。这一任务通过结合原始文献与引用文献的上下文信息，确保生成的文本提供恰当的引用资料。传统研究多从文本摘要角度出发进行引用生成。本研究提出了一个新的框架，并通过比较研究展示了大型语言模型（LLMs）在生成引用文本方面的应用。通过在提示中加入论文间的知识图谱关系，我们进一步提升了模型的生成质量，使其更好地理解文献间的关系。为检验模型效能，我们选用了S2ORC数据集的英文计算机科学论文子集进行测试。结果显示，Vicuna在此任务中以14.15的Meteor得分、12.88的Rouge-1、1.52的Rouge-2和10.94的Rouge-L领先。同时，Alpaca模型通过融入知识图谱，将Rouge-1的得分提升了36.98%，Meteor得分提升了33.14%，表现尤为出色。

> Citation Text Generation (CTG) is a task in natural language processing (NLP) that aims to produce text that accurately cites or references a cited document within a source document. In CTG, the generated text draws upon contextual cues from both the source document and the cited paper, ensuring accurate and relevant citation information is provided. Previous work in the field of citation generation is mainly based on the text summarization of documents. Following this, this paper presents a framework, and a comparative study to demonstrate the use of Large Language Models (LLMs) for the task of citation generation. Also, we have shown the improvement in the results of citation generation by incorporating the knowledge graph relations of the papers in the prompt for the LLM to better learn the relationship between the papers. To assess how well our model is performing, we have used a subset of standard S2ORC dataset, which only consists of computer science academic research papers in the English Language. Vicuna performs best for this task with 14.15 Meteor, 12.88 Rouge-1, 1.52 Rouge-2, and 10.94 Rouge-L. Also, Alpaca performs best, and improves the performance by 36.98% in Rouge-1, and 33.14% in Meteor by including knowledge graphs.

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/x1.png)

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/single_citation_architecture.png)

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/prompt1.png)

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/prompt2.png)

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/table_1_without.jpg)

![KG-CTG：借助知识图谱引导的大型语言模型实现引文自动生成](../../../paper_images/2404.09763/table_1_with.jpg)

[Arxiv](https://arxiv.org/abs/2404.09763)