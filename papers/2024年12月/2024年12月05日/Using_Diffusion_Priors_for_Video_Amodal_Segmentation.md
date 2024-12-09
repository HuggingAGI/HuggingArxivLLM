# 利用扩散先验实现视频的非模态分割

发布时间：2024年12月05日

`其他` `计算机视觉` `视频处理`

> Using Diffusion Priors for Video Amodal Segmentation

# 摘要

> 人类的客体永久性是个关键线索，能助我们理解物体的持久性，哪怕它们在场景里完全被遮挡。当下物体分割的方法未考虑世界的这种非模态特性，只适用于可见或模态物体的分割。非模态方法寥寥无几；单图像分割方法难以应对高水平遮挡，用时间信息推断效果更佳，多帧方法仅专注于分割刚性物体。为此，我们提议把视频非模态分割设定为条件生成任务来解决，借助视频生成模型的基础知识。我们的方法简单，重新利用这些模型，以物体的一系列模态掩码帧和上下文伪深度图为条件，去了解哪个物体边界可能被遮挡，进而拓展以想象出物体的完整范围。随后是内容完成阶段，能够修复物体的遮挡区域。我们在四个数据集上拿我们的方法与众多先进方法做基准测试，结果显示物体遮挡区域的非模态分割有高达 13%的显著提升。

> Object permanence in humans is a fundamental cue that helps in understanding persistence of objects, even when they are fully occluded in the scene. Present day methods in object segmentation do not account for this amodal nature of the world, and only work for segmentation of visible or modal objects. Few amodal methods exist; single-image segmentation methods cannot handle high-levels of occlusions which are better inferred using temporal information, and multi-frame methods have focused solely on segmenting rigid objects. To this end, we propose to tackle video amodal segmentation by formulating it as a conditional generation task, capitalizing on the foundational knowledge in video generative models. Our method is simple; we repurpose these models to condition on a sequence of modal mask frames of an object along with contextual pseudo-depth maps, to learn which object boundary may be occluded and therefore, extended to hallucinate the complete extent of an object. This is followed by a content completion stage which is able to inpaint the occluded regions of an object. We benchmark our approach alongside a wide array of state-of-the-art methods on four datasets and show a dramatic improvement of upto 13% for amodal segmentation in an object's occluded region.

[Arxiv](https://arxiv.org/abs/2412.04623)