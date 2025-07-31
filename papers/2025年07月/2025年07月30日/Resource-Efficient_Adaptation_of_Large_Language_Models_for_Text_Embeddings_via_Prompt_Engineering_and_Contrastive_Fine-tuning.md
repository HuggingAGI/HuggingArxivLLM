# # 资源高效适配：利用提示工程与对比微调优化大型语言模型的文本嵌入能力
研究通过提示工程和对比微调方法，实现大型语言模型在文本嵌入任务上的资源高效适配。

发布时间：2025年07月30日

`LLM应用` `大型语言模型` `文本嵌入`

> Resource-Efficient Adaptation of Large Language Models for Text Embeddings via Prompt Engineering and Contrastive Fine-tuning

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理 (NLP) 中占据核心地位，并在文本生成方面取得了卓越表现。它们的标记级表示捕获了丰富且符合人类认知的语义信息。然而，将这些向量池化为文本嵌入会丢失关键信息。尽管如此，许多非生成的下游任务，如聚类、分类或检索，仍然依赖于准确且可控的句级或文档级嵌入。我们探讨了针对预训练、仅解码器的 LLM 的几种适应策略：(i) 不同的标记嵌入聚合技术，(ii) 任务特定的提示工程，以及 (iii) 通过对比微调进行文本级增强。将这些组件结合起来，在 MTEB 的英语聚类任务中取得了最先进的性能。对注意力图的分析进一步表明，微调使模型关注从提示标记转移到语义相关的单词，表明最终隐藏状态中意义的压缩更加有效。我们的实验表明，通过结合提示工程和在合成生成的正对上进行资源高效的对比微调，可以有效地将 LLM 适应为文本嵌入模型。

> Large Language Models (LLMs) have become a cornerstone in Natural Language Processing (NLP), achieving impressive performance in text generation. Their token-level representations capture rich, human-aligned semantics. However, pooling these vectors into a text embedding discards crucial information. Nevertheless, many non-generative downstream tasks, such as clustering, classification, or retrieval, still depend on accurate and controllable sentence- or document-level embeddings. We explore several adaptation strategies for pre-trained, decoder-only LLMs: (i) various aggregation techniques for token embeddings, (ii) task-specific prompt engineering, and (iii) text-level augmentation via contrastive fine-tuning. Combining these components yields state-of-the-art performance on the English clustering track of the Massive Text Embedding Benchmark (MTEB). An analysis of the attention map further shows that fine-tuning shifts focus from prompt tokens to semantically relevant words, indicating more effective compression of meaning into the final hidden state. Our experiments demonstrate that LLMs can be effectively adapted as text embedding models through a combination of prompt engineering and resource-efficient contrastive fine-tuning on synthetically generated positive pairs.

[Arxiv](https://arxiv.org/abs/2507.22729)