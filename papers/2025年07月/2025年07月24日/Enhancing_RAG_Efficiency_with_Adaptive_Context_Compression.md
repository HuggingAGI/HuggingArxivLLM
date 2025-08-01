# # 提升RAG效率的自适应上下文压缩方法
自适应上下文压缩优化RAG效率

发布时间：2025年07月24日

`RAG` `问答系统`

> Enhancing RAG Efficiency with Adaptive Context Compression

# 摘要

> 检索增强生成（RAG）通过引入外部知识增强了大型语言模型（LLMs），但因检索到的长上下文导致推理成本显著增加。尽管上下文压缩缓解了这一问题，但现有方法采用固定压缩率，对简单查询过度压缩或对复杂查询压缩不足。我们提出自适应上下文压缩框架ACC-RAG，该框架根据输入复杂度动态调整压缩率，在不降低准确性的同时优化推理效率。ACC-RAG结合层次化压缩器（用于多粒度嵌入）与上下文选择器，保留最小必要信息，类似于人类的快速浏览。在维基百科和五个问答数据集上的评估表明，ACC-RAG超越固定压缩率方法，相比标准RAG实现4倍以上的推理加速，同时保持或提升准确率。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) with external knowledge but incurs significant inference costs due to lengthy retrieved contexts. While context compression mitigates this issue, existing methods apply fixed compression rates, over-compressing simple queries or under-compressing complex ones. We propose Adaptive Context Compression for RAG (ACC-RAG), a framework that dynamically adjusts compression rates based on input complexity, optimizing inference efficiency without sacrificing accuracy. ACC-RAG combines a hierarchical compressor (for multi-granular embeddings) with a context selector to retain minimal sufficient information, akin to human skimming. Evaluated on Wikipedia and five QA datasets, ACC-RAG outperforms fixed-rate methods and matches/unlocks over 4 times faster inference versus standard RAG while maintaining or improving accuracy.

[Arxiv](https://arxiv.org/abs/2507.22931)