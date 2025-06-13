# # ConTextTab: 语义感知型表格内上下文学习器

发布时间：2025年06月12日

`LLM应用` `数据分析` `数据科学`

> ConTextTab: A Semantics-Aware Tabular In-Context Learner

# 摘要

> 表格内上下文学习 (ICL) 近期在多个表格预测任务中实现了最先进 (SOTA) 的性能。此前，ICL 仅限于在小型表格上的分类问题，但近期的进展如 TabPFN 和 TabICL 已将其应用扩展至大型数据集。尽管在架构上高效且很好地适应了表格数据结构，但目前基于表格的 ICL 架构仅在合成数据上进行训练，未能充分利用现实世界表格数据中的丰富语义和世界知识。另一方面，基于预训练大型语言模型（如 TabuLa-8B）的表格 ICL 模型整合了深度语义理解和世界知识，但由于固有的架构限制，仅能利用少量上下文。为了结合这两个世界的最佳优势，我们引入了 ConTextTab，将语义理解和对齐整合到基于表格的 ICL 框架中。通过为不同数据模态使用专门的嵌入，并在大规模现实世界表格数据上进行训练，我们的模型在一系列基准测试中与 SOTA 模型相媲美，同时在语义丰富的 CARTE 基准上树立了新标准。

> Tabular in-context learning (ICL) has recently achieved state-of-the-art (SOTA) performance on several tabular prediction tasks. Previously restricted to classification problems on small tables, recent advances such as TabPFN and TabICL have extended its use to larger datasets. While being architecturally efficient and well-adapted to tabular data structures, current table-native ICL architectures, being trained exclusively on synthetic data, do not fully leverage the rich semantics and world knowledge contained in real-world tabular data. On another end of this spectrum, tabular ICL models based on pretrained large language models such as TabuLa-8B integrate deep semantic understanding and world knowledge but are only able to make use of a small amount of context due to inherent architectural limitations. With the aim to combine the best of both these worlds, we introduce ConTextTab, integrating semantic understanding and alignment into a table-native ICL framework. By employing specialized embeddings for different data modalities and by training on large-scale real-world tabular data, our model is competitive with SOTA across a broad set of benchmarks while setting a new standard on the semantically rich CARTE benchmark.

[Arxiv](https://arxiv.org/abs/2506.10707)