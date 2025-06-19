# # SonicVerse：多任务学习助力基于音乐特征的字幕生成

发布时间：2025年06月18日

`LLM应用

理由：这篇论文主要探讨了多任务音乐描述模型 SonicVerse 的设计与应用，结合了描述生成和音乐特征检测任务，并利用大型语言模型生成详细的时间感知描述。虽然涉及大型语言模型的应用，但主要聚焦于音乐描述生成的实际应用，属于LLM应用类别。` `人工智能`

> SonicVerse: Multi-Task Learning for Music Feature-Informed Captioning

# 摘要

> 详细且准确的音乐描述不仅能够丰富音乐数据库，更能推动音乐人工智能的研究。本文提出的多任务音乐描述模型 SonicVerse，将描述生成与音调检测、人声检测等辅助音乐特征检测任务相结合，能够同时捕捉低层次的声学细节和高层次的音乐属性。其核心创新在于一种基于投影的架构，该架构可将音频输入转换为语言令牌，同时通过专用辅助头检测音乐特征。这些辅助头的输出也被投影为语言令牌，从而增强描述生成的效果。该框架不仅能够为短音乐片段生成丰富、描述性的文本，还能够通过结合大型语言模型的输出，直接生成针对较长音乐作品的详细时间感知描述。在训练过程中，我们扩展了 MusicBench 数据集，使用模块化音乐特征提取器 MIRFLEX 注释了音乐特征，从而得到了配对的音频、描述和音乐特征数据。实验结果表明，这种特征整合方式显著提升了生成描述的质量和细节丰富度。

> Detailed captions that accurately reflect the characteristics of a music piece can enrich music databases and drive forward research in music AI. This paper introduces a multi-task music captioning model, SonicVerse, that integrates caption generation with auxiliary music feature detection tasks such as key detection, vocals detection, and more, so as to directly capture both low-level acoustic details as well as high-level musical attributes. The key contribution is a projection-based architecture that transforms audio input into language tokens, while simultaneously detecting music features through dedicated auxiliary heads. The outputs of these heads are also projected into language tokens, to enhance the captioning input. This framework not only produces rich, descriptive captions for short music fragments but also directly enables the generation of detailed time-informed descriptions for longer music pieces, by chaining the outputs using a large-language model. To train the model, we extended the MusicBench dataset by annotating it with music features using MIRFLEX, a modular music feature extractor, resulting in paired audio, captions and music feature data. Experimental results show that incorporating features in this way improves the quality and detail of the generated captions.

[Arxiv](https://arxiv.org/abs/2506.15154)