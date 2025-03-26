# GINGER：基于扎根信息颗粒的响应生成

发布时间：2025年03月23日

`RAG` `问答系统`

> GINGER: Grounded Information Nugget-Based Generation of Responses

# 摘要

> 检索增强生成（RAG）正面临事实正确性、来源归属和响应完整性方面的挑战。我们提出了一种模块化的生成管道，该管道基于从检索到的文档中提取的信息块。该管道包含信息块检测、聚类、排序、顶级聚类摘要和流畅度提升等多个阶段。它不仅保证了对具体事实的依据，还促进了来源归属，并在长度限制内确保了最大信息的包含。实验结果表明，在TREC RAG'24数据集上，使用AutoNuggetizer框架评估，GINGER达到了最先进的性能。

> Retrieval-augmented generation (RAG) faces challenges related to factual correctness, source attribution, and response completeness. To address them, we propose a modular pipeline for grounded response generation that operates on information nuggets-minimal, atomic units of relevant information extracted from retrieved documents. The multistage pipeline encompasses nugget detection, clustering, ranking, top cluster summarization, and fluency enhancement. It guarantees grounding in specific facts, facilitates source attribution, and ensures maximum information inclusion within length constraints. Extensive experiments on the TREC RAG'24 dataset evaluated with the AutoNuggetizer framework demonstrate that GINGER achieves state-of-the-art performance on this benchmark.

[Arxiv](https://arxiv.org/abs/2503.18174)