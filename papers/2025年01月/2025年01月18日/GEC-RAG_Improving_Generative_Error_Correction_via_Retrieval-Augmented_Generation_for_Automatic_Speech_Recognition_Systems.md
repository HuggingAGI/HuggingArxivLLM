# GEC-RAG: 利用检索增强生成技术提升自动语音识别系统的生成式错误纠正能力

发布时间：2025年01月18日

`RAG

理由：该论文提出了一种基于检索增强生成（RAG）的方法来提升自动语音识别（ASR）系统的性能，特别是在低资源语言（如波斯语）的领域。RAG方法通过检索与ASR转录相似的示例，为生成式大型语言模型（LLM）提供相关的系统错误模式，从而实现精准校正。这种方法的核心是利用RAG来增强ASR系统的性能，因此归类为RAG。` `语音识别` `低资源语言`

> GEC-RAG: Improving Generative Error Correction via Retrieval-Augmented Generation for Automatic Speech Recognition Systems

# 摘要

> # 摘要
自动语音识别（ASR）系统在多种应用中表现出色，但数据稀缺和特定领域（如低资源语言）的独特语言特征会显著降低其性能，导致更高的词错误率（WER）。本研究提出了一种基于检索增强生成（GEC-RAG）的生成式错误校正方法，旨在提升低资源领域（如波斯语）的ASR准确性。我们将ASR系统视为黑箱（这在云服务中很常见），并在上下文学习（ICL）框架下引入检索增强生成（RAG）方法，以提升ASR预测的质量。通过构建一个将ASR预测（1-best和5-best假设）与真实值配对的知识库，GEC-RAG利用词频-逆文档频率（TF-IDF）度量检索与ASR转录在词汇上相似的示例，从而为生成式大型语言模型（LLM）提供相关的系统错误模式，实现精准校正。实验结果表明，该策略显著降低了波斯语的WER，并展现了在领域适应和低资源场景中的潜力。这项研究证明了在不直接修改或微调模型的情况下，通过RAG增强ASR系统的有效性，只需更新转录知识库中的领域数据即可适应任何领域。

> Automatic Speech Recognition (ASR) systems have demonstrated remarkable performance across various applications. However, limited data and the unique language features of specific domains, such as low-resource languages, significantly degrade their performance and lead to higher Word Error Rates (WER). In this study, we propose Generative Error Correction via Retrieval-Augmented Generation (GEC-RAG), a novel approach designed to improve ASR accuracy for low-resource domains, like Persian. Our approach treats the ASR system as a black-box, a common practice in cloud-based services, and proposes a Retrieval-Augmented Generation (RAG) approach within the In-Context Learning (ICL) scheme to enhance the quality of ASR predictions. By constructing a knowledge base that pairs ASR predictions (1-best and 5-best hypotheses) with their corresponding ground truths, GEC-RAG retrieves lexically similar examples to the ASR transcription using the Term Frequency-Inverse Document Frequency (TF-IDF) measure. This process provides relevant error patterns of the system alongside the ASR transcription to the Generative Large Language Model (LLM), enabling targeted corrections. Our results demonstrate that this strategy significantly reduces WER in Persian and highlights a potential for domain adaptation and low-resource scenarios. This research underscores the effectiveness of using RAG in enhancing ASR systems without requiring direct model modification or fine-tuning, making it adaptable to any domain by simply updating the transcription knowledge base with domain-specific data.

[Arxiv](https://arxiv.org/abs/2501.10734)