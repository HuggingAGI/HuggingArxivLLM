# ListConRanker: 基于列表编码的对比文本重排序器

发布时间：2025年01月13日

`RAG

理由：这篇论文主要讨论了重排序模型在检索增强生成（RAG）中的应用，特别是如何通过改进编码和损失函数来提升重排序的效果。重排序模型是RAG系统中的关键组件，用于优化检索结果的排序，从而提高生成模型的效果。因此，这篇论文应归类为RAG。` `信息检索`

> ListConRanker: A Contrastive Text Reranker with Listwise Encoding

# 摘要

> # 摘要
重排序模型通过衡量查询与段落间的语义相似性来重新排序段落，随着检索增强生成的广泛应用，这类模型备受关注。传统方法多采用点对点编码，仅能对每个段落编码查询上下文。然而，重排序模型更注重段落间的比较，即列表编码。此外，传统模型使用交叉熵损失函数训练，导致梯度变化不平滑、训练效率低下。为此，我们提出了一种新型列表编码对比文本重排序器（ListConRanker），在编码过程中引入段落间对比，增强正例间及正负例间的对比信息。同时，采用圆形损失训练模型，提升梯度灵活性并解决训练效率问题。实验表明，ListConRanker在中文大规模文本嵌入基准（如cMedQA1.0、cMedQA2.0、MMarcoReranking和T2Reranking数据集）上表现优异，达到业界领先水平。

> Reranker models aim to re-rank the passages based on the semantics similarity between the given query and passages, which have recently received more attention due to the wide application of the Retrieval-Augmented Generation. Most previous methods apply pointwise encoding, meaning that it can only encode the context of the query for each passage input into the model. However, for the reranker model, given a query, the comparison results between passages are even more important, which is called listwise encoding. Besides, previous models are trained using the cross-entropy loss function, which leads to issues of unsmooth gradient changes during training and low training efficiency. To address these issues, we propose a novel Listwise-encoded Contrastive text reRanker (ListConRanker). It can help the passage to be compared with other passages during the encoding process, and enhance the contrastive information between positive examples and between positive and negative examples. At the same time, we use the circle loss to train the model to increase the flexibility of gradients and solve the problem of training efficiency. Experimental results show that ListConRanker achieves state-of-the-art performance on the reranking benchmark of Chinese Massive Text Embedding Benchmark, including the cMedQA1.0, cMedQA2.0, MMarcoReranking, and T2Reranking datasets.

[Arxiv](https://arxiv.org/abs/2501.07111)