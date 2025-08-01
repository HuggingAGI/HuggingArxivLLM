# Causal2Vec：提升解码器型LLM的多功能嵌入能力

发布时间：2025年07月31日

`LLM应用` `信息技术`

> Causal2Vec: Improving Decoder-only LLMs as Versatile Embedding Models

# 摘要

> 解码器型大型语言模型（LLMs）正在成为构建嵌入模型的理想选择，这些模型能够将自然语言文本的语义信息高效编码为密集向量表示，适用于多种嵌入任务。然而，现有方法主要通过去除LLMs中的因果注意力机制来实现双向注意力，这可能削弱模型在预训练中获得的语义信息提取能力。此外，领先的单向方法通常依赖额外输入文本来克服因果注意力的限制，这不可避免地增加了计算成本。针对这些问题，我们提出了Causal2Vec，这是一种专门针对解码器型LLMs的通用嵌入模型，旨在提升性能，同时保持原始架构不变且计算开销可控。具体来说，我们首先使用轻量级BERT式模型对输入文本进行预编码，生成一个上下文感知的单个标记，并将其附加到LLM输入序列的最前端，使每个标记无需关注未来标记即可捕获上下文信息。此外，为缓解由最后一个标记池化带来的近期偏差，并帮助LLMs更好地利用上下文感知标记中的语义信息，我们将上下文标记和EOS标记的最后一个隐藏状态拼接，作为最终的文本嵌入。在实际应用中，Causal2Vec在仅基于公开检索数据集训练的模型中，于MTEB基准测试中达到最先进的性能水平，同时将序列长度减少高达85%，推理时间减少高达82%，相较于最佳性能方法。

> Decoder-only large language models (LLMs) are increasingly used to build embedding models that effectively encode the semantic information of natural language texts into dense vector representations for various embedding tasks. However, many existing methods primarily focus on removing the causal attention mask in LLMs to enable bidirectional attention, potentially undermining the model's ability to extract semantic information acquired during pretraining. Additionally, leading unidirectional approaches often rely on extra input text to overcome the inherent limitations of causal attention, inevitably increasing computational costs. In this work, we propose Causal2Vec, a general-purpose embedding model tailored to enhance the performance of decoder-only LLMs without altering their original architectures or introducing significant computational overhead. Specifically, we first employ a lightweight BERT-style model to pre-encode the input text into a single Contextual token, which is then prepended to the LLM's input sequence, allowing each token to capture contextualized information even without attending to future tokens. Furthermore, to mitigate the recency bias introduced by last-token pooling and help LLMs better leverage the semantic information encoded in the Contextual token, we concatenate the last hidden states of Contextual and EOS tokens as the final text embedding. In practice, Causal2Vec achieves state-of-the-art performance on the Massive Text Embeddings Benchmark (MTEB) among models trained solely on publicly available retrieval datasets, while reducing the required sequence length by up to 85% and inference time by up to 82% compared to best-performing methods.

[Arxiv](https://arxiv.org/abs/2507.23386)