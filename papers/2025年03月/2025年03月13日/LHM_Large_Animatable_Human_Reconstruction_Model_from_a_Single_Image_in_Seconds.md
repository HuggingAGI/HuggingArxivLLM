# LHM：仅需一张图像，数秒内完成大型可动画化人体模型重建

发布时间：2025年03月13日

`其他` `计算机图形学`

> LHM: Large Animatable Human Reconstruction Model from a Single Image in Seconds

# 摘要

> 从单张图像重建可动画化的3D人体面临几何、外观和变形解耦的模糊性挑战。现有3D人体重建方法多聚焦于静态建模，且依赖合成3D扫描的训练限制了其泛化能力。基于优化的视频方法虽能实现高保真重建，但需要受控捕捉环境和高计算量的优化流程。

受到大型重建模型在静态建模中的启发，我们提出LHM（大型可动画化人体重建模型），通过一次前馈传递生成3D高斯体素化的高保真角色。模型采用多模态Transformer架构，利用注意力机制有效编码人体位置与图像特征，细致保留服装几何与纹理。为提升面部身份保留与细节恢复，我们设计了头部特征金字塔编码方案，聚合多尺度头部特征。

实验表明，LHM能在几秒内生成无需后期处理的高保真角色，面部与手部效果尤为突出，在重建精度与泛化能力上均超越现有方法。

> Animatable 3D human reconstruction from a single image is a challenging problem due to the ambiguity in decoupling geometry, appearance, and deformation. Recent advances in 3D human reconstruction mainly focus on static human modeling, and the reliance of using synthetic 3D scans for training limits their generalization ability. Conversely, optimization-based video methods achieve higher fidelity but demand controlled capture conditions and computationally intensive refinement processes. Motivated by the emergence of large reconstruction models for efficient static reconstruction, we propose LHM (Large Animatable Human Reconstruction Model) to infer high-fidelity avatars represented as 3D Gaussian splatting in a feed-forward pass. Our model leverages a multimodal transformer architecture to effectively encode the human body positional features and image features with attention mechanism, enabling detailed preservation of clothing geometry and texture. To further boost the face identity preservation and fine detail recovery, we propose a head feature pyramid encoding scheme to aggregate multi-scale features of the head regions. Extensive experiments demonstrate that our LHM generates plausible animatable human in seconds without post-processing for face and hands, outperforming existing methods in both reconstruction accuracy and generalization ability.

[Arxiv](https://arxiv.org/abs/2503.10625)