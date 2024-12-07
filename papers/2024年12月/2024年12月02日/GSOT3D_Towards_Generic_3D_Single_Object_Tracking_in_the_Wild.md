# GSOT3D：致力于实现野外通用的 3D 单个对象跟踪

发布时间：2024年12月02日

`其他` `3D 跟踪` `计算机视觉`

> GSOT3D: Towards Generic 3D Single Object Tracking in the Wild

# 摘要

> 在本文中，我们推出了一个全新的基准——GSOT3D，旨在助力野外通用 3D 单目标跟踪（SOT）的发展。具体来说，GSOT3D 提供了 620 个序列，共 123K 帧，涵盖了 54 种广泛的对象类别。每个序列都具备多种模式，包含点云（PC）、RGB 图像和深度。这使得 GSOT3D 能够支持各类 3D 跟踪任务，如 PC 上的单模态 3D SOT 以及 RGB-PC 或 RGB-D 上的多模态 3D SOT，从而极大地拓展了 3D 目标跟踪的研究方向。为提供高质量的每帧 3D 标注，所有序列均经过多轮精心检查和完善的人工标注。据我们所知，GSOT3D 是专注于各种通用 3D 目标跟踪任务的最大基准。为了解现有 3D 跟踪器的表现，并为 GSOT3D 上的未来研究提供对比，我们评估了八个具有代表性的基于点云的跟踪模型。我们的评估结果显示，这些模型在 GSOT3D 上表现严重不佳，对于稳健和通用的 3D 目标跟踪，还需要付出更多努力。另外，为鼓励未来的研究，我们提出了一个简单却有效的通用 3D 跟踪器，名为 PROT3D，它通过渐进式时空网络定位目标对象，且大幅领先于所有现有的解决方案。通过发布 GSOT3D，我们期望在未来的研究和应用中推动 3D 跟踪取得进一步发展。我们的基准、模型以及评估结果将在我们的网页 https://github.com/ailovejinx/GSOT3D 上公开。

> In this paper, we present a novel benchmark, GSOT3D, that aims at facilitating development of generic 3D single object tracking (SOT) in the wild. Specifically, GSOT3D offers 620 sequences with 123K frames, and covers a wide selection of 54 object categories. Each sequence is offered with multiple modalities, including the point cloud (PC), RGB image, and depth. This allows GSOT3D to support various 3D tracking tasks, such as single-modal 3D SOT on PC and multi-modal 3D SOT on RGB-PC or RGB-D, and thus greatly broadens research directions for 3D object tracking. To provide highquality per-frame 3D annotations, all sequences are labeled manually with multiple rounds of meticulous inspection and refinement. To our best knowledge, GSOT3D is the largest benchmark dedicated to various generic 3D object tracking tasks. To understand how existing 3D trackers perform and to provide comparisons for future research on GSOT3D, we assess eight representative point cloud-based tracking models. Our evaluation results exhibit that these models heavily degrade on GSOT3D, and more efforts are required for robust and generic 3D object tracking. Besides, to encourage future research, we present a simple yet effective generic 3D tracker, named PROT3D, that localizes the target object via a progressive spatial-temporal network and outperforms all current solutions by a large margin. By releasing GSOT3D, we expect to advance further 3D tracking in future research and applications. Our benchmark and model as well as the evaluation results will be publicly released at our webpage https://github.com/ailovejinx/GSOT3D.

[Arxiv](https://arxiv.org/abs/2412.02129)