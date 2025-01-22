# 资源高效的遥感文本-图像检索训练框架

发布时间：2025年01月17日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型视觉-语言预训练模型来改进遥感文本-图像检索（RSTIR）任务。虽然论文中提到了大型视觉-语言预训练模型，但核心内容集中在如何优化这些模型在特定任务（遥感图像检索）中的应用，包括降低内存消耗、提高检索性能等。因此，这篇论文更适合归类为“LLM应用”，因为它主要关注的是如何将大型模型应用于具体的实际问题，而不是探讨模型的理论基础或构建新的模型架构。` `图像检索`

> A Resource-Efficient Training Framework for Remote Sensing Text--Image Retrieval

# 摘要

> # 摘要
遥感文本-图像检索（RSTIR）旨在根据描述性文本从数据库中检索匹配的遥感图像。近年来，大型视觉-语言预训练模型的快速发展为RSTIR带来了新的思路。然而，随着模型复杂度的增加，现有研究在迁移学习中的资源效率表现不佳。为此，我们提出了一种计算和内存高效的检索框架（CMER）。为了降低训练内存消耗，我们设计了Focus-Adapter模块，采用侧分支结构，其焦点层有效抑制了背景像素对小目标的干扰。同时，我们利用遥感场景类别作为元数据，设计了一种简洁的增强技术，通过土地覆盖类别的先验知识缩小搜索空间。此外，我们提出了负样本回收策略，使负样本池与mini-batch大小解耦，在不增加编码器的情况下提升了泛化性能。我们在公开数据集上进行了定量和定性实验，并结合多种先进方法扩展了基准测试，验证了CMER的竞争力。与最新方法相比，CMER在RSITMD上的检索性能提升了2%--5%，同时减少了49%的内存消耗，训练数据吞吐量提高了1.4倍。CMER的代码和数据集将在https://github.com/ZhangWeihang99/CMER开源。

> Remote sensing text--image retrieval (RSTIR) aims to retrieve the matched remote sensing (RS) images from the database according to the descriptive text. Recently, the rapid development of large visual-language pre-training models provides new insights for RSTIR. Nevertheless, as the complexity of models grows in RSTIR, the previous studies suffer from suboptimal resource efficiency during transfer learning. To address this issue, we propose a computation and memory-efficient retrieval (CMER) framework for RSTIR. To reduce the training memory consumption, we propose the Focus-Adapter module, which adopts a side branch structure. Its focus layer suppresses the interference of background pixels for small targets. Simultaneously, to enhance data efficacy, we regard the RS scene category as the metadata and design a concise augmentation technique. The scene label augmentation leverages the prior knowledge from land cover categories and shrinks the search space. We propose the negative sample recycling strategy to make the negative sample pool decoupled from the mini-batch size. It improves the generalization performance without introducing additional encoders. We have conducted quantitative and qualitative experiments on public datasets and expanded the benchmark with some advanced approaches, which demonstrates the competitiveness of the proposed CMER. Compared with the recent advanced methods, the overall retrieval performance of CMER is 2%--5% higher on RSITMD. Moreover, our proposed method reduces memory consumption by 49% and has a 1.4x data throughput during training. The code of the CMER and the dataset will be released at https://github.com/ZhangWeihang99/CMER.

[Arxiv](https://arxiv.org/abs/2501.10638)