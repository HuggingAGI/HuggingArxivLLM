# # FinDER：面向问答与增强生成评估的金融数据集  
FinDER 是专为金融领域设计的问答与增强生成评估数据集。

发布时间：2025年04月22日

`RAG` `问答系统`

> FinDER: Financial Dataset for Question Answering and Evaluating Retrieval-Augmented Generation

# 摘要

> 在瞬息万变的金融领域，准确且及时的信息对应对市场变化至关重要。正确检索信息在金融问答（QA）中尤为关键，因为许多语言模型在这一领域难以保证事实准确性。我们推出了FinDER，这是一个由专家生成的数据集，专为金融领域的检索增强生成（RAG）设计。与现有依赖清晰查询和预定义上下文的QA数据集不同，FinDER专注于由领域专家标注与搜索相关的证据，提供了5,703个基于真实金融问答的查询-证据-答案三元组。这些查询常包含缩写、首字母缩略词和简洁表达，捕捉了专业人士在实际搜索行为中常见的简短性和模糊性。通过考验模型从大规模语料库中检索相关信息的能力，而不是依赖于现成确定的上下文，FinDER为评估RAG系统提供了一个更现实的基准。我们进一步对多个先进的检索模型和大型语言模型进行了全面评估，展示了来自现实基准的挑战，以推动未来在金融领域实现真实且精准的RAG研究。

> In the fast-paced financial domain, accurate and up-to-date information is critical to addressing ever-evolving market conditions. Retrieving this information correctly is essential in financial Question-Answering (QA), since many language models struggle with factual accuracy in this domain. We present FinDER, an expert-generated dataset tailored for Retrieval-Augmented Generation (RAG) in finance. Unlike existing QA datasets that provide predefined contexts and rely on relatively clear and straightforward queries, FinDER focuses on annotating search-relevant evidence by domain experts, offering 5,703 query-evidence-answer triplets derived from real-world financial inquiries. These queries frequently include abbreviations, acronyms, and concise expressions, capturing the brevity and ambiguity common in the realistic search behavior of professionals. By challenging models to retrieve relevant information from large corpora rather than relying on readily determined contexts, FinDER offers a more realistic benchmark for evaluating RAG systems. We further present a comprehensive evaluation of multiple state-of-the-art retrieval models and Large Language Models, showcasing challenges derived from a realistic benchmark to drive future research on truthful and precise RAG in the financial domain.

[Arxiv](https://arxiv.org/abs/2504.15800)