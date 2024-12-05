# IRisPath：凭借强大的红外-RGB 融合来强化越野导航，提升白天和夜间的通行能力

发布时间：2024年12月04日

`其他` `自动驾驶` `越野导航`

> IRisPath: Enhancing Off-Road Navigation with Robust IR-RGB Fusion for Improved Day and Night Traversability

# 摘要

> 自主越野导航在农业、建筑、搜索救援及国防等领域必不可少。传统的公路自动驾驶方法在动态地形中表现不佳，致使越野时车辆控制效果差。近来的深度学习模型借助感知传感器和动觉反馈来实现此类地形上的导航。然而，该方法存在域外不确定性。诸如天气变化和一天中的时段等因素会影响模型性能。我们提出了一个名为 FuseIsPath 的多模态融合网络，它能够利用 LWIR 和 RGB 图像增强应对动态天气和光照条件的能力。为助力该领域的进一步研究，我们还开源了一个包含 LWIR 和 RGB 图像以及可通行性伪标签的日夜数据集。为了共同配准这两种图像，我们开发了一种新的 LWIR、LiDAR 和 RGB 相机无目标外在校准方法，平移精度达 1.7 厘米，旋转精度达 0.827 度。

> Autonomous off-road navigation is required for applications in agriculture, construction, search and rescue and defence. Traditional on-road autonomous methods struggle with dynamic terrains, leading to poor vehicle control on off-road. Recent deep-learning models have used perception sensors along with kinesthetic feedback for navigation on such terrains. However, this approach has out-of-domain uncertainty. Factors like change in weather and time of day impacts the performance of the model. We propose a multi modal fusion network FuseIsPath capable of using LWIR and RGB images to provide robustness against dynamic weather and light conditions. To aid further works in this domain, we also open-source a day-night dataset with LWIR and RGB images along with pseudo-labels for traversability. In order to co-register the two images we developed a novel method for targetless extrinsic calibration of LWIR, LiDAR and RGB cameras with translation accuracy of 1.7cm and rotation accuracy of 0.827degree.

[Arxiv](https://arxiv.org/abs/2412.03173)