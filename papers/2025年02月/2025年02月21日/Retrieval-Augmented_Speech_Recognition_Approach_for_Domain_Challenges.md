# # 检索增强语音识别方法应对领域挑战

发布时间：2025年02月21日

`RAG` `语音识别` `领域适应`

> Retrieval-Augmented Speech Recognition Approach for Domain Challenges

# 摘要

> 语音识别系统在实际应用中常常面临领域不匹配的挑战，尤其是在数据获取受限或涉及保密性问题的情况下，难以获取领域特定数据。本文受大型语言模型（LLMs）中检索增强生成（RAG）技术启发，提出了一种基于LLM的检索增强语音识别方法。该方法在推理阶段引入领域特定文本数据，从而有效提升语音识别性能。与传统方法在训练阶段依赖领域特定文本数据不同，我们的模型通过学习如何利用提示中的文本信息，从而提升LLM解码器的语音识别性能。得益于RAG检索机制的优势，我们的方法能够高效访问本地领域特定文档，从而有效解决领域不匹配问题。实验结果表明，该方法在CSJ数据库上显著提升了语音识别准确率，甚至在未使用完整训练数据的情况下，也达到了当前最优的性能。

> Speech recognition systems often face challenges due to domain mismatch, particularly in real-world applications where domain-specific data is unavailable because of data accessibility and confidentiality constraints. Inspired by Retrieval-Augmented Generation (RAG) techniques for large language models (LLMs), this paper introduces a LLM-based retrieval-augmented speech recognition method that incorporates domain-specific textual data at the inference stage to enhance recognition performance. Rather than relying on domain-specific textual data during the training phase, our model is trained to learn how to utilize textual information provided in prompts for LLM decoder to improve speech recognition performance. Benefiting from the advantages of the RAG retrieval mechanism, our approach efficiently accesses locally available domain-specific documents, ensuring a convenient and effective process for solving domain mismatch problems. Experiments conducted on the CSJ database demonstrate that the proposed method significantly improves speech recognition accuracy and achieves state-of-the-art results on the CSJ dataset, even without relying on the full training data.

[Arxiv](https://arxiv.org/abs/2502.15264)