# DreamCraft3D++：利用多平面重建模型实现高效分层3D生成

发布时间：2024年10月16日

`其他

理由：这篇论文主要讨论的是3D资产生成技术，特别是DreamCraft3D++的改进和优化。虽然它涉及到一些生成模型和优化技术，但核心内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `3D建模` `内容创作`

> DreamCraft3D++: Efficient Hierarchical 3D Generation with Multi-Plane Reconstruction Model

# 摘要

> 摘要：我们推出了 DreamCraft3D++，作为 DreamCraft3D 的升级版，它能够高效生成高质量的复杂 3D 资产。DreamCraft3D++ 沿用了 DreamCraft3D 的多阶段生成流程，但用基于前馈多平面的重建模型替代了耗时的几何雕刻优化，速度提升了 1000 倍。在纹理优化方面，我们引入了一种无需训练的 IP-Adapter 模块，通过增强的多视图图像提升纹理和几何一致性，速度比 DreamCraft3D 的 DreamBooth 微调快 4 倍。实验表明，DreamCraft3D++ 能够生成具有复杂几何结构和逼真 360° 纹理的创意 3D 资产，在质量和速度上均领先于现有图像到 3D 方法。完整实现将开源，为 3D 内容创作带来更多可能性。

> 
Abstract:We introduce DreamCraft3D++, an extension of DreamCraft3D that enables efficient high-quality generation of complex 3D assets. DreamCraft3D++ inherits the multi-stage generation process of DreamCraft3D, but replaces the time-consuming geometry sculpting optimization with a feed-forward multi-plane based reconstruction model, speeding up the process by 1000x. For texture refinement, we propose a training-free IP-Adapter module that is conditioned on the enhanced multi-view images to enhance texture and geometry consistency, providing a 4x faster alternative to DreamCraft3D's DreamBooth fine-tuning. Experiments on diverse datasets demonstrate DreamCraft3D++'s ability to generate creative 3D assets with intricate geometry and realistic 360° textures, outperforming state-of-the-art image-to-3D methods in quality and speed. The full implementation will be open-sourced to enable new possibilities in 3D content creation.
    

[Arxiv](https://arxiv.org/pdf/2410.12928)