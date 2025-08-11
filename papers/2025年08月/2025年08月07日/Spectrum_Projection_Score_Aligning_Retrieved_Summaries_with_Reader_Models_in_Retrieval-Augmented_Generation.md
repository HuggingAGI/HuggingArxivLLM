# 光谱投影评分：在检索增强生成中对齐摘要与读者模型

发布时间：2025年08月07日

`RAG` `问答系统`

> Spectrum Projection Score: Aligning Retrieved Summaries with Reader Models in Retrieval-Augmented Generation

# 摘要

> 借助检索增强生成（RAG）方法，遵循检索-阅读器范式，大型语言模型（LLMs）的生成性能得到了显著提升。然而，先前的研究通常会整体评估RAG，将检索器和阅读器的效果一并考量，这使得难以单独衡量检索的真实贡献，尤其是考虑到作为阅读器使用的LLMs对提示的敏感性。为此，我们引入了光谱投影得分（SPS），这是一种轻量级、无监督的指标，通过比较摘要生成的token形成的区域与读者子空间的主方向，来衡量检索摘要与其隐藏表示的语义对齐程度，并评估相关性。基于SPS，我们提出了一种推理时间控制器框架xCompress，它能够动态采样、排序和压缩检索摘要候选。在五个问答基准测试和四个开源LLMs上的广泛实验表明，SPS不仅提升了各项任务的性能，还为检索与生成之间的交互提供了一个合理化的视角。

> Large Language Models (LLMs) have shown improved generation performance through retrieval-augmented generation (RAG) following the retriever-reader paradigm, which supplements model inputs with externally retrieved knowledge. However, prior work often evaluates RAG holistically, assessing the retriever and reader jointly, making it difficult to isolate the true contribution of retrieval, particularly given the prompt sensitivity of LLMs used as readers. We introduce Spectrum Projection Score (SPS), a lightweight, supervision-free metric that allows the reader to gauge the semantic alignment of a retrieved summary with its hidden representation by comparing the area formed by generated tokens from the summary, and the principal directions of subspace in the reader and to measure the relevance. Building on SPS we present xCompress, an inference time controller framework that dynamically samples, ranks, and compresses retrieval summary candidates. Extensive experiments on five QA benchmarks with four open source LLMs show that SPS not only enhances performance across a range of tasks but also provides a principled perspective on the interaction between retrieval and generation.

[Arxiv](https://arxiv.org/abs/2508.05909)