# 对比提示通过推理过程中的引导增强大型语言模型中的句子嵌入

发布时间：2025年05月19日

`LLM应用` `机器学习`

> Contrastive Prompting Enhances Sentence Embeddings in LLMs through Inference-Time Steering

# 摘要

> 从大型语言模型（LLMs）中提取句子嵌入是一种实用方法，无需额外数据或微调。以往研究通常关注提示工程，引导LLMs将句子的核心语义信息编码到最后一个标记的嵌入中。然而，这些方法中最后一个标记仍编码大量非关键信息（如停用词），限制了其编码能力。为此，我们提出了一种对比提示（CP）方法，通过引入额外的辅助提示来提取更好的句子嵌入。通过与辅助提示进行对比，CP能够引导现有提示关注句子的核心语义，而非非关键信息。CP是一种即插即用的推理时干预方法，可与各种基于提示的方法结合使用。在语义文本相似度（STS）任务和下游分类任务上的广泛实验表明，我们的方法能够提升现有基于提示的方法在不同LLMs上的性能。我们的代码将在https://github.com/zifengcheng/CP上发布。

> Extracting sentence embeddings from large language models (LLMs) is a practical direction, as it requires neither additional data nor fine-tuning. Previous studies usually focus on prompt engineering to guide LLMs to encode the core semantic information of the sentence into the embedding of the last token. However, the last token in these methods still encodes an excess of non-essential information, such as stop words, limiting its encoding capacity. To this end, we propose a Contrastive Prompting (CP) method that introduces an extra auxiliary prompt to elicit better sentence embedding. By contrasting with the auxiliary prompt, CP can steer existing prompts to encode the core semantics of the sentence, rather than non-essential information. CP is a plug-and-play inference-time intervention method that can be combined with various prompt-based methods. Extensive experiments on Semantic Textual Similarity (STS) tasks and downstream classification tasks demonstrate that our method can improve the performance of existing prompt-based methods across different LLMs. Our code will be released at https://github.com/zifengcheng/CP.

[Arxiv](https://arxiv.org/abs/2505.12831)