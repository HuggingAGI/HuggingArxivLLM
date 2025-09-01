# 面向本体学习的异构LLM方法（少样本提示、集成类型与基于注意力的分类法）

发布时间：2025年08月26日

`RAG` `基础理论`

> Heterogeneous LLM Methods for Ontology Learning (Few-Shot Prompting, Ensemble Typing, and Attention-Based Taxonomies)

# 摘要

> 我们提出了一套完整方案，针对LLMs4OL 2025挑战赛的A、B、C三项任务——它们共同构成了完整的本体构建流程：术语提取、类型标注与分类体系发现。我们的方法融合了检索增强提示、零样本分类与基于注意力的图建模技术，每项技术均针对具体任务需求定制。任务A中，我们通过检索增强生成（RAG）管道，联合提取领域特定术语及其本体类型。我们将训练数据重构为文档与术语-类型的对应关系，测试时则通过语义相似的训练样例辅助推理。该单遍方法无需模型微调，且通过词汇增强有效提升了整体性能。任务B需为给定术语分配类型，我们采用双重策略应对：少样本场景下（针对有标注数据的领域），复用带少样本提示的RAG方案；零样本场景下（针对全新领域），则采用零样本分类器——融合多个嵌入模型的余弦相似度分数，并基于置信度加权。任务C中，我们将分类体系发现建模为图推理问题，利用类型标签的嵌入向量训练轻量级交叉注意力层，通过近似软邻接矩阵预测is-a关系。这些模块化、任务定制的解决方案帮助我们在三项任务的官方排行榜中均位列前茅。综上，这些策略充分体现了基于LLM的架构在跨异质领域本体学习中的可扩展性、适应性与鲁棒性。
  代码可在以下地址获取：https://github.com/BelyaevaAlex/LLMs4OL-Challenge-Alexbek

> We present a comprehensive system for addressing Tasks A, B, and C of the LLMs4OL 2025 challenge, which together span the full ontology construction pipeline: term extraction, typing, and taxonomy discovery. Our approach combines retrieval-augmented prompting, zero-shot classification, and attention-based graph modeling -- each tailored to the demands of the respective task. For Task A, we jointly extract domain-specific terms and their ontological types using a retrieval-augmented generation (RAG) pipeline. Training data was reformulated into a document to terms and types correspondence, while test-time inference leverages semantically similar training examples. This single-pass method requires no model finetuning and improves overall performance through lexical augmentation Task B, which involves assigning types to given terms, is handled via a dual strategy. In the few-shot setting (for domains with labeled training data), we reuse the RAG scheme with few-shot prompting. In the zero-shot setting (for previously unseen domains), we use a zero-shot classifier that combines cosine similarity scores from multiple embedding models using confidence-based weighting. In Task C, we model taxonomy discovery as graph inference. Using embeddings of type labels, we train a lightweight cross-attention layer to predict is-a relations by approximating a soft adjacency matrix. These modular, task-specific solutions enabled us to achieve top-ranking results in the official leaderboard across all three tasks. Taken together these strategies showcase the scalability, adaptability, and robustness of LLM-based architectures for ontology learning across heterogeneous domains.
  Code is available at: https://github.com/BelyaevaAlex/LLMs4OL-Challenge-Alexbek

[Arxiv](https://arxiv.org/abs/2508.19428)