# SKETCH：用于实现整体检索的结构化知识增强型文本理解

发布时间：2024年12月19日

`RAG` `检索系统`

> SKETCH: Structured Knowledge Enhanced Text Comprehension for Holistic Retrieval

# 摘要

> 检索增强生成（RAG）系统对于借助海量语料库生成有依据且贴合上下文的回应发挥着关键作用，极大地减少了大型语言模型中的幻觉现象。尽管有显著进步，但这些系统在从大型数据集中高效处理和检索信息的同时，难以全面理解上下文。本文引入了 SKETCH，这一新颖方法将语义文本检索和知识图谱相融合，强化了 RAG 检索流程，把结构化和非结构化数据加以整合，以达成更全面的理解。SKETCH 在检索性能上有大幅提升，且相比传统方法，保持了出色的上下文完整性。在四个不同的数据集（QuALITY、QASPER、NarrativeQA 和意大利美食）中进行评估，SKETCH 在关键的 RAGAS 指标（如答案相关性、忠实度、上下文精度和上下文召回率）上始终优于基线方法。特别要指出的是，在意大利美食数据集上，SKETCH 实现了 0.94 的答案相关性和 0.99 的上下文精度，在所有评估指标中表现最为出色。这些成果凸显了 SKETCH 提供更精准且贴合上下文回应的能力，为未来的检索系统树立了新的标杆。

> Retrieval-Augmented Generation (RAG) systems have become pivotal in leveraging vast corpora to generate informed and contextually relevant responses, notably reducing hallucinations in Large Language Models. Despite significant advancements, these systems struggle to efficiently process and retrieve information from large datasets while maintaining a comprehensive understanding of the context. This paper introduces SKETCH, a novel methodology that enhances the RAG retrieval process by integrating semantic text retrieval with knowledge graphs, thereby merging structured and unstructured data for a more holistic comprehension. SKETCH, demonstrates substantial improvements in retrieval performance and maintains superior context integrity compared to traditional methods. Evaluated across four diverse datasets: QuALITY, QASPER, NarrativeQA, and Italian Cuisine-SKETCH consistently outperforms baseline approaches on key RAGAS metrics such as answer_relevancy, faithfulness, context_precision and context_recall. Notably, on the Italian Cuisine dataset, SKETCH achieved an answer relevancy of 0.94 and a context precision of 0.99, representing the highest performance across all evaluated metrics. These results highlight SKETCH's capability in delivering more accurate and contextually relevant responses, setting new benchmarks for future retrieval systems.

[Arxiv](https://arxiv.org/abs/2412.15443)