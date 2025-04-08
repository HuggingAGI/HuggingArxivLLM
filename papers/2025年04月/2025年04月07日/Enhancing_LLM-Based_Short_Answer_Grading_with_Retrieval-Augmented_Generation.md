# 基于LLM的简答题评分改进：结合检索增强生成

发布时间：2025年04月07日

`RAG` `人工智能`

> Enhancing LLM-Based Short Answer Grading with Retrieval-Augmented Generation

# 摘要

> 短问答评估是科学教育中的关键环节，能够有效评估学生对复杂三维知识的理解。在语言任务中表现出类人能力的大型语言模型（LLMs）正越来越多地被用于协助人工评分者，以减轻其工作负担。然而，LLMs在领域知识方面的局限性限制了它们对任务特定要求的理解，并阻碍了它们实现令人满意的性能。检索增强生成（RAG）通过在评估过程中使LLMs能够访问相关领域特定知识，成为了一个有前景的解决方案。在这项工作中，我们提出了一种自适应的RAG框架用于自动化评分，该框架能够根据问题和学生答案的上下文动态检索并整合领域特定知识。我们的方法结合语义搜索和经过筛选的教育资源以检索有价值的参考资料。在科学教育数据集上的实验结果表明，与基线LLM方法相比，我们的系统在评分准确率上有所提升。研究结果表明，增强RAG的评分系统可以作为可靠的辅助工具，并带来性能的高效提升。

> Short answer assessment is a vital component of science education, allowing evaluation of students' complex three-dimensional understanding. Large language models (LLMs) that possess human-like ability in linguistic tasks are increasingly popular in assisting human graders to reduce their workload. However, LLMs' limitations in domain knowledge restrict their understanding in task-specific requirements and hinder their ability to achieve satisfactory performance. Retrieval-augmented generation (RAG) emerges as a promising solution by enabling LLMs to access relevant domain-specific knowledge during assessment. In this work, we propose an adaptive RAG framework for automated grading that dynamically retrieves and incorporates domain-specific knowledge based on the question and student answer context. Our approach combines semantic search and curated educational sources to retrieve valuable reference materials. Experimental results in a science education dataset demonstrate that our system achieves an improvement in grading accuracy compared to baseline LLM approaches. The findings suggest that RAG-enhanced grading systems can serve as reliable support with efficient performance gains.

[Arxiv](https://arxiv.org/abs/2504.05276)