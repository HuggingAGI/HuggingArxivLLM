# AdaptiVocab：轻量级词汇适配，助力LLM在特定领域实现效率飞跃

发布时间：2025年03月25日

`LLM应用` `计算效率` `低资源领域`

> AdaptiVocab: Enhancing LLM Efficiency in Focused Domains through Lightweight Vocabulary Adaptation

# 摘要

> 大型语言模型（LLMs）作为通用模型，展现了令人印象深刻的多功能性。然而，这种广泛的适用性伴随着高昂的计算开销，尤其是在自回归解码过程中，每一步都需要进行前向传递。在特定领域场景中，通用能力往往是多余的，可以为了效率而进行替换。在本研究中，我们从一个全新的角度审视领域适应问题，通过将词汇表适应到特定关注领域，从而降低延迟和计算成本。

我们引入了AdaptiVocab，一种端到端的词汇表适应方法，旨在提升LLM在低资源领域中的效率。AdaptiVocab可以应用于任何分词器和架构，通过替换为基于特定领域n-gram的词汇，减少输入处理和输出生成所需的令牌数量。AdaptiVocab使用现有嵌入的指数加权组合初始化新的n-gram嵌入，并采用轻量级微调阶段，可以在单个GPU上高效完成。

我们在三个利基领域对两个70亿参数的LLM进行了评估，考察效率、生成质量和最终任务性能。实验结果表明，AdaptiVocab在不降低性能的前提下，将令牌使用量减少了25%以上。

> Large Language Models (LLMs) have shown impressive versatility as general purpose models. However, their broad applicability comes at a high-cost computational overhead, particularly in auto-regressive decoding where each step requires a forward pass. In domain-specific settings, general-purpose capabilities are unnecessary and can be exchanged for efficiency. In this work, we take a novel perspective on domain adaptation, reducing latency and computational costs by adapting the vocabulary to focused domains of interest. We introduce AdaptiVocab, an end-to-end approach for vocabulary adaptation, designed to enhance LLM efficiency in low-resource domains. AdaptiVocab can be applied to any tokenizer and architecture, modifying the vocabulary by replacing tokens with domain-specific n-gram-based tokens, thereby reducing the number of tokens required for both input processing and output generation. AdaptiVocab initializes new n-token embeddings using an exponentially weighted combination of existing embeddings and employs a lightweight fine-tuning phase that can be efficiently performed on a single GPU. We evaluate two 7B LLMs across three niche domains, assessing efficiency, generation quality, and end-task performance. Our results show that AdaptiVocab reduces token usage by over 25% without compromising performance

[Arxiv](https://arxiv.org/abs/2503.19693)