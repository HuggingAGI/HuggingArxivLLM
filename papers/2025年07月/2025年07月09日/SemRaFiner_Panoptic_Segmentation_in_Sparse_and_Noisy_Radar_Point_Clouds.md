# SemRaFiner：稀疏噪声雷达点云的全景分割

发布时间：2025年07月09日

`其他` `自动驾驶` `雷达技术`

> SemRaFiner: Panoptic Segmentation in Sparse and Noisy Radar Point Clouds

# 摘要

> 语义场景理解，包括对移动物体的感知和分类，是实现自动驾驶安全驾驶行为的关键。摄像头和LiDAR是常用的传感器，但它们在恶劣天气下表现受限，且通常不提供运动信息。雷达传感器通过测量多普勒速度克服了这些限制，直接提供移动物体信息，但其测量数据较为稀疏且噪声较大。本文专注于解决稀疏雷达点云的全景分割问题，以提升场景理解能力。我们的方法SemRaFiner针对稀疏雷达点云密度变化进行了优化，并改进了特征提取以提升精度。此外，我们提出了一种优化的训练流程，通过引入专门的数据增强来改进实例分配。实验结果表明，我们的方法在基于雷达的全景分割任务中优于现有最优方法。

> Semantic scene understanding, including the perception and classification of moving agents, is essential to enabling safe and robust driving behaviours of autonomous vehicles. Cameras and LiDARs are commonly used for semantic scene understanding. However, both sensor modalities face limitations in adverse weather and usually do not provide motion information. Radar sensors overcome these limitations and directly offer information about moving agents by measuring the Doppler velocity, but the measurements are comparably sparse and noisy. In this paper, we address the problem of panoptic segmentation in sparse radar point clouds to enhance scene understanding. Our approach, called SemRaFiner, accounts for changing density in sparse radar point clouds and optimizes the feature extraction to improve accuracy. Furthermore, we propose an optimized training procedure to refine instance assignments by incorporating a dedicated data augmentation. Our experiments suggest that our approach outperforms state-of-the-art methods for radar-based panoptic segmentation.

[Arxiv](https://arxiv.org/abs/2507.06906)