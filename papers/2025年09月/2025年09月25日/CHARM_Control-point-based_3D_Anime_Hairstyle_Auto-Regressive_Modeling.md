# CHARM：基于控制点的3D动漫发型自回归建模

发布时间：2025年09月25日

`其他` `媒体与娱乐`

> CHARM: Control-point-based 3D Anime Hairstyle Auto-Regressive Modeling

# 摘要

> 我们提出CHARM——一种专为动漫发型建模设计的新型参数化表示与生成框架。传统头发建模方法多采用基于发丝或体素的表示来构建真实感头发，而动漫发型则呈现出高度风格化的分段结构几何特征，这对现有技术构成了不小的挑战。现有研究常依赖密集网格建模或手工设计的样条曲线，不仅编辑效率低下，也难以支持可扩展的学习任务。CHARM创新性地提出了一种紧凑且可逆的基于控制点的参数化方法：每个发片由一系列控制点表示，而每个控制点仅需五个几何参数即可编码。这种高效精准的表示方法既能满足艺术家友好的设计需求，又可支持基于学习的生成任务。基于这一表示方法，CHARM进一步构建了自回归生成框架，能够从输入图像或点云中高效生成动漫发型。该框架将动漫发型解读为一种序列式“头发语言”，通过自回归Transformer捕捉局部几何细节与全局发型拓扑结构，从而实现高保真的动漫发型生成。为助力动漫发型生成的训练与评估，我们构建了AnimeHair数据集——一个包含37K高质量动漫发型的大规模数据集，其中包含分离的发片与处理后的网格数据。大量实验表明，CHARM在重建精度与生成质量上均达到了当前最佳水平，为动漫发型建模提供了一种兼具表现力与可扩展性的解决方案。项目页面：https://hyzcluster.github.io/charm/

> We present CHARM, a novel parametric representation and generative framework for anime hairstyle modeling. While traditional hair modeling methods focus on realistic hair using strand-based or volumetric representations, anime hairstyle exhibits highly stylized, piecewise-structured geometry that challenges existing techniques. Existing works often rely on dense mesh modeling or hand-crafted spline curves, making them inefficient for editing and unsuitable for scalable learning. CHARM introduces a compact, invertible control-point-based parameterization, where a sequence of control points represents each hair card, and each point is encoded with only five geometric parameters. This efficient and accurate representation supports both artist-friendly design and learning-based generation. Built upon this representation, CHARM introduces an autoregressive generative framework that effectively generates anime hairstyles from input images or point clouds. By interpreting anime hairstyles as a sequential "hair language", our autoregressive transformer captures both local geometry and global hairstyle topology, resulting in high-fidelity anime hairstyle creation. To facilitate both training and evaluation of anime hairstyle generation, we construct AnimeHair, a large-scale dataset of 37K high-quality anime hairstyles with separated hair cards and processed mesh data. Extensive experiments demonstrate state-of-the-art performance of CHARM in both reconstruction accuracy and generation quality, offering an expressive and scalable solution for anime hairstyle modeling. Project page: https://hyzcluster.github.io/charm/

[Arxiv](https://arxiv.org/abs/2509.21114)