# 从序列到结构：探索Transformer中的子结构推理机制

发布时间：2025年07月11日

`LLM理论` `图结构` `人工智能`

> From Sequence to Structure: Uncovering Substructure Reasoning in Transformers

# 摘要

> 近期研究表明，大型语言模型（LLMs）具备解决图推理任务的能力。值得注意的是，即使图结构嵌入在文本描述中，LLMs仍能有效回答相关问题。这引出了一个根本性问题：仅解码器式的Transformer架构如何理解潜在的图结构？为解答此问题，我们从子结构提取任务入手，解析Transformer内部机制，并分析输入查询的影响。具体而言，我们结合实证结果与理论分析，提出了一种名为诱导子结构过滤（ISF）的视角，用于捕捉多层Transformer中的子结构识别过程。我们进一步验证了ISF在LLMs中的有效性，揭示了各层之间一致的内部动态。基于这些见解，我们探索了Transformer在处理多种图类型中的更广泛应用能力。具体来说，我们引入了基于子结构思考的概念，以高效提取复杂复合模式，并证明仅解码器式的Transformer能够成功从属性图（如分子图）中提取子结构。综上所述，我们的研究为基于序列的Transformer如何在图数据上执行子结构提取任务提供了新的见解。

> Recent studies suggest that large language models (LLMs) possess the capability to solve graph reasoning tasks. Notably, even when graph structures are embedded within textual descriptions, LLMs can still effectively answer related questions. This raises a fundamental question: How can a decoder-only Transformer architecture understand underlying graph structures? To address this, we start with the substructure extraction task, interpreting the inner mechanisms inside the transformers and analyzing the impact of the input queries. Specifically, through both empirical results and theoretical analysis, we present Induced Substructure Filtration (ISF), a perspective that captures the substructure identification in the multi-layer transformers. We further validate the ISF process in LLMs, revealing consistent internal dynamics across layers. Building on these insights, we explore the broader capabilities of Transformers in handling diverse graph types. Specifically, we introduce the concept of thinking in substructures to efficiently extract complex composite patterns, and demonstrate that decoder-only Transformers can successfully extract substructures from attributed graphs, such as molecular graphs. Together, our findings offer a new insight on how sequence-based Transformers perform the substructure extraction task over graph data.

[Arxiv](https://arxiv.org/abs/2507.10435)