# CAD-Unet：一种用于对 CT 图像中的 COVID-19 肺部感染进行精确分割的胶囊网络增强型 Unet 架构

发布时间：2024年12月09日

`其他` `新冠疫情`

> CAD-Unet: A Capsule Network-Enhanced Unet Architecture for Accurate Segmentation of COVID-19 Lung Infections from CT Images

# 摘要

> 自 2019 年新冠疫情爆发以来，医学成像已成为诊断新冠肺炎的主要手段。在临床中，通过计算机断层扫描图像对肺部感染进行分割，能够迅速且精准地对新冠病情进行量化和诊断。然而，对肺部新冠感染的分割极具挑战，主要原因在于磨玻璃影呈现的边界模糊且对比度有限。此外，浸润物、肺组织和肺壁之间的相似性易混淆，进一步使分割任务变得复杂。为应对这些难题，本文推出了一种全新的深度网络架构，名为 CAD-Unet，用于分割新冠肺部感染。在此架构中，胶囊网络被融入现有的 Unet 框架。胶囊网络是一种有别于传统卷积神经网络的新型网络架构，其利用向量在胶囊间传递信息，有助于提取复杂的病变空间信息。另外，我们设计了胶囊编码器路径，并在 unet 编码器与胶囊编码器之间建立了耦合路径。这种设计充分发挥了两种网络结构的互补优势，实现了高效的信息融合。 最后，在四个公开可用的数据集上开展了广泛实验，涵盖二值分割任务和多类分割任务。实验结果表明所提模型具有出色的分割性能。代码已发布于：https://github.com/AmanoTooko-jie/CAD-Unet 。

> Since the outbreak of the COVID-19 pandemic in 2019, medical imaging has emerged as a primary modality for diagnosing COVID-19 pneumonia. In clinical settings, the segmentation of lung infections from computed tomography images enables rapid and accurate quantification and diagnosis of COVID-19. Segmentation of COVID-19 infections in the lungs poses a formidable challenge, primarily due to the indistinct boundaries and limited contrast presented by ground glass opacity manifestations. Moreover, the confounding similarity between infiltrates, lung tissues, and lung walls further complicates this segmentation task. To address these challenges, this paper introduces a novel deep network architecture, called CAD-Unet, for segmenting COVID-19 lung infections. In this architecture, capsule networks are incorporated into the existing Unet framework. Capsule networks represent a novel network architecture that differs from traditional convolutional neural networks. They utilize vectors for information transfer among capsules, facilitating the extraction of intricate lesion spatial information. Additionally, we design a capsule encoder path and establish a coupling path between the unet encoder and the capsule encoder. This design maximizes the complementary advantages of both network structures while achieving efficient information fusion. \noindent Finally, extensive experiments are conducted on four publicly available datasets, encompassing binary segmentation tasks and multi-class segmentation tasks. The experimental results demonstrate the superior segmentation performance of the proposed model. The code has been released at: https://github.com/AmanoTooko-jie/CAD-Unet.

[Arxiv](https://arxiv.org/abs/2412.06314)