# 大型语言模型在无需人类辅助时难以描述 haystack：对 LLMs 的人机协同评估

发布时间：2025年02月20日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLM）在处理大规模文档集合中的实际应用和表现，特别是与传统主题模型的对比。它评估了LLM在知识获取中的应用效果，并讨论了其优势和局限性，属于LLM的实际应用研究。` `文档分析`

> Large Language Models Struggle to Describe the Haystack without Human Help: Human-in-the-loop Evaluation of LLMs

# 摘要

> 自然语言处理（NLP）常用于帮助理解大规模文档集合，这一应用已从传统主题模型转向大型语言模型（LLM）。然而，LLM在现实世界中用于大规模语料库理解的实际效果仍待深入探索。本研究通过两个数据集，评估了无监督、有监督的LLM探索方法和传统主题模型在知识获取方面的表现。基于LLM的方法生成的topic更易读，且在数据探索中胜过传统模型，但它们为特定领域数据生成的topic过于泛泛，难以让用户深入理解文档内容。通过在LLM生成过程中加入人工监督，可以缓解幻觉和过度泛化问题，从而改善数据探索，但需要投入更多的人力。相比之下，传统模型如潜在狄利克雷分配（LDA）在探索中依然有效，但用户体验较差。我们发现，LLM在没有人工辅助的情况下难以描述大规模语料库的细节，尤其是在特定领域数据上，并且由于上下文长度限制，面临扩展性和幻觉问题。数据集可从https://huggingface.co/datasets/zli12321/Bills获取。

> A common use of NLP is to facilitate the understanding of large document collections, with a shift from using traditional topic models to Large Language Models. Yet the effectiveness of using LLM for large corpus understanding in real-world applications remains under-explored. This study measures the knowledge users acquire with unsupervised, supervised LLM-based exploratory approaches or traditional topic models on two datasets. While LLM-based methods generate more human-readable topics and show higher average win probabilities than traditional models for data exploration, they produce overly generic topics for domain-specific datasets that do not easily allow users to learn much about the documents. Adding human supervision to the LLM generation process improves data exploration by mitigating hallucination and over-genericity but requires greater human effort. In contrast, traditional. models like Latent Dirichlet Allocation (LDA) remain effective for exploration but are less user-friendly. We show that LLMs struggle to describe the haystack of large corpora without human help, particularly domain-specific data, and face scaling and hallucination limitations due to context length constraints. Dataset available at https://huggingface. co/datasets/zli12321/Bills.

[Arxiv](https://arxiv.org/abs/2502.14748)