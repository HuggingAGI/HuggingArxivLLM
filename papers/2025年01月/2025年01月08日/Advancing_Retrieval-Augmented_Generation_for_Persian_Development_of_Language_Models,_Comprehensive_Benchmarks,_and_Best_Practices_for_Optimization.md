# 波斯语检索增强生成的前沿进展：语言模型开发、全面基准测试与优化最佳实践

发布时间：2025年01月08日

`RAG

理由：这篇论文主要讨论了在低资源语言（特别是波斯语）中构建检索增强生成（RAG）系统的挑战和方法。论文介绍了专门为波斯语设计的模型（如MatinaRoberta和MatinaSRoberta），并详细描述了如何通过大规模预训练、定制损失函数微调等方法来提升检索和生成的准确性。此外，论文还探讨了如何通过调整温度、块大小和文档摘要索引等参数来优化RAG设置。这些内容都与检索增强生成（RAG）系统密切相关，因此将其分类为RAG是合适的。` `搜索引擎`

> Advancing Retrieval-Augmented Generation for Persian: Development of Language Models, Comprehensive Benchmarks, and Best Practices for Optimization

# 摘要

> 本文研究了在低资源语言中构建检索增强生成（RAG）系统的挑战，特别是波斯语的复杂形态和灵活语法。通过引入波斯语专用模型MatinaRoberta（掩码语言模型）和MatinaSRoberta（微调的Sentence-BERT），以及一个全面的基准测试框架，研究旨在提升检索和生成的准确性。模型在73.11亿个波斯语标记的多样化语料库上训练后，使用通用知识（PQuad）、科学专业文本和组织报告三个数据集进行评估。方法包括大规模预训练、定制损失函数微调，以及使用传统指标和检索增强生成评估框架进行系统评估。结果显示，MatinaSRoberta在上下文相关性和检索准确性上优于之前的嵌入模型。研究还探索了温度调整、块大小修改和文档摘要索引以优化RAG设置。大型模型如Llama-3.1（70B）在生成准确性上表现最佳，而小型模型在特定领域和正式语境中表现欠佳。研究结果强调了通过定制嵌入和检索生成设置开发波斯语RAG系统的潜力，并展示了在低资源语言中提升搜索引擎和法律文档分析等NLP应用的可能性。

> This paper examines the specific obstacles of constructing Retrieval-Augmented Generation(RAG) systems in low-resource languages, with a focus on Persian's complicated morphology and versatile syntax. The research aims to improve retrieval and generation accuracy by introducing Persian-specific models, namely MatinaRoberta(a masked language model) and MatinaSRoberta(a fine-tuned Sentence-BERT), along with a comprehensive benchmarking framework. Three datasets-general knowledge(PQuad), scientifically specialized texts, and organizational reports, were used to assess these models after they were trained on a varied corpus of 73.11 billion Persian tokens. The methodology involved extensive pretraining, fine-tuning with tailored loss functions, and systematic evaluations using both traditional metrics and the Retrieval-Augmented Generation Assessment framework. The results show that MatinaSRoberta outperformed previous embeddings, achieving superior contextual relevance and retrieval accuracy across datasets. Temperature tweaking, chunk size modifications, and document summary indexing were explored to enhance RAG setups. Larger models like Llama-3.1 (70B) consistently demonstrated the highest generation accuracy, while smaller models faced challenges with domain-specific and formal contexts. The findings underscore the potential for developing RAG systems in Persian through customized embeddings and retrieval-generation settings and highlight the enhancement of NLP applications such as search engines and legal document analysis in low-resource languages.

[Arxiv](https://arxiv.org/abs/2501.04858)