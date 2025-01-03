# “我听说过你！”：为未知实体生成口语命名实体识别数据

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）生成句子，并结合文本到语音（TTS）系统来生成口语命名实体识别（NER）数据。这种方法旨在解决标注口语NER数据成本高昂的问题，并展示了在多个设置中的SOTA性能。因此，这篇论文属于LLM应用类别，因为它直接应用了LLM来解决实际问题。` `语音处理`

> "I've Heard of You!": Generate Spoken Named Entity Recognition Data for Unseen Entities

# 摘要

> # 摘要
口语命名实体识别（NER）在语音处理中至关重要，但新命名实体的不断涌现使得标注口语NER数据成本高昂。本文指出，现有系统在处理未见实体时表现欠佳。为此，我们提出了一种基于命名实体词典（NED）的低成本数据生成方法：利用大型语言模型（LLM）生成句子，再通过文本到语音（TTS）系统合成语音，并引入噪声度量过滤数据。我们发布了一个包含8,853个实体的新口语NER基准测试。实验显示，该方法在域内、零样本域适应和完全零样本设置中均达到了SOTA性能。数据可在https://github.com/DeepLearnXMU/HeardU获取。

> Spoken named entity recognition (NER) aims to identify named entities from speech, playing an important role in speech processing. New named entities appear every day, however, annotating their Spoken NER data is costly. In this paper, we demonstrate that existing Spoken NER systems perform poorly when dealing with previously unseen named entities. To tackle this challenge, we propose a method for generating Spoken NER data based on a named entity dictionary (NED) to reduce costs. Specifically, we first use a large language model (LLM) to generate sentences from the sampled named entities and then use a text-to-speech (TTS) system to generate the speech. Furthermore, we introduce a noise metric to filter out noisy data. To evaluate our approach, we release a novel Spoken NER benchmark along with a corresponding NED containing 8,853 entities. Experiment results show that our method achieves state-of-the-art (SOTA) performance in the in-domain, zero-shot domain adaptation, and fully zero-shot settings. Our data will be available at https://github.com/DeepLearnXMU/HeardU.

[Arxiv](https://arxiv.org/abs/2412.19102)