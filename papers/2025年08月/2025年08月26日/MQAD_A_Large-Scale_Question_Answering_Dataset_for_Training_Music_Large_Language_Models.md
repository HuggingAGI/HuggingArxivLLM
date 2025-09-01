# MQAD：面向音乐大型语言模型训练的大规模问答数据集

发布时间：2025年08月26日

`LLM应用` `媒体与娱乐`

> MQAD: A Large-Scale Question Answering Dataset for Training Music Large Language Models

# 摘要

> 问答（QA）是人类理解一段音乐音频内容的自然方法。但对机器来说，获取覆盖音乐多方面的大规模数据集虽至关重要，却因这类公开音乐数据的稀缺而颇具挑战。本文介绍了MQAD——一个基于百万歌曲数据集（MSD）构建的音乐问答数据集，涵盖节拍、和弦、调式、结构、乐器、流派等丰富音乐特征，覆盖27万首歌曲，配有近300万条多样化的问题与描述。MQAD的独特之处在于提供和弦、段落等详细的时变音乐信息，从而能够深入探索歌曲的内在音乐结构。为构建MQAD，我们的方法借助专业的音乐信息检索（MIR）模型提取高层级音乐特征，同时利用大型语言模型（LLMs）生成自然语言问答对。实验表明，在MQAD上训练的模型在性能上超越了传统的音乐音频描述方法。该数据集和代码可通过https://github.com/oyzh888/MQAD获取。

> Question-answering (QA) is a natural approach for humans to understand a piece of music audio. However, for machines, accessing a large-scale dataset covering diverse aspects of music is crucial, yet challenging, due to the scarcity of publicly available music data of this type. This paper introduces MQAD, a music QA dataset built on the Million Song Dataset (MSD), encompassing a rich array of musical features, including beat, chord, key, structure, instrument, and genre -- across 270,000 tracks, featuring nearly 3 million diverse questions and captions. MQAD distinguishes itself by offering detailed time-varying musical information such as chords and sections, enabling exploration into the inherent structure of music within a song. To compile MQAD, our methodology leverages specialized Music Information Retrieval (MIR) models to extract higher-level musical features and Large Language Models (LLMs) to generate natural language QA pairs. Then, we leverage a multimodal LLM that integrates the LLaMA2 and Whisper architectures, along with novel subjective metrics to assess the performance of MQAD. In experiments, our model trained on MQAD demonstrates advancements over conventional music audio captioning approaches. The dataset and code are available at https://github.com/oyzh888/MQAD.

[Arxiv](https://arxiv.org/abs/2508.19514)