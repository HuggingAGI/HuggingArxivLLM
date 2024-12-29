# 朝着构建新加坡及其他地区的语音基础模型迈进

发布时间：2024年12月16日

`LLM应用` `语音处理` `新加坡`

> Towards a Speech Foundation Model for Singapore and Beyond

# 摘要

> 此技术报告介绍了 MERaLiON 语音编码器，这一基础模型旨在助力众多下游语音应用。作为新加坡国家多模态大型语言模型计划的一部分所开发，MERaLiON 语音编码器专为满足新加坡及周边东南亚地区的语音处理需求而打造。目前，该模型主要支持英语，包括新加坡使用的各类英语。我们正积极扩充数据集，以在后续版本中逐步涵盖其他语言。MERaLiON 语音编码器基于掩码语言建模的自监督学习方式，从零开始在 20 万小时的未标注语音数据上完成了预训练。下文将详细阐述我们的训练流程和超参数调试实验。我们的评估显示，在语音识别的自发和新加坡语音基准方面有了提升，同时在其他十个语音任务中与其他先进的语音编码器相比也不落下风。我们承诺发布模型，为新加坡及其他地区更广泛的研究工作提供支持。

> This technical report describes the MERaLiON Speech Encoder, a foundation model designed to support a wide range of downstream speech applications. Developed as part of Singapore's National Multimodal Large Language Model Programme, the MERaLiON Speech Encoder is tailored to address the speech processing needs in Singapore and the surrounding Southeast Asian region. The model currently supports mainly English, including the variety spoken in Singapore. We are actively expanding our datasets to gradually cover other languages in subsequent releases. The MERaLiON Speech Encoder was pre-trained from scratch on 200K hours of unlabelled speech data using a self-supervised learning approach based on masked language modelling. We describe our training procedure and hyperparameter tuning experiments in detail below. Our evaluation demonstrates improvements to spontaneous and Singapore speech benchmarks for speech recognition, while remaining competitive to other state-of-the-art speech encoders across ten other speech tasks. We commit to releasing our model, supporting broader research endeavours, both in Singapore and beyond.

[Arxiv](https://arxiv.org/abs/2412.11538)