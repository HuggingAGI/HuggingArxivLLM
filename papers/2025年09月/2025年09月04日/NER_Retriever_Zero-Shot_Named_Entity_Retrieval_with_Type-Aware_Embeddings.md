# NER检索器：类型感知嵌入驱动的零样本命名实体检索

发布时间：2025年09月04日

`LLM应用` `基础理论`

> NER Retriever: Zero-Shot Named Entity Retrieval with Type-Aware Embeddings

# 摘要

> 我们提出了NER Retriever，这是一种用于特定命名实体检索的零样本检索框架。特定命名实体检索是命名实体识别（NER）的变体，该任务中，感兴趣的实体类型并非预先给定，而是通过用户定义的类型描述来检索提及该类型实体的文档。我们的方法不依赖固定模式或微调模型，而是借助大型语言模型（LLMs）的内部表示，将实体提及与用户提供的开放式类型描述共同嵌入到一个共享语义空间中。我们发现，内部表示（尤其是来自Transformer中间层的价值向量）比常用的顶层嵌入能更有效地编码细粒度类型信息。为优化这些表示，我们训练了一个轻量级对比投影网络，该网络能对齐类型兼容的实体，同时分离不相关的类型。由此得到的实体嵌入不仅紧凑且具有类型感知能力，同时非常适合最近邻搜索。在三个基准数据集上的评估结果显示，NER Retriever显著优于词汇检索和密集句级检索基线。我们的研究结果为LLMs内部表示的选择提供了实证支持，并为可扩展、无模式的实体检索提供了实用解决方案。NER Retriever代码库已公开，地址为https://github.com/ShacharOr100/ner_retriever

> We present NER Retriever, a zero-shot retrieval framework for ad-hoc Named Entity Retrieval, a variant of Named Entity Recognition (NER), where the types of interest are not provided in advance, and a user-defined type description is used to retrieve documents mentioning entities of that type. Instead of relying on fixed schemas or fine-tuned models, our method builds on internal representations of large language models (LLMs) to embed both entity mentions and user-provided open-ended type descriptions into a shared semantic space. We show that internal representations, specifically the value vectors from mid-layer transformer blocks, encode fine-grained type information more effectively than commonly used top-layer embeddings. To refine these representations, we train a lightweight contrastive projection network that aligns type-compatible entities while separating unrelated types. The resulting entity embeddings are compact, type-aware, and well-suited for nearest-neighbor search. Evaluated on three benchmarks, NER Retriever significantly outperforms both lexical and dense sentence-level retrieval baselines. Our findings provide empirical support for representation selection within LLMs and demonstrate a practical solution for scalable, schema-free entity retrieval. The NER Retriever Codebase is publicly available at https://github.com/ShacharOr100/ner_retriever

[Arxiv](https://arxiv.org/abs/2509.04011)