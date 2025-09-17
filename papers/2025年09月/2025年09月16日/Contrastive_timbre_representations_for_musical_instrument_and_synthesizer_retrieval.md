# 面向乐器与合成器检索的对比音色表征

发布时间：2025年09月16日

`其他` `媒体与娱乐`

> Contrastive timbre representations for musical instrument and synthesizer retrieval

# 摘要

> 在数字音乐制作领域，如何从音频混合中高效提取特定乐器的音色一直是个难题。本文提出了一个乐器检索对比学习框架，只需一个模型就能直接查询乐器数据库，无论是单乐器还是多乐器声音都适用。针对采样器、合成器等虚拟乐器，我们设计了生成逼真正/负声音对的技术，解决了常见音频数据增强方法的局限性。
  第一个实验以3,884种乐器的数据集为对象，输入单乐器音频进行检索。结果显示，对比学习方法与基于分类预训练的现有研究相比毫不逊色。第二个实验则聚焦多乐器混合音频的检索任务，此时我们提出的对比框架表现更优，在三乐器混合场景中，top-1准确率达81.7%，top-5准确率达95.7%。

> Efficiently retrieving specific instrument timbres from audio mixtures remains a challenge in digital music production. This paper introduces a contrastive learning framework for musical instrument retrieval, enabling direct querying of instrument databases using a single model for both single- and multi-instrument sounds. We propose techniques to generate realistic positive/negative pairs of sounds for virtual musical instruments, such as samplers and synthesizers, addressing limitations in common audio data augmentation methods.
  The first experiment focuses on instrument retrieval from a dataset of 3,884 instruments, using single-instrument audio as input. Contrastive approaches are competitive with previous works based on classification pre-training. The second experiment considers multi-instrument retrieval with a mixture of instruments as audio input. In this case, the proposed contrastive framework outperforms related works, achieving 81.7\% top-1 and 95.7\% top-5 accuracies for three-instrument mixtures.

[Arxiv](https://arxiv.org/abs/2509.13285)