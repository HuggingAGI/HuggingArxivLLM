# 探索人类识别中多种步态模式的更多可能性

发布时间：2024年12月16日

`其他` `生物识别` `步态分析`

> Exploring More from Multiple Gait Modalities for Human Identification

# 摘要

> 步态作为一种软生物特征，能在远处反映出个人独特的行走模式，为无约束的人员识别提供了极具前景的技术。在很大程度上排除 RGB 视频中与步态无关的线索后，轮廓和骨架尽管视觉上较为紧凑，但长期以来一直是两种极为流行的步态模式。近来，已有多次尝试引入诸如人体解析和光流图像等更具信息量的数据形式来捕捉步态特征，同时还有多分支架构。然而，由于模型设计和实验设置不一致，我们认为对于这些流行的步态模式，在涉及表示能力和融合策略探索方面，仍缺乏全面且公平的比较研究。从精细与粗粒度形状以及整体与像素级运动建模的视角出发，本工作对三种流行的步态表示，即轮廓、人体解析和光流，展开了深入探究，并进行了各类融合评估，通过实验揭示了它们的异同。基于所得见解，我们进一步开发了 C$^2$Fusion 策略，进而构建了新框架 MultiGait++。C$^2$Fusion 保留共性并突出差异，以丰富步态特征的学习。为验证我们的发现和结论，在 Gait3D、GREW、CCPG 和 SUSTech1K 上开展了大量实验。代码可在 https://github.com/ShiqiYu/OpenGait 获取。

> The gait, as a kind of soft biometric characteristic, can reflect the distinct walking patterns of individuals at a distance, exhibiting a promising technique for unrestrained human identification. With largely excluding gait-unrelated cues hidden in RGB videos, the silhouette and skeleton, though visually compact, have acted as two of the most prevailing gait modalities for a long time. Recently, several attempts have been made to introduce more informative data forms like human parsing and optical flow images to capture gait characteristics, along with multi-branch architectures. However, due to the inconsistency within model designs and experiment settings, we argue that a comprehensive and fair comparative study among these popular gait modalities, involving the representational capacity and fusion strategy exploration, is still lacking. From the perspectives of fine vs. coarse-grained shape and whole vs. pixel-wise motion modeling, this work presents an in-depth investigation of three popular gait representations, i.e., silhouette, human parsing, and optical flow, with various fusion evaluations, and experimentally exposes their similarities and differences. Based on the obtained insights, we further develop a C$^2$Fusion strategy, consequently building our new framework MultiGait++. C$^2$Fusion preserves commonalities while highlighting differences to enrich the learning of gait features. To verify our findings and conclusions, extensive experiments on Gait3D, GREW, CCPG, and SUSTech1K are conducted. The code is available at https://github.com/ShiqiYu/OpenGait.

[Arxiv](https://arxiv.org/abs/2412.11495)