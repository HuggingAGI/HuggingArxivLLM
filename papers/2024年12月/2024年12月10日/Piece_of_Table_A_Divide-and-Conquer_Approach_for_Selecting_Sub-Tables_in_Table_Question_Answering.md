# Piece of Table：一种在表格问答中选择子表的分治策略

发布时间：2024年12月10日

`LLM应用` `问答系统`

> Piece of Table: A Divide-and-Conquer Approach for Selecting Sub-Tables in Table Question Answering

# 摘要

> 将语言模型（LMs）应用于表格颇具挑战，原因在于二维表格与语言模型最初设计所针对的一维文本存在固有结构差异。而且，在将线性化表格用于语言模型时，自注意力计算中常有的最大标记长度限制，导致难以全面理解大表格中的上下文。为应对这些难题，我们推出了PieTa（表格片段）这一新框架，用于基于子表的问答（QA）。PieTa通过将表格分割为较小窗口的迭代流程运作，利用语言模型在每个窗口中选取相关单元格，并将这些单元格合并为子表。这种多分辨率手段既能捕获多行多列的依赖关系，又能规避长上下文输入带来的限制。作为一种简单的迭代子表联合算法实例，PieTa的性能优于以往基于子表的问答方法。

> Applying language models (LMs) to tables is challenging due to the inherent structural differences between two-dimensional tables and one-dimensional text for which the LMs were originally designed. Furthermore, when applying linearized tables to LMs, the maximum token lengths often imposed in self-attention calculations make it difficult to comprehensively understand the context spread across large tables. To address these challenges, we present PieTa (Piece of Table), a new framework for sub-table-based question answering (QA). PieTa operates through an iterative process of dividing tables into smaller windows, using LMs to select relevant cells within each window, and merging these cells into a sub-table. This multi-resolution approach captures dependencies across multiple rows and columns while avoiding the limitations caused by long context inputs. Instantiated as a simple iterative sub-table union algorithm, PieTa demonstrates improved performance over previous sub-table-based QA approaches.

[Arxiv](https://arxiv.org/abs/2412.07629)