# 多样化策略显著提升LLM在RAG与长上下文任务中的表现。

发布时间：2025年02月13日

`RAG

摘要中讨论了检索增强生成（RAG）方法在问答任务中的应用，并提出了一种基于最大边缘相关性和最远点采样的方法来提高内容选择的多样性，从而提升性能。这直接涉及RAG技术的改进和应用，因此属于RAG类别。` `问答系统` `信息检索`

> Diversity Enhances an LLM's Performance in RAG and Long-context Task

# 摘要

> 大型语言模型（LLMs）的快速发展凸显了上下文窗口限制的挑战，这主要是由于自注意力机制的二次时间复杂度（\(O(N^2)\)，其中 \(N\) 表示上下文窗口长度）。这一限制影响了问答（Q\&A）中的检索增强生成（RAG）和长上下文摘要等任务。一种常见的方法是选择与查询最相似的内容；然而，这通常会导致冗余，并排除多样化的相关信息。基于最大边缘相关性（MMR）和最远点采样（FPS）的原则，我们在内容选择过程中引入了多样性。我们的研究发现，在基于LLM的问答和摘要之前，将多样性融入内容选择，可以显著提高相关句子或块的召回率。这些结果强调了在未来的LLM应用中保持多样性的重要性，以进一步提升摘要和问答的效果。

> The rapid advancements in large language models (LLMs) have highlighted the challenge of context window limitations, primarily due to the quadratic time complexity of the self-attention mechanism (\(O(N^2)\), where \(N\) denotes the context window length). This constraint impacts tasks such as retrieval-augmented generation (RAG) in question answering (Q\&A) and long context summarization. A common approach involves selecting content with the highest similarity to the query; however, this often leads to redundancy and the exclusion of diverse yet relevant information. Building on principles from Maximal Marginal Relevance (MMR) and Farthest Point Sampling (FPS), we integrate diversity into the content selection process. Our findings reveal that incorporating diversity substantially increases the recall of selecting relevant sentences or chunks before LLM-based Q\&A and summarization. These results highlight the importance of maintaining diversity in future LLM applications to further improve summarization and Q\&A outcomes.

[Arxiv](https://arxiv.org/abs/2502.09017)