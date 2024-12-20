# Movie2Story：一个用于理解视频并以新颖文本形式讲述故事的框架

发布时间：2024年12月19日

`LLM应用` `多模态` `文本生成`

> Movie2Story: A framework for understanding videos and telling stories in the form of novel text

# 摘要

> 多模态视频到文本模型已取得显著进展，主要体现在对视频内容的简短描述生成上。但在生成融合视频与音频的丰富长文本描述方面，仍存在欠缺。本文引入了名为 M2S 的框架，旨在结合音频、视频和字符识别来生成新长度的文本。M2S 涵盖了用于视频长文本描述与理解、基于音频的情感、语速和字符对齐分析，以及基于视觉的字符识别对齐等模块。借助大型语言模型 GPT4o 整合多模态信息，M2S 在多模态文本生成领域表现出色。我们通过对比实验和人工评估，证实了 M2S 的有效性和准确性。此外，该模型框架具备良好的可扩展性，未来研究潜力巨大。

> Multimodal video-to-text models have made considerable progress, primarily in generating brief descriptions of video content. However, there is still a deficiency in generating rich long-form text descriptions that integrate both video and audio. In this paper, we introduce a framework called M2S, designed to generate novel-length text by combining audio, video, and character recognition. M2S includes modules for video long-form text description and comprehension, audio-based analysis of emotion, speech rate, and character alignment, and visual-based character recognition alignment. By integrating multimodal information using the large language model GPT4o, M2S stands out in the field of multimodal text generation. We demonstrate the effectiveness and accuracy of M2S through comparative experiments and human evaluation. Additionally, the model framework has good scalability and significant potential for future research.

[Arxiv](https://arxiv.org/abs/2412.14965)