# # 重写前必读：通过持续预训练为重写器注入领域知识

发布时间：2025年07月01日

`RAG`

> Read the Docs Before Rewriting: Equip Rewriter with Domain Knowledge via Continual Pre-training

# 摘要

> 检索增强生成（RAG）的问题回答（QA）系统通过根据用户查询检索相关文档来增强大型语言模型的知识。由于用户查询与文档措辞之间的差异，通常需要进行查询改写。然而，在专业领域，改写模型可能因缺乏领域特定知识而难以应对。为解决这一问题，我们提出了R&R（先读文档再改写）改写器，该方法通过持续预训练专业文档来提升改写能力，类似于学生通过复习教科书为开卷考试做准备。此外，该方法还可以结合监督微调以获得更好的效果。在多个数据集上的实验表明，R&R在多个专业领域的QA任务中表现出色，有效缩小了查询与文档之间的差距，同时在一般场景中也保持了良好的性能，从而推动了RAG基QA系统在专业领域的应用。

> A Retrieval-Augmented Generation (RAG)-based question-answering (QA) system enhances a large language model's knowledge by retrieving relevant documents based on user queries. Discrepancies between user queries and document phrasings often necessitate query rewriting. However, in specialized domains, the rewriter model may struggle due to limited domain-specific knowledge. To resolve this, we propose the R\&R (Read the doc before Rewriting) rewriter, which involves continual pre-training on professional documents, akin to how students prepare for open-book exams by reviewing textbooks. Additionally, it can be combined with supervised fine-tuning for improved results. Experiments on multiple datasets demonstrate that R\&R excels in professional QA across multiple domains, effectively bridging the query-document gap, while maintaining good performance in general scenarios, thus advancing the application of RAG-based QA systems in specialized fields.

[Arxiv](https://arxiv.org/abs/2507.00477)