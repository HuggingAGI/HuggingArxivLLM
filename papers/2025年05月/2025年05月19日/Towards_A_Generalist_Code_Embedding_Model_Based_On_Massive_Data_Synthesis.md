# 构建基于海量数据合成的通用型代码嵌入模型

发布时间：2025年05月19日

`RAG` `软件工程` `人工智能`

> Towards A Generalist Code Embedding Model Based On Massive Data Synthesis

# 摘要

> 代码嵌入模型因检索增强生成（RAG）在软件开发中的普及而备受关注。这些模型致力于捕捉代码中丰富的语义关系，这些关系与文本中的关系有着显著不同。然而，现有模型仍受限于高质量训练数据的匮乏。在本研究中，我们推出**CodeR**（**Code** **R**etrieval），一款面向通用代码检索的先进嵌入模型。CodeR的出色表现依托于CodeR-Pile，这是一个遵循DRU（多样性、可靠性、可用性）原则，通过创新数据合成管道构建的大型合成数据集。为优化训练效果，我们提出Annealing课程学习策略，实现异源数据间的高效知识迁移。我们在16个多样化代码检索任务中对CodeR进行了评估，结果显示其显著超越现有基线模型，并展现出强大的跨领域泛化能力。我们已公开发布代码和预训练模型，以助力该领域的进一步研究。访问https://github.com/FlagOpen/FlagEmbedding/tree/master/research/BGE_Coder获取更多信息。

> Code embedding models attract increasing attention due to the widespread popularity of retrieval-augmented generation (RAG) in software development. These models are expected to capture the rich semantic relationships inherent to code, which differ significantly from those found in text. However, existing models remain severely limited due to the scarcity of high-quality training data. In this work, we introduce \textbf{CodeR} (underline{Code} underline{R}etrieval), a state-of-the-art embedding model for general-purpose code retrieval. The superior performance of CodeR is built upon CodeR-Pile, a large-scale synthetic dataset constructed under the DRU (Diversity, Reliability, Usability) principle via a novel data synthesis pipeline. To optimize training effectiveness, we propose Annealing, a curriculum learning strategy that enables effective knowledge transfer across heterogeneous sources of data. We evaluate CodeR based on 16 diverse code retrieval tasks, where it significantly outperforms existing baselines and exhibits strong out-of-domain generalization performance. We have publicly released our code and the well-trained model to facilitate further research in this critical area. https://github.com/FlagOpen/FlagEmbedding/tree/master/research/BGE_Coder.

[Arxiv](https://arxiv.org/abs/2505.12697)