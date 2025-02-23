# 快与优之间：生成增强中灵活用户控制下的精准与成本平衡

发布时间：2025年02月17日

`RAG` `生成技术`

> Fast or Better? Balancing Accuracy and Cost in Retrieval-Augmented Generation with Flexible User Control

# 摘要

> 检索增强生成（RAG）方法在提升大型语言模型（LLM）准确性方面展现出显著优势，通过融合外部知识检索功能实现更可靠的文本生成。然而，现有的RAG框架普遍存在检索策略不够智能的问题，要么在不需要时进行过度检索，要么在需要复杂推理时未能进行迭代检索，导致效率低下。近期提出的自适应检索策略虽然能够根据查询复杂度动态调整检索方式，但其灵活性不足，难以满足不同用户的具体需求。在本文中，我们提出了一种创新的用户可控RAG框架，实现了准确率与成本之间的灵活平衡。我们的方法采用双分类器设计：一个专注于提升准确率，另一个则致力于优化检索效率。通过一个直观的控制参数α，用户可以根据实际需求在“最低成本检索”与“高准确率检索”之间自由切换。实证研究表明，本方法在准确率、检索成本和用户控制能力之间实现了良好平衡，为实际应用场景提供了一个既实用又灵活的解决方案。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful approach to mitigate large language model (LLM) hallucinations by incorporating external knowledge retrieval. However, existing RAG frameworks often apply retrieval indiscriminately,leading to inefficiencies-over-retrieving when unnecessary or failing to retrieve iteratively when required for complex reasoning. Recent adaptive retrieval strategies, though adaptively navigates these retrieval strategies, predict only based on query complexity and lacks user-driven flexibility, making them infeasible for diverse user application needs. In this paper, we introduce a novel user-controllable RAG framework that enables dynamic adjustment of the accuracy-cost trade-off. Our approach leverages two classifiers: one trained to prioritize accuracy and another to prioritize retrieval efficiency. Via an interpretable control parameter $α$, users can seamlessly navigate between minimal-cost retrieval and high-accuracy retrieval based on their specific requirements. We empirically demonstrate that our approach effectively balances accuracy, retrieval cost, and user controllability, making it a practical and adaptable solution for real-world applications.

[Arxiv](https://arxiv.org/abs/2502.12145)