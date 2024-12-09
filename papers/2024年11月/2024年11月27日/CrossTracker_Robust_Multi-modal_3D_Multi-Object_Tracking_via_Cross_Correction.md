# CrossTracker：借助交叉校正达成稳健的多模态 3D 多目标跟踪

发布时间：2024年11月27日

`其他` `自动驾驶` `多目标跟踪`

> CrossTracker: Robust Multi-modal 3D Multi-Object Tracking via Cross Correction

# 摘要

> 相机与激光雷达检测的融合为解决 3D 多目标跟踪（MOT）中的跟踪失败问题带来了极具潜力的方案。然而，现有的方法大多借助相机检测来纠正由潜在激光雷达检测问题引发的跟踪失败，却忽视了利用激光雷达数据优化相机检测所能带来的相互益处。这种局限性源自它们类似于单阶段目标检测器的单阶段架构，缺少专门用于充分挖掘互补多模态信息的轨迹优化模块。为此，我们推出了 CrossTracker，这是一种用于在线多模态 3D MOT 的全新两阶段模式。CrossTracker 以粗到精的方式运作，先产生粗轨迹，然后通过独立的优化过程对其进行细化。具体来说，CrossTracker 涵盖三个关键模块：i）多模态建模（M^3）模块，通过融合多模态信息（图像、点云，甚至从图像中提取的平面几何），为后续的轨迹生成提供有力的度量标准。ii）粗轨迹生成（C-TG）模块，生成初始的粗双流轨迹。iii）轨迹细化（TR）模块，通过相机和激光雷达流之间的交叉校正来优化粗轨迹。综合实验显示，我们的 CrossTracker 比十八个竞品表现更优，凸显了其在利用相机和激光雷达传感器的协同优势实现稳健多模态 3D MOT 方面的有效性。

> The fusion of camera- and LiDAR-based detections offers a promising solution to mitigate tracking failures in 3D multi-object tracking (MOT). However, existing methods predominantly exploit camera detections to correct tracking failures caused by potential LiDAR detection problems, neglecting the reciprocal benefit of refining camera detections using LiDAR data. This limitation is rooted in their single-stage architecture, akin to single-stage object detectors, lacking a dedicated trajectory refinement module to fully exploit the complementary multi-modal information. To this end, we introduce CrossTracker, a novel two-stage paradigm for online multi-modal 3D MOT. CrossTracker operates in a coarse-to-fine manner, initially generating coarse trajectories and subsequently refining them through an independent refinement process. Specifically, CrossTracker incorporates three essential modules: i) a multi-modal modeling (M^3) module that, by fusing multi-modal information (images, point clouds, and even plane geometry extracted from images), provides a robust metric for subsequent trajectory generation. ii) a coarse trajectory generation (C-TG) module that generates initial coarse dual-stream trajectories, and iii) a trajectory refinement (TR) module that refines coarse trajectories through cross correction between camera and LiDAR streams. Comprehensive experiments demonstrate the superior performance of our CrossTracker over its eighteen competitors, underscoring its effectiveness in harnessing the synergistic benefits of camera and LiDAR sensors for robust multi-modal 3D MOT.

[Arxiv](https://arxiv.org/abs/2411.18850)