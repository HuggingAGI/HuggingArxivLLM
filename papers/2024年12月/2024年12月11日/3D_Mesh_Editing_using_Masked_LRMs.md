# 使用掩码 LRMs 进行 3D 网格编辑

发布时间：2024年12月11日

`其他` `3D 重建` `图形编辑`

> 3D Mesh Editing using Masked LRMs

# 摘要

> 摘要：我们依托多视图图像 3D 重建的最新成果，提出一种新颖的网格形状编辑方法。我们把形状编辑设定为一个条件重建问题，即模型必须重建输入形状，除了特定的 3D 区域，该区域的几何形状要依据条件信号生成。为此，我们训练了用于掩蔽重建的条件大型重建模型（LRM），采用从随机生成的 3D 遮挡渲染的多视图一致掩码，并以一个清晰的视点作为条件信号。在推理时，我们手动界定一个要编辑的 3D 区域，并提供来自规范视点的编辑图像来填充该区域。我们表明，仅一次前向传递，我们的方法不仅凭借与 SoTA 相当的重建能力保留了未掩蔽区域的输入几何形状，而且表现力强，能从单个图像引导完成各种网格编辑，这是以往工作难以实现的，同时比顶尖的竞争先行工作快 10 倍。

> 
Abstract:We present a novel approach to mesh shape editing, building on recent progress in 3D reconstruction from multi-view images. We formulate shape editing as a conditional reconstruction problem, where the model must reconstruct the input shape with the exception of a specified 3D region, in which the geometry should be generated from the conditional signal. To this end, we train a conditional Large Reconstruction Model (LRM) for masked reconstruction, using multi-view consistent masks rendered from a randomly generated 3D occlusion, and using one clean viewpoint as the conditional signal. During inference, we manually define a 3D region to edit and provide an edited image from a canonical viewpoint to fill in that region. We demonstrate that, in just a single forward pass, our method not only preserves the input geometry in the unmasked region through reconstruction capabilities on par with SoTA, but is also expressive enough to perform a variety of mesh edits from a single image guidance that past works struggle with, while being 10x faster than the top-performing competing prior work.
    

[Arxiv](https://arxiv.org/pdf/2412.08641)