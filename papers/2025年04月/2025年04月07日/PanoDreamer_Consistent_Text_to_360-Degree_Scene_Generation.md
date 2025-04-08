# PanoDreamer：从文本到360度场景的一致性生成

发布时间：2025年04月07日

`LLM应用` `虚拟现实`

> PanoDreamer: Consistent Text to 360-Degree Scene Generation

# 摘要

> 从文本描述、参考图像或两者结合中自动生成完整的3D场景，在虚拟现实和游戏等领域有广泛应用。然而，现有方法常生成低质量纹理和不一致的3D结构，尤其在显著超出参考图像视野范围时问题更突出。为解决这些挑战，我们提出了PanoDreamer——一个全新的3D场景生成框架，支持灵活的文本和图像控制。PanoDreamer采用大型语言模型和变形-优化流水线，先生成初始图像集合，再合成360度全景图，并将其提升为3D点云。随后，通过多视角图像生成和点云扩展细化，最终利用3D高斯散射生成高质量、几何一致的3D场景，可从任意视角渲染。实验结果证明了PanoDreamer的卓越效果。

> Automatically generating a complete 3D scene from a text description, a reference image, or both has significant applications in fields like virtual reality and gaming. However, current methods often generate low-quality textures and inconsistent 3D structures. This is especially true when extrapolating significantly beyond the field of view of the reference image. To address these challenges, we propose PanoDreamer, a novel framework for consistent, 3D scene generation with flexible text and image control. Our approach employs a large language model and a warp-refine pipeline, first generating an initial set of images and then compositing them into a 360-degree panorama. This panorama is then lifted into 3D to form an initial point cloud. We then use several approaches to generate additional images, from different viewpoints, that are consistent with the initial point cloud and expand/refine the initial point cloud. Given the resulting set of images, we utilize 3D Gaussian Splatting to create the final 3D scene, which can then be rendered from different viewpoints. Experiments demonstrate the effectiveness of PanoDreamer in generating high-quality, geometrically consistent 3D scenes.

[Arxiv](https://arxiv.org/abs/2504.05152)