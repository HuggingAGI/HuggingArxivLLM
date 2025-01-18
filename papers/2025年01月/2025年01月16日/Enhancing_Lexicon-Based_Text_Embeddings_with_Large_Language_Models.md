# 利用大型语言模型提升基于词典的文本嵌入效果

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）在文本嵌入任务中取得优异表现，并提出了一种新的基于词典的嵌入方法（LENS）。论文的核心是LLMs在具体任务中的应用，特别是如何通过改进嵌入方法来提升性能。因此，这篇论文应归类为LLM应用。` `信息检索`

> Enhancing Lexicon-Based Text Embeddings with Large Language Models

# 摘要

> # 摘要
近期的大型语言模型（LLMs）在通用文本嵌入任务中表现卓越。尽管密集嵌入在相关研究中占据主导，我们首次提出了基于词典的嵌入方法（LENS），利用LLMs在这些任务中取得了优异表现。针对传统因果LLMs中的标记化冗余和单向注意力限制，LENS通过标记嵌入聚类整合词汇空间，并探索了双向注意力和多种池化策略。具体而言，LENS通过将每个维度分配给特定标记簇来简化词典匹配，语义相似的标记被分组，并通过双向注意力充分释放LLMs的潜力。大量实验表明，LENS在MTEB上超越了密集嵌入，提供了与密集嵌入大小相当的紧凑特征表示。特别值得一提的是，LENS与密集嵌入的结合在MTEB的检索子集（BEIR）上达到了业界领先水平。

> Recent large language models (LLMs) have demonstrated exceptional performance on general-purpose text embedding tasks. While dense embeddings have dominated related research, we introduce the first Lexicon-based EmbeddiNgS (LENS) leveraging LLMs that achieve competitive performance on these tasks. Regarding the inherent tokenization redundancy issue and unidirectional attention limitations in traditional causal LLMs, LENS consolidates the vocabulary space through token embedding clustering, and investigates bidirectional attention and various pooling strategies. Specifically, LENS simplifies lexicon matching by assigning each dimension to a specific token cluster, where semantically similar tokens are grouped together, and unlocking the full potential of LLMs through bidirectional attention. Extensive experiments demonstrate that LENS outperforms dense embeddings on the Massive Text Embedding Benchmark (MTEB), delivering compact feature representations that match the sizes of dense counterparts. Notably, combining LENSE with dense embeddings achieves state-of-the-art performance on the retrieval subset of MTEB (i.e. BEIR).

[Arxiv](https://arxiv.org/abs/2501.09749)