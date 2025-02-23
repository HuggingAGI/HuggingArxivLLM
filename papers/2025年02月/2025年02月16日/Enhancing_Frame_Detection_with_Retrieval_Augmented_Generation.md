# 检索增强生成提升框架检测

发布时间：2025年02月16日

`RAG` `知识图谱`

> Enhancing Frame Detection with Retrieval Augmented Generation

# 摘要

> 自然语言处理的最新进展显著提升了从非结构化文本中提取结构化语义表示的能力，尤其是在框架语义角色标注（FSRL）领域。尽管如此，检索增强生成（RAG）模型在框架检测方面的潜力仍未得到充分挖掘。本文首次提出了一种基于RAG的框架检测方法——RCIF（检索候选并识别框架）。RCIF的创新之处在于无需显式目标跨度，并包含三个核心阶段：（1）从多源表示中生成框架嵌入；（2）根据输入文本检索候选框架；（3）识别最合适的框架。我们进行了全面的实验，覆盖了零样本、少样本和微调等多种设置。实验结果表明，RCIF的检索组件通过缩小搜索空间显著降低了任务复杂性，使框架识别器能够更高效地完成候选集的优化。RCIF在FrameNet 1.5和1.7数据集上达到了当前最佳性能，证明了其在仅依赖原始文本场景下的强大鲁棒性。此外，我们利用RCIF生成的结构化表示作为中介，有效提升了在将自然语言问题转化为SPARQL查询任务中对词汇变化的泛化能力。


> Recent advancements in Natural Language Processing have significantly improved the extraction of structured semantic representations from unstructured text, especially through Frame Semantic Role Labeling (FSRL). Despite this progress, the potential of Retrieval-Augmented Generation (RAG) models for frame detection remains under-explored. In this paper, we present the first RAG-based approach for frame detection called RCIF (Retrieve Candidates and Identify Frames). RCIF is also the first approach to operate without the need for explicit target span and comprises three main stages: (1) generation of frame embeddings from various representations ; (2) retrieval of candidate frames given an input text; and (3) identification of the most suitable frames. We conducted extensive experiments across multiple configurations, including zero-shot, few-shot, and fine-tuning settings. Our results show that our retrieval component significantly reduces the complexity of the task by narrowing the search space thus allowing the frame identifier to refine and complete the set of candidates. Our approach achieves state-of-the-art performance on FrameNet 1.5 and 1.7, demonstrating its robustness in scenarios where only raw text is provided. Furthermore, we leverage the structured representation obtained through this method as a proxy to enhance generalization across lexical variations in the task of translating natural language questions into SPARQL queries.

[Arxiv](https://arxiv.org/abs/2502.12210)