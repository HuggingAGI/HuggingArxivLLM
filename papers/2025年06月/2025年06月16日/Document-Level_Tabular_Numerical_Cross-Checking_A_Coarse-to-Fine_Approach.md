# 文档级表格数值核对：粗细结合方法

发布时间：2025年06月16日

`LLM应用` `数据处理`

> Document-Level Tabular Numerical Cross-Checking: A Coarse-to-Fine Approach

# 摘要

> 披露文件中的表格数值一致性对确保准确性、维护可信度以及规避声誉和经济风险至关重要。然而，自动化表格数值交叉核对面临两大挑战：(C1) 文档层面候选实例的组合爆炸问题，以及 (C2) 多维度数值语义的理解。以往研究多依赖启发式过滤或简化上下文提取，难以在性能与效率间取得平衡。大型语言模型（LLMs）虽在实例层面展现了卓越的上下文理解能力，但受限于计算效率（C1）和领域知识的不足。本文提出 CoFiTCheck，一种基于 LLM 的粗细结合框架，通过嵌入式过滤和判别分类两个阶段解决这些挑战。嵌入式过滤阶段采用指令并行编码方法，利用 LLMs 高效表示表格中所有数值提及，并通过解耦 InfoNCE 目标缓解孤立提及问题。判别分类阶段则借助专门的 LLM 对剩余候选对进行细粒度分析。此外，我们引入跨表格数值对齐的预训练范式，通过弱监督的跨表格数值等式关系丰富任务特定先验，无需人工标注。在三种真实披露文件类型的全面评估中，CoFiTCheck 不仅显著超越以往方法，还保持了实际效率，展现了其优越性。

> Numerical consistency across tables in disclosure documents is critical for ensuring accuracy, maintaining credibility, and avoiding reputational and economic risks. Automated tabular numerical cross-checking presents two significant challenges: (C1) managing the combinatorial explosion of candidate instances at the document level and (C2) comprehending multi-faceted numerical semantics. Previous research typically depends on heuristic-based filtering or simplified context extraction, often struggling to balance performance and efficiency. Recently, large language models (LLMs) have demonstrated remarkable contextual understanding capabilities that helps address C2 at the instance level, yet they remain hampered by computational inefficiency (C1) and limited domain expertise. This paper introduces CoFiTCheck, a novel LLM-based coarse-to-fine framework that addresses these challenges through two sequential stages: embedding-based filtering and discriminative classification. The embedding-based filtering stage introduces an instructional parallel encoding method to efficiently represent all numerical mentions in a table with LLMs, as well as a decoupled InfoNCE objective to mitigate the isolated mention problem. The discriminative classification stage employs a specialized LLM for fine-grained analysis of the remaining candidate pairs. This stage is further enhanced by our crosstable numerical alignment pretraining paradigm, which leverages weak supervision from cross-table numerical equality relationships to enrich task-specific priors without requiring manual annotation. Comprehensive evaluation across three types of real-world disclosure documents demonstrates that CoFiTCheck significantly outperforms previous methods while maintaining practical efficiency.

[Arxiv](https://arxiv.org/abs/2506.13328)