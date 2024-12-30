# CAD-GPT：借助空间推理强化的多模态大型语言模型来合成 CAD 施工顺序

发布时间：2024年12月27日

`LLM应用` `计算机辅助设计` `3D 建模`

> CAD-GPT: Synthesising CAD Construction Sequence with Spatial Reasoning-Enhanced Multimodal LLMs

# 摘要

> 计算机辅助设计（CAD）能够实现精准的 2D 和 3D 建模、进行广泛的分析与优化，极大地提升了设计流程的效率、准确性和创新性。现有的 CAD 模型创建方法依赖于潜在向量或点云，获取困难且存储成本高。多模态大型语言模型（MLLMs）的最新进展促使研究人员利用自然语言指令和图像来构建 CAD 模型。然而，这些模型在准确推断 3D 空间位置和方向上仍有不足，致使在确定构建几何图形的空间 3D 起点和挤出方向时不够精准。本研究推出了 CAD-GPT，这是一种采用空间推理增强型 MLLM 的 CAD 合成方法，以单个图像或文本描述作为输入。为实现精确的空间推理，我们的方法引入了 3D 建模空间机制。该机制借助专门的空间展开机制，将 3D 空间位置和 3D 草图平面旋转角度映射到 1D 语言特征空间，同时将 2D 草图坐标离散化为合适的平面空间，从而精确确定空间起始位置、草图方向和 2D 草图坐标平移。大量实验表明，CAD-GPT 在 CAD 模型合成方面，无论在数量上还是质量上，都始终优于现有的先进方法。

> Computer-aided design (CAD) significantly enhances the efficiency, accuracy, and innovation of design processes by enabling precise 2D and 3D modeling, extensive analysis, and optimization. Existing methods for creating CAD models rely on latent vectors or point clouds, which are difficult to obtain and costly to store. Recent advances in Multimodal Large Language Models (MLLMs) have inspired researchers to use natural language instructions and images for CAD model construction. However, these models still struggle with inferring accurate 3D spatial location and orientation, leading to inaccuracies in determining the spatial 3D starting points and extrusion directions for constructing geometries. This work introduces CAD-GPT, a CAD synthesis method with spatial reasoning-enhanced MLLM that takes either a single image or a textual description as input. To achieve precise spatial inference, our approach introduces a 3D Modeling Spatial Mechanism. This method maps 3D spatial positions and 3D sketch plane rotation angles into a 1D linguistic feature space using a specialized spatial unfolding mechanism, while discretizing 2D sketch coordinates into an appropriate planar space to enable precise determination of spatial starting position, sketch orientation, and 2D sketch coordinate translations. Extensive experiments demonstrate that CAD-GPT consistently outperforms existing state-of-the-art methods in CAD model synthesis, both quantitatively and qualitatively.

[Arxiv](https://arxiv.org/abs/2412.19663)