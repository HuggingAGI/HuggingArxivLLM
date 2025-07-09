# DocIE@XLLM25：基于完全合成的演示，探索用于信息抽取任务的上下文学习方法。

发布时间：2025年07月08日

`LLM应用` `人工智能`

> DocIE@XLLM25: In-Context Learning for Information Extraction using Fully Synthetic Demonstrations

# 摘要

> 在零样本或少样本场景下，文档级实体和关系抽取领域仍面临高质量标注语料库稀缺的问题。本文提出了一种基于大型语言模型的全自动合成数据生成与上下文学习管道，专为文档级实体和关系抽取设计。与现有依赖人工标注演示或直接零样本推理的方法不同，我们的创新之处在于结合了合成数据生成与基于检索的上下文学习，采用了一种优化推理的语言模型。这种方法不仅让我们能够无需人工标注即可构建高质量的演示数据库，还能够在推理过程中动态检索相关示例。基于此方法，我们生成了一个包含超过【数学公式】维基百科摘要的合成数据集，其中标注了约【数学公式】个实体和【数学公式】个关系三元组。最后，我们在DocIE共享任务上进行了零样本设置下的实体和关系抽取评估。结果表明，即使是当前最先进的大型语言模型，在文档级的上下文联合实体和关系抽取任务上仍然面临巨大挑战。

> Large, high-quality annotated corpora remain scarce in document-level entity and relation extraction in zero-shot or few-shot settings. In this paper, we present a fully automatic, LLM-based pipeline for synthetic data generation and in-context learning for document-level entity and relation extraction. In contrast to existing approaches that rely on manually annotated demonstrations or direct zero-shot inference, our method combines synthetic data generation with retrieval-based in-context learning, using a reasoning-optimized language model. This allows us to build a high-quality demonstration database without manual annotation and to dynamically retrieve relevant examples at inference time. Based on our approach we produce a synthetic dataset of over $5k$ Wikipedia abstracts with approximately $59k$ entities and $30k$ relation triples. Finally, we evaluate in-context learning performance on the DocIE shared task, extracting entities and relations from long documents in a zero-shot setting. We find that in-context joint entity and relation extraction at document-level remains a challenging task, even for state-of-the-art large language models.

[Arxiv](https://arxiv.org/abs/2507.05997)