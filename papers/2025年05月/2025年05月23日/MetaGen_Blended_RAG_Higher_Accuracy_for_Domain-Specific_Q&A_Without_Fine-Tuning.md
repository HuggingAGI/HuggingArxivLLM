# # MetaGen Blended RAG：无需微调，领域问答更精准
MetaGen Blended RAG 在无需微调的情况下，显著提升了领域特定问答任务的准确性。

发布时间：2025年05月23日

`RAG` `企业应用` `问答系统`

> MetaGen Blended RAG: Higher Accuracy for Domain-Specific Q&A Without Fine-Tuning

# 摘要

> 尽管检索增强生成（RAG）得到了广泛探索，但其在企业中使用特定领域数据集的部署仍然受到限制，原因在于答案的准确性较差。这些语料库通常隐藏在企业知识库的防火墙后，包含复杂的特定领域术语，在大型语言模型（LLMs）的预训练过程中很少被接触；跨领域（如网络、军事或法律等）甚至在同一领域（如医学）内都表现出显著的语义变异性，从而导致RAG系统上下文精度较差。目前，在这种情况下，尝试了微调或结合微调的RAG方法，但这些方法速度慢、成本高，且随着新领域特定数据的出现，缺乏准确性上的泛化能力。我们提出了一种针对企业搜索的方法，重点通过混合查询索引和元数据增强来提升特定领域语料库的检索效果。这种名为“MetaGen混合RAG”的方法利用关键概念、主题和缩略语构建元数据生成管道，然后创建带有增强元数据的混合索引，并提升搜索查询。此方法避免了过拟合，并在跨领域时实现了有效的泛化。在生物医学领域的PubMedQA基准测试中，该方法实现了82%的检索准确率和77%的RAG准确率，超越了所有先前未经微调的RAG准确度结果，同时为零样本结果设定了新基准，并优于GPT3.5等更大规模的模型。结果甚至可以与该数据集上表现最佳的微调模型相媲美，我们进一步通过在SQuAD、NQ等其他问答数据集上的评估，证明了该方法的鲁棒性和可扩展性。

> Despite the widespread exploration of Retrieval-Augmented Generation (RAG), its deployment in enterprises for domain-specific datasets remains limited due to poor answer accuracy. These corpora, often shielded behind firewalls in private enterprise knowledge bases, having complex, domain-specific terminology, rarely seen by LLMs during pre-training; exhibit significant semantic variability across domains (like networking, military, or legal, etc.), or even within a single domain like medicine, and thus result in poor context precision for RAG systems. Currently, in such situations, fine-tuning or RAG with fine-tuning is attempted, but these approaches are slow, expensive, and lack generalization for accuracy as the new domain-specific data emerges. We propose an approach for Enterprise Search that focuses on enhancing the retriever for a domain-specific corpus through hybrid query indexes and metadata enrichment. This 'MetaGen Blended RAG' method constructs a metadata generation pipeline using key concepts, topics, and acronyms, and then creates a metadata-enriched hybrid index with boosted search queries. This approach avoids overfitting and generalizes effectively across domains. On the PubMedQA benchmark for the biomedical domain, the proposed method achieves 82% retrieval accuracy and 77% RAG accuracy, surpassing all previous RAG accuracy results without fine-tuning and sets a new benchmark for zero-shot results while outperforming much larger models like GPT3.5. The results are even comparable to the best fine-tuned models on this dataset, and we further demonstrate the robustness and scalability of the approach by evaluating it on other Q&A datasets like SQuAD, NQ etc.

[Arxiv](https://arxiv.org/abs/2505.18247)