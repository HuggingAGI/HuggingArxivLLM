# 扩散模型与自回归语言模型的对比：从文本嵌入视角分析

发布时间：2025年05月20日

`LLM应用` `文档检索` `信息检索`

> Diffusion vs. Autoregressive Language Models: A Text Embedding Perspective

# 摘要

> 基于大型语言模型（LLM）的嵌入模型正逐步超越BERT和T5模型，在文档检索等通用文本嵌入任务中表现更优。然而，LLM嵌入模型存在一个关键限制：其单向注意力机制与文本嵌入任务的双向特性存在不匹配。为此，我们提出采用扩散语言模型进行文本嵌入，这得益于其固有的双向架构以及在推理任务中匹敌甚至超越LLM的近期成功。我们进行了首个关于扩散语言嵌入模型的系统性研究，结果显示：在长文档检索中，其性能优于基于LLM的嵌入模型20%；在推理密集型检索中，性能提升8%；在指令遵循检索中，性能提升2%，并在传统文本嵌入基准测试中取得了具有竞争力的表现。我们的分析证实，双向注意力机制对于编码长篇和复杂文本中的全局上下文至关重要。

> Large language model (LLM)-based embedding models, benefiting from large scale pre-training and post-training, have begun to surpass BERT and T5-based models on general-purpose text embedding tasks such as document retrieval. However, a fundamental limitation of LLM embeddings lies in the unidirectional attention used during autoregressive pre-training, which misaligns with the bidirectional nature of text embedding tasks. To this end, We propose adopting diffusion language models for text embeddings, motivated by their inherent bidirectional architecture and recent success in matching or surpassing LLMs especially on reasoning tasks. We present the first systematic study of the diffusion language embedding model, which outperforms the LLM-based embedding model by 20% on long-document retrieval, 8% on reasoning-intensive retrieval, 2% on instruction-following retrieval, and achieve competitive performance on traditional text embedding benchmarks. Our analysis verifies that bidirectional attention is crucial for encoding global context in long and complex text.

[Arxiv](https://arxiv.org/abs/2505.15045)