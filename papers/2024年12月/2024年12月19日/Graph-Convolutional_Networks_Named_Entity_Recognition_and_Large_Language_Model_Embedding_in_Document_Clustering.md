# 图卷积网络：在文档聚类中的命名实体识别与大型语言模型嵌入

发布时间：2024年12月19日

`LLM应用` `机器学习` `文档聚类`

> Graph-Convolutional Networks: Named Entity Recognition and Large Language Model Embedding in Document Clustering

# 摘要

> 机器学习领域近来取得了显著进展，尤其是像 BERT 和 GPT 这类大型语言模型（LLMs），它们提供了丰富的上下文嵌入，优化了文本的表示效果。但当下的文档聚类方式往往忽视了命名实体（NEs）之间的深层关联以及 LLM 嵌入的潜力。此文提出了一种创新的方法，即在基于图的框架中将命名实体识别（NER）与 LLM 嵌入相结合用于文档聚类。该方法构建了一个图，图中节点代表文档，边依据命名实体相似度加权，并通过图卷积网络（GCN）进行优化。如此便能确保语义相关的文档更有效地分组。实验结果显示，我们的方法在聚类方面优于传统的基于共现的方法，对于富含命名实体的文档尤其如此。

> Recent advances in machine learning, particularly Large Language Models (LLMs) such as BERT and GPT, provide rich contextual embeddings that improve text representation. However, current document clustering approaches often ignore the deeper relationships between named entities (NEs) and the potential of LLM embeddings. This paper proposes a novel approach that integrates Named Entity Recognition (NER) and LLM embeddings within a graph-based framework for document clustering. The method builds a graph with nodes representing documents and edges weighted by named entity similarity, optimized using a graph-convolutional network (GCN). This ensures a more effective grouping of semantically related documents. Experimental results indicate that our approach outperforms conventional co-occurrence-based methods in clustering, notably for documents rich in named entities.

[Arxiv](https://arxiv.org/abs/2412.14867)