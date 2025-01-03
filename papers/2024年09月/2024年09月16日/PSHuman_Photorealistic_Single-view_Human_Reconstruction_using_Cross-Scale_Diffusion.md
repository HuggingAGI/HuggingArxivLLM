# PSHuman: 基于跨尺度扩散的逼真单视角人体重建

发布时间：2024年09月16日

`其他

理由：这篇论文主要讨论的是3D人体建模和重建技术，特别是利用多视图扩散模型进行人体网格重建。虽然涉及到一些生成模型和条件化技术，但其核心内容与Agent、RAG、LLM应用或LLM理论无关。因此，将其分类为“其他”更为合适。` `计算机视觉` `3D建模`

> PSHuman: Photorealistic Single-view Human Reconstruction using Cross-Scale Diffusion

# 摘要

> # 摘要
逼真且精细的3D人体建模在众多应用中至关重要，近年来取得了显著进展。然而，由于问题的病态性以及复杂的服装拓扑和自遮挡，单目RGB图像的全身重建仍面临挑战。本文提出PSHuman框架，利用多视图扩散模型的先验显式重建人体网格。研究发现，直接在单视图人体图像上应用多视图扩散会导致严重的几何失真，尤其是面部区域。为此，我们提出跨尺度扩散方法，建模全局全身形状与局部面部特征的联合概率分布，实现无几何失真的细节保留与身份一致的新视图生成。此外，为增强不同姿态下的跨视图身体形状一致性，我们在SMPL-X等参数模型上对生成模型进行条件化，利用身体先验避免生成与人体解剖结构不符的不自然视图。基于生成的多视图法线和彩色图像，我们提出基于SMPLX的显式人体雕刻，高效恢复逼真的纹理人体网格。在CAPE和THuman2.1数据集上的大量实验与定量评估表明，PSHuman在几何细节、纹理保真度和泛化能力上表现卓越。

> 
Abstract:Detailed and photorealistic 3D human modeling is essential for various applications and has seen tremendous progress. However, full-body reconstruction from a monocular RGB image remains challenging due to the ill-posed nature of the problem and sophisticated clothing topology with self-occlusions. In this paper, we propose PSHuman, a novel framework that explicitly reconstructs human meshes utilizing priors from the multiview diffusion model. It is found that directly applying multiview diffusion on single-view human images leads to severe geometric distortions, especially on generated faces. To address it, we propose a cross-scale diffusion that models the joint probability distribution of global full-body shape and local facial characteristics, enabling detailed and identity-preserved novel-view generation without any geometric distortion. Moreover, to enhance cross-view body shape consistency of varied human poses, we condition the generative model on parametric models like SMPL-X, which provide body priors and prevent unnatural views inconsistent with human anatomy. Leveraging the generated multi-view normal and color images, we present SMPLX-initialized explicit human carving to recover realistic textured human meshes efficiently. Extensive experimental results and quantitative evaluations on CAPE and THuman2.1 datasets demonstrate PSHumans superiority in geometry details, texture fidelity, and generalization capability.
    

[Arxiv](https://arxiv.org/pdf/2409.10141)