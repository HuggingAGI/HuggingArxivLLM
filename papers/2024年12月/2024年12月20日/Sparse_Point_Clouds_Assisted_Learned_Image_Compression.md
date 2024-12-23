# 稀疏点云辅助的图像学习压缩

发布时间：2024年12月20日

`其他` `自动驾驶` `图像压缩`

> Sparse Point Clouds Assisted Learned Image Compression

# 摘要

> 在自动驾驶领域，存在着各式各样的传感器数据类型，每种都代表着同一场景的不同模态。所以，借助其他传感器的数据来助力图像压缩是行得通的。不过，很少有技术去挖掘利用模态间的相关性来提升图像压缩性能的潜在益处。本文受近期学习型图像压缩的成功所启发，提出了一个新框架，利用稀疏点云在自动驾驶场景中辅助学习型图像压缩。我们先把 3D 稀疏点云投影到 2D 平面，形成稀疏深度图。凭借这个深度图，接着预测相机图像。随后，用这些预测图像提取多尺度结构特征。再把这些特征作为额外信息融入学习型图像压缩流程，以提升压缩性能。我们提出的框架与各类主流学习型图像压缩模型兼容，并且通过不同的现有图像压缩方法验证了我们的方法。实验结果显示，把点云辅助纳入压缩流程能持续提升性能。

> In the field of autonomous driving, a variety of sensor data types exist, each representing different modalities of the same scene. Therefore, it is feasible to utilize data from other sensors to facilitate image compression. However, few techniques have explored the potential benefits of utilizing inter-modality correlations to enhance the image compression performance. In this paper, motivated by the recent success of learned image compression, we propose a new framework that uses sparse point clouds to assist in learned image compression in the autonomous driving scenario. We first project the 3D sparse point cloud onto a 2D plane, resulting in a sparse depth map. Utilizing this depth map, we proceed to predict camera images. Subsequently, we use these predicted images to extract multi-scale structural features. These features are then incorporated into learned image compression pipeline as additional information to improve the compression performance. Our proposed framework is compatible with various mainstream learned image compression models, and we validate our approach using different existing image compression methods. The experimental results show that incorporating point cloud assistance into the compression pipeline consistently enhances the performance.

[Arxiv](https://arxiv.org/abs/2412.15752)