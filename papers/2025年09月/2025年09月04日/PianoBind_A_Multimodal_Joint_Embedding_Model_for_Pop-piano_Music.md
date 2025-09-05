# PianoBind：面向流行钢琴音乐的多模态联合嵌入模型

发布时间：2025年09月04日

`其他` `媒体与娱乐`

> PianoBind: A Multimodal Joint Embedding Model for Pop-piano Music

# 摘要

> 尽管独奏钢琴曲仅用单一乐器演绎，却拥有极强的表现力，能跨流派、情绪与风格传递丰富的语义内涵。但目前主流的通用音乐表示模型大多基于大规模数据集训练，在捕捉同质独奏钢琴曲的细微语义差异时常常力不从心。此外，现有钢琴专用表示模型多为单模态，未能捕捉钢琴音乐本质上的多模态特性，而这种特性通过音频、符号和文本等模态共同体现。针对这些问题，我们提出了PianoBind——一款专为钢琴设计的多模态联合嵌入模型。我们在一个联合嵌入框架中系统探索了多源训练与模态利用策略，该框架经优化后可精准捕捉（1）小规模及（2）同质钢琴数据集中的细粒度语义差异。实验结果显示，PianoBind学习到的多模态表示能有效捕捉钢琴曲的细腻韵味，在域内与域外钢琴数据集上的文本到音乐检索性能均优于通用音乐联合嵌入模型。此外，我们的设计方案还为钢琴音乐之外的同质数据集多模态表示学习提供了可迁移的启示。

> Solo piano music, despite being a single-instrument medium, possesses significant expressive capabilities, conveying rich semantic information across genres, moods, and styles. However, current general-purpose music representation models, predominantly trained on large-scale datasets, often struggle to captures subtle semantic distinctions within homogeneous solo piano music. Furthermore, existing piano-specific representation models are typically unimodal, failing to capture the inherently multimodal nature of piano music, expressed through audio, symbolic, and textual modalities. To address these limitations, we propose PianoBind, a piano-specific multimodal joint embedding model. We systematically investigate strategies for multi-source training and modality utilization within a joint embedding framework optimized for capturing fine-grained semantic distinctions in (1) small-scale and (2) homogeneous piano datasets. Our experimental results demonstrate that PianoBind learns multimodal representations that effectively capture subtle nuances of piano music, achieving superior text-to-music retrieval performance on in-domain and out-of-domain piano datasets compared to general-purpose music joint embedding models. Moreover, our design choices offer reusable insights for multimodal representation learning with homogeneous datasets beyond piano music.

[Arxiv](https://arxiv.org/abs/2509.04215)