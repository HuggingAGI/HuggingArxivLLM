# 将大型语言模型与领域专用图数据库对齐，实现NL2GQL

发布时间：2024年09月05日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决自然语言到图查询语言（NL2GQL）的转换问题。具体来说，论文提出了一种利用ChatGPT生成NL-GQL数据对，并通过微调LLMs来对齐图数据库的方法。这属于LLM在实际应用中的使用，因此应归类为LLM应用。`

> Aligning Large Language Models to a Domain-specific Graph Database for NL2GQL

# 摘要

> # 摘要
图数据库（Graph DB）在金融、社交网络和医学等多个领域应用广泛。然而，将自然语言（NL）转换为图查询语言（GQL），即NL2GQL，由于其复杂性和专业性，带来了巨大挑战。尽管一些方法尝试利用大型语言模型（LLMs）解决类似任务（如text2SQL），但在特定领域的NL2GQL任务中，缺乏领域特定的NL-GQL数据对，使得LLMs与图数据库的对齐变得复杂。为此，我们提出了一套明确的流程：首先，利用ChatGPT生成NL-GQL数据对，并通过图数据库进行自我指导；随后，使用生成的数据微调LLMs，确保其与图数据库的对齐。此外，我们发现相关模式在高效生成准确GQL中的重要性，因此引入了一种提取相关模式作为输入上下文的方法。我们使用从金融和医学领域的图数据库中构建的两个数据集（FinGQL和MediGQL）进行评估。实验结果显示，我们的方法显著优于基线方法，在FinGQL和MediGQL上分别提升了5.90和6.36个绝对点的EM，以及6.00和7.09个绝对点的EX。

> Graph Databases (Graph DB) find extensive application across diverse domains such as finance, social networks, and medicine. Yet, the translation of Natural Language (NL) into the Graph Query Language (GQL), referred to as NL2GQL, poses significant challenges owing to its intricate and specialized nature. Some approaches have sought to utilize Large Language Models (LLMs) to address analogous tasks like text2SQL. Nonetheless, in the realm of NL2GQL tasks tailored to a particular domain, the absence of domain-specific NL-GQL data pairs adds complexity to aligning LLMs with the graph DB. To tackle this challenge, we present a well-defined pipeline. Initially, we utilize ChatGPT to generate NL-GQL data pairs, leveraging the provided graph DB with self-instruction. Subsequently, we employ the generated data to fine-tune LLMs, ensuring alignment between LLMs and the graph DB. Moreover, we find the importance of relevant schema in efficiently generating accurate GQLs. Thus, we introduce a method to extract relevant schema as the input context. We evaluate our method using two carefully constructed datasets derived from graph DBs in the finance and medicine domains, named FinGQL and MediGQL. Experimental results reveal that our approach significantly outperforms a set of baseline methods, with improvements of 5.90 and 6.36 absolute points on EM, and 6.00 and 7.09 absolute points on EX for FinGQL and MediGQL, respectively.

[Arxiv](https://arxiv.org/abs/2402.16567)