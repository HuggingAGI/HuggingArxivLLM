# # **用于长文本 RAG 的可控检索增强上下文评估**  
    本研究提出了一种新的方法，通过可控检索增强上下文评估，提升长文本 RAG 模型的性能与效果。

发布时间：2025年06月24日

`RAG` `信息检索`

> Controlled Retrieval-augmented Context Evaluation for Long-form RAG

# 摘要

> 检索增强生成（RAG）通过整合外部知识源中的上下文来提升大型语言模型的能力。然而，尽管检索模块的有效性通常通过基于相关性的指标来评估，但这些指标可能无法全面反映检索对最终RAG结果的影响，尤其是在长文本生成任务中。我们提出，为长文本生成任务（如报告生成）提供全面的检索增强上下文至关重要，并为此设计了一些独立于生成过程的上下文评估指标。我们引入了CRUX框架，这是一个	extbf{C}ontrolled 	extbf{R}etrieval-a	extbf{U}gmented conte	extbf{X}t（可控检索增强上下文）评估框架，旨在直接评估检索增强的上下文质量。通过人工编写的摘要，CRUX能够控制知识的信息范围，从而衡量上下文在长文本生成中对关键信息的覆盖程度。此外，CRUX采用基于问题的评估方法，以细致入微的方式评估RAG的检索效果。实验结果表明，CRUX提供了更具反思性和诊断价值的评估。我们的研究还发现，当前的检索方法仍有很大的改进空间，并为推进RAG的检索能力指明了方向。我们的数据和代码已公开，以支持和促进未来关于检索的研究。

> Retrieval-augmented generation (RAG) enhances large language models by incorporating context retrieved from external knowledge sources. While the effectiveness of the retrieval module is typically evaluated with relevance-based ranking metrics, such metrics may be insufficient to reflect the retrieval's impact on the final RAG result, especially in long-form generation scenarios. We argue that providing a comprehensive retrieval-augmented context is important for long-form RAG tasks like report generation and propose metrics for assessing the context independent of generation. We introduce CRUX, a \textbf{C}ontrolled \textbf{R}etrieval-a\textbf{U}gmented conte\textbf{X}t evaluation framework designed to directly assess retrieval-augmented contexts. This framework uses human-written summaries to control the information scope of knowledge, enabling us to measure how well the context covers information essential for long-form generation. CRUX uses question-based evaluation to assess RAG's retrieval in a fine-grained manner. Empirical results show that CRUX offers more reflective and diagnostic evaluation. Our findings also reveal substantial room for improvement in current retrieval methods, pointing to promising directions for advancing RAG's retrieval. Our data and code are publicly available to support and advance future research on retrieval.

[Arxiv](https://arxiv.org/abs/2506.20051)