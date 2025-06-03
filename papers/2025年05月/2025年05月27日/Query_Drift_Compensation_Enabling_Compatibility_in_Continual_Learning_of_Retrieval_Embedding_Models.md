# 补偿Query漂移，实现检索嵌入模型的持续学习兼容性

发布时间：2025年05月27日

`LLM应用` `信息检索`

> Query Drift Compensation: Enabling Compatibility in Continual Learning of Retrieval Embedding Models

# 摘要

> 文本嵌入模型支持语义搜索，为多个NLP应用（如基于检索增强生成）提供高效信息检索（IR）能力。然而，现有研究主要集中在训练数据静态的场景，限制了其在动态场景中的应用潜力。传统IR方法通过将大规模文档集编码为低维嵌入并存储在数据库中实现检索。但在模型更新时，由于嵌入空间的变化，旧语料库无法直接复用，重新索引又面临高昂成本。本研究建立了一个大规模持续学习基准，通过持续训练密集检索嵌入模型来适应新数据集的查询-文档对。我们发现，模型更新会导致旧任务性能显著下降。为此，我们提出了嵌入蒸馏和查询漂移补偿方法，通过将新模型的查询嵌入映射到旧空间，实现了与旧索引的兼容，有效缓解了遗忘问题。实验表明，该方法在无需重新索引的情况下显著提升了性能。代码已开源，地址为https://github.com/dipamgoswami/QDC。

> Text embedding models enable semantic search, powering several NLP applications like Retrieval Augmented Generation by efficient information retrieval (IR). However, text embedding models are commonly studied in scenarios where the training data is static, thus limiting its applications to dynamic scenarios where new training data emerges over time. IR methods generally encode a huge corpus of documents to low-dimensional embeddings and store them in a database index. During retrieval, a semantic search over the corpus is performed and the document whose embedding is most similar to the query embedding is returned. When updating an embedding model with new training data, using the already indexed corpus is suboptimal due to the non-compatibility issue, since the model which was used to obtain the embeddings of the corpus has changed. While re-indexing of old corpus documents using the updated model enables compatibility, it requires much higher computation and time. Thus, it is critical to study how the already indexed corpus can still be effectively used without the need of re-indexing. In this work, we establish a continual learning benchmark with large-scale datasets and continually train dense retrieval embedding models on query-document pairs from new datasets in each task and observe forgetting on old tasks due to significant drift of embeddings. We employ embedding distillation on both query and document embeddings to maintain stability and propose a novel query drift compensation method during retrieval to project new model query embeddings to the old embedding space. This enables compatibility with previously indexed corpus embeddings extracted using the old model and thus reduces the forgetting. We show that the proposed method significantly improves performance without any re-indexing. Code is available at https://github.com/dipamgoswami/QDC.

[Arxiv](https://arxiv.org/abs/2506.00037)