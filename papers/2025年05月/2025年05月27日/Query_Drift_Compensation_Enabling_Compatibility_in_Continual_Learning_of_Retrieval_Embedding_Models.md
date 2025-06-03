# Query Drift Compensation: 在检索嵌入模型的持续学习中实现兼容性

发布时间：2025年05月27日

`RAG` `信息检索`

> Query Drift Compensation: Enabling Compatibility in Continual Learning of Retrieval Embedding Models

# 摘要

> 文本嵌入模型支持语义搜索，为检索增强生成等NLP应用提供高效信息检索(IR)能力。然而，这类模型通常在训练数据静态的场景下研究，因此其应用受限于动态场景，即随着时间推移出现新训练数据的情况。信息检索方法通常将大量文档编码为低维嵌入，并存储在数据库索引中。检索时，会在文档集中执行语义搜索，并返回与查询嵌入最相似的文档嵌入。当使用新训练数据更新嵌入模型时，由于模型已更改，导致嵌入不兼容，因此使用已索引的文档集效果不佳。虽然使用更新后的模型重新索引旧文档集可以实现兼容，但这需要更高的计算和时间成本。因此，研究如何在无需重新索引的情况下有效利用已索引文档集至关重要。

在本研究中，我们使用大规模数据集建立了一个持续学习基准，并在每个任务中对来自新数据集的查询-文档对进行密集检索嵌入模型的持续训练，观察到由于嵌入显著漂移导致的旧任务遗忘现象。我们在查询和文档嵌入上采用嵌入蒸馏以维持稳定性，并在检索过程中提出了一种新颖的查询漂移补偿方法，将新模型的查询嵌入投影到旧嵌入空间中。这使得新模型能够与使用旧模型提取的先前索引文档嵌入兼容，从而减少遗忘。我们证明了所提方法在无需任何重新索引的情况下显著提升了性能。代码可在https://github.com/dipamgoswami/QDC获取。

> Text embedding models enable semantic search, powering several NLP applications like Retrieval Augmented Generation by efficient information retrieval (IR). However, text embedding models are commonly studied in scenarios where the training data is static, thus limiting its applications to dynamic scenarios where new training data emerges over time. IR methods generally encode a huge corpus of documents to low-dimensional embeddings and store them in a database index. During retrieval, a semantic search over the corpus is performed and the document whose embedding is most similar to the query embedding is returned. When updating an embedding model with new training data, using the already indexed corpus is suboptimal due to the non-compatibility issue, since the model which was used to obtain the embeddings of the corpus has changed. While re-indexing of old corpus documents using the updated model enables compatibility, it requires much higher computation and time. Thus, it is critical to study how the already indexed corpus can still be effectively used without the need of re-indexing. In this work, we establish a continual learning benchmark with large-scale datasets and continually train dense retrieval embedding models on query-document pairs from new datasets in each task and observe forgetting on old tasks due to significant drift of embeddings. We employ embedding distillation on both query and document embeddings to maintain stability and propose a novel query drift compensation method during retrieval to project new model query embeddings to the old embedding space. This enables compatibility with previously indexed corpus embeddings extracted using the old model and thus reduces the forgetting. We show that the proposed method significantly improves performance without any re-indexing. Code is available at https://github.com/dipamgoswami/QDC.

[Arxiv](https://arxiv.org/abs/2506.00037)