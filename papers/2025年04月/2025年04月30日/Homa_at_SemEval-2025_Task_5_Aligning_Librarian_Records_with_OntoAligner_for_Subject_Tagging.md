# Homa在SemEval-2025任务5中的研究：利用OntoAligner对图书馆员记录进行主题标签对齐

发布时间：2025年04月30日

`RAG` `信息科学` `数字图书馆`

> Homa at SemEval-2025 Task 5: Aligning Librarian Records with OntoAligner for Subject Tagging

# 摘要

> 本文介绍了我们开发的Homa系统，用于SemEval-2025任务5：主题标记。该任务旨在利用Gemeinsame Normdatei (GND)分类法，自动为TIBKAT的技术记录分配主题标签。我们采用了模块化本体对齐工具包OntoAligner，并结合检索增强生成（RAG）技术来解决这一问题。我们的方法将主题标记问题转化为对齐任务，通过语义相似性将记录与GND类别匹配。实验结果不仅展示了该方法的优势和局限性，还凸显了对齐技术在提升数字图书馆主题标记方面的潜力。

> This paper presents our system, Homa, for SemEval-2025 Task 5: Subject Tagging, which focuses on automatically assigning subject labels to technical records from TIBKAT using the Gemeinsame Normdatei (GND) taxonomy. We leverage OntoAligner, a modular ontology alignment toolkit, to address this task by integrating retrieval-augmented generation (RAG) techniques. Our approach formulates the subject tagging problem as an alignment task, where records are matched to GND categories based on semantic similarity. We evaluate OntoAligner's adaptability for subject indexing and analyze its effectiveness in handling multilingual records. Experimental results demonstrate the strengths and limitations of this method, highlighting the potential of alignment techniques for improving subject tagging in digital libraries.

[Arxiv](https://arxiv.org/abs/2504.21474)