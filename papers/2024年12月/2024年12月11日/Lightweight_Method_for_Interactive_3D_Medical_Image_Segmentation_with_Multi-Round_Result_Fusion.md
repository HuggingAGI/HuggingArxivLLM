# 一种用于交互式 3D 医学图像分割且结合多轮结果融合的轻量级方法

发布时间：2024年12月11日

`LLM应用` `医学成像` `图像分割`

> Lightweight Method for Interactive 3D Medical Image Segmentation with Multi-Round Result Fusion

# 摘要

> 在医学成像领域，常常需要对病变或器官进行精准标注。然而，3D 体图像通常包含成百上千个切片，这让标注工作极为耗时费力。近来，分割任意模型（SAM）因在交互式分割中出色的零样本泛化能力而备受瞩目。尽管研究人员已探索将 SAM 用于医学应用，比如采用 SAM 适配器或构建 3D SAM 模型，但有个关键问题仍未解决：传统的 CNN 网络在此任务中能否达成同样出色的零样本泛化？本文中，我们提出用于 3D 医学图像分割的轻量级交互网络（LIM-Net），这是一种展现了基于紧凑 CNN 模型潜力的新方法。LIM-Net 基于 2D CNN 骨干，借由用户提示生成 2D 提示掩码来开启分割。接着，该掩码通过内存模块在 3D 序列中传播。为在交互过程中优化和稳定结果，多轮结果融合（MRF）模块从多轮中选取并合并最优掩码。我们在多个数据集和模态上开展的大量实验证实了 LIM-Net 的卓越性能。和基于 SAM 的模型相比，它对未曾见过的数据有更强的泛化能力，准确性相当，且所需交互更少。值得一提的是，LIM-Net 的轻量设计在部署和推理效率方面优势显著，GPU 内存消耗低，适用于资源受限的环境。这些可喜成果表明，LIM-Net 能够作为有力的基线，与流行的 SAM 模型互为补充和对照，进一步推动有效的交互式医学图像分割。代码将在 url{https://github.com/goodtime-123/LIM-Net} 发布。

> In medical imaging, precise annotation of lesions or organs is often required. However, 3D volumetric images typically consist of hundreds or thousands of slices, making the annotation process extremely time-consuming and laborious. Recently, the Segment Anything Model (SAM) has drawn widespread attention due to its remarkable zero-shot generalization capabilities in interactive segmentation. While researchers have explored adapting SAM for medical applications, such as using SAM adapters or constructing 3D SAM models, a key question remains: Can traditional CNN networks achieve the same strong zero-shot generalization in this task? In this paper, we propose the Lightweight Interactive Network for 3D Medical Image Segmentation (LIM-Net), a novel approach demonstrating the potential of compact CNN-based models. Built upon a 2D CNN backbone, LIM-Net initiates segmentation by generating a 2D prompt mask from user hints. This mask is then propagated through the 3D sequence via the Memory Module. To refine and stabilize results during interaction, the Multi-Round Result Fusion (MRF) Module selects and merges optimal masks from multiple rounds. Our extensive experiments across multiple datasets and modalities demonstrate LIM-Net's competitive performance. It exhibits stronger generalization to unseen data compared to SAM-based models, with competitive accuracy while requiring fewer interactions. Notably, LIM-Net's lightweight design offers significant advantages in deployment and inference efficiency, with low GPU memory consumption suitable for resource-constrained environments. These promising results demonstrate LIM-Net can serve as a strong baseline, complementing and contrasting with popular SAM models to further boost effective interactive medical image segmentation. The code will be released at url{https://github.com/goodtime-123/LIM-Net}.

[Arxiv](https://arxiv.org/abs/2412.08315)