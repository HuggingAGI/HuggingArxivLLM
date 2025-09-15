# SignClip：基于多模态对比融合的口型线索手语翻译方法

发布时间：2025年09月12日

`其他` `媒体与娱乐`

> SignClip: Leveraging Mouthing Cues for Sign Language Translation by Multimodal Contrastive Fusion

# 摘要

> 手语翻译（SLT）旨在将手语视频翻译成自然语言，是实现包容性沟通的重要桥梁。尽管近年来的研究借助强大的视觉主干和大型语言模型取得进展，但多数方法仍聚焦于手部信号（手势），却常忽略口型等非手部线索。实际上，口型在手语中承载着关键语言信息，对区分视觉相似的手语至关重要。本文提出SignClip——一个提升手语翻译准确性的新型框架，它融合手部与非手部线索，具体包括空间手势和唇部动作特征。此外，SignClip引入具有多级对齐目标的分层对比学习框架，确保手语-唇部与视觉-文本模态间的语义一致性。在PHOENIX14T和How2Sign两个基准数据集上的大量实验验证了该方法的优越性：例如在PHOENIX14T的无Gloss设置下，SignClip超越此前最先进模型SpaMo，BLEU-4从24.32提升至24.71，ROUGE从46.57提升至48.38。

> Sign language translation (SLT) aims to translate natural language from sign language videos, serving as a vital bridge for inclusive communication. While recent advances leverage powerful visual backbones and large language models, most approaches mainly focus on manual signals (hand gestures) and tend to overlook non-manual cues like mouthing. In fact, mouthing conveys essential linguistic information in sign languages and plays a crucial role in disambiguating visually similar signs. In this paper, we propose SignClip, a novel framework to improve the accuracy of sign language translation. It fuses manual and non-manual cues, specifically spatial gesture and lip movement features. Besides, SignClip introduces a hierarchical contrastive learning framework with multi-level alignment objectives, ensuring semantic consistency across sign-lip and visual-text modalities. Extensive experiments on two benchmark datasets, PHOENIX14T and How2Sign, demonstrate the superiority of our approach. For example, on PHOENIX14T, in the Gloss-free setting, SignClip surpasses the previous state-of-the-art model SpaMo, improving BLEU-4 from 24.32 to 24.71, and ROUGE from 46.57 to 48.38.

[Arxiv](https://arxiv.org/abs/2509.10266)