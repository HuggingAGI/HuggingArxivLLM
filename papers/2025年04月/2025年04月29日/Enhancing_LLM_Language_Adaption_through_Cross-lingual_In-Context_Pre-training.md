# # 跨语言上下文预训练助力提升LLM的语言适应能力

发布时间：2025年04月29日

`LLM理论` `机器翻译`

> Enhancing LLM Language Adaption through Cross-lingual In-Context Pre-training

# 摘要

> 大型语言模型（LLMs）虽然主要基于英语进行预训练，却在多语言任务中表现出色，这得益于预训练过程中形成的跨语言机制。然而，现有的跨语言迁移方法仍受限于平行资源，面临语言和领域覆盖不足的问题。为此，我们提出了一种简单且高效的跨语言上下文预训练方法（CrossIC-PT）。该方法通过利用语义相关的双语文本，并结合简单的下一个单词预测任务，有效提升了跨语言迁移能力。

具体而言，我们通过交错排列语义相关的双语维基百科文档，构建了一个统一的上下文窗口来生成CrossIC-PT训练样本。为应对窗口大小限制，我们设计了一种系统化的分段策略，将长篇双语文档分割为多个片段，同时优化滑动窗口机制以保持上下文连贯性。此外，我们还引入了一个语义检索框架，从网络爬取的语料库中进一步扩展数据来源，构建更多CrossIC-PT样本。

实验结果表明，CrossIC-PT在三个主流模型（Llama-3.1-8B、Qwen2.5-7B 和 Qwen2.5-1.5B）上，针对六种目标语言的多语言性能均实现了显著提升，分别带来了3.79%、3.99%和1.95%的性能增益。经过数据增强后，性能提升更加明显。

> Large language models (LLMs) exhibit remarkable multilingual capabilities despite English-dominated pre-training, attributed to cross-lingual mechanisms during pre-training. Existing methods for enhancing cross-lingual transfer remain constrained by parallel resources, suffering from limited linguistic and domain coverage. We propose Cross-lingual In-context Pre-training (CrossIC-PT), a simple and scalable approach that enhances cross-lingual transfer by leveraging semantically related bilingual texts via simple next-word prediction. We construct CrossIC-PT samples by interleaving semantic-related bilingual Wikipedia documents into a single context window. To access window size constraints, we implement a systematic segmentation policy to split long bilingual document pairs into chunks while adjusting the sliding window mechanism to preserve contextual coherence. We further extend data availability through a semantic retrieval framework to construct CrossIC-PT samples from web-crawled corpus. Experimental results demonstrate that CrossIC-PT improves multilingual performance on three models (Llama-3.1-8B, Qwen2.5-7B, and Qwen2.5-1.5B) across six target languages, yielding performance gains of 3.79%, 3.99%, and 1.95%, respectively, with additional improvements after data augmentation.

[Arxiv](https://arxiv.org/abs/2504.20484)