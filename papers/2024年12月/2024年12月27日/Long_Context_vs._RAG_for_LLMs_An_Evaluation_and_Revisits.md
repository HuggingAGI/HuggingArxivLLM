# 长上下文与 RAG 在 LLMs 中的评估与再探

发布时间：2024年12月27日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）和扩展上下文窗口（LC）两种策略在LLMs中的应用，特别是它们在处理超长外部上下文时的表现。论文通过实验和评估，比较了RAG和LC在不同类型问题上的表现，并指出了它们各自的优势和劣势。因此，这篇论文的核心内容与RAG密切相关，适合归类为RAG。` `问答系统`

> Long Context vs. RAG for LLMs: An Evaluation and Revisits

# 摘要

> 扩展上下文窗口（长上下文，LC）和利用检索器选择性获取信息（检索增强生成，RAG）是让LLMs整合超长外部上下文的两种主要策略。本文回顾了近期相关研究，提炼出关键见解与差异。通过剔除无需外部上下文即可回答的问题、筛选最优检索方法并扩展数据集，我们进行了更全面的评估。结果显示，在问答基准测试中，LC通常优于RAG，尤其在维基百科类问题上。基于摘要的检索与LC表现相当，而基于块的检索则稍逊一筹。然而，RAG在对话类和一般问题查询上更具优势。这些发现揭示了RAG与LC策略间的权衡，为未来优化带外部知识源的LLMs提供了方向。我们还深入探讨了该主题，指出现有研究中常被忽视的上下文相关性的重要性。

> Extending context windows (i.e., Long Context, LC) and using retrievers to selectively access relevant information (i.e., Retrieval-Augmented Generation, RAG) are the two main strategies to enable LLMs to incorporate extremely long external contexts. This paper revisits recent studies on this topic, highlighting their key insights and discrepancies. We then provide a more comprehensive evaluation by filtering out questions answerable without external context, identifying the most effective retrieval methods, and expanding the datasets. We show that LC generally outperforms RAG in question-answering benchmarks, especially for Wikipedia-based questions. Summarization-based retrieval performs comparably to LC, while chunk-based retrieval lags behind. However, RAG has advantages in dialogue-based and general question queries. These insights underscore the trade-offs between RAG and LC strategies, offering guidance for future optimization of LLMs with external knowledge sources. We also provide an in-depth discussion on this topic, highlighting the overlooked importance of context relevance in existing studies.

[Arxiv](https://arxiv.org/abs/2501.01880)