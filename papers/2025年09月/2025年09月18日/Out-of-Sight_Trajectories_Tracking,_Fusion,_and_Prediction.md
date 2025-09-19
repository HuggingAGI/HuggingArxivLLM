# 隐匿轨迹：跟踪、融合与预测

发布时间：2025年09月18日

`其他` `交通运输`

> Out-of-Sight Trajectories: Tracking, Fusion, and Prediction

# 摘要

> 轨迹预测是计算机视觉与自主系统领域的关键任务，在自动驾驶、机器人技术、监控及虚拟现实中均扮演重要角色。现有方法通常依赖完整且无噪声的观测数据，却忽视了视线外物体带来的挑战，以及传感器数据中因相机覆盖范围有限、遮挡、缺乏去噪轨迹真实标签而产生的固有噪声。这些局限不仅带来安全风险，还会影响现实场景中预测的可靠性。在这项扩展研究中，我们提出了视线外轨迹（OST）的新进展——这是一项利用含噪声传感器数据预测视线外物体无噪声视觉轨迹的创新任务。基于前期研究，我们扩展了视线外轨迹预测（OOSTraj）的应用范围，将行人与车辆纳入研究对象，使其在自动驾驶、机器人技术、监控及虚拟现实中具备更广泛的适用性。我们改进的视觉-定位去噪模块通过相机标定建立视觉-定位映射，既解决了视觉参考缺失问题，又能以无监督方式有效去除传感器数据中的噪声。在Vi-Fi与JRDB数据集上的大量实验表明，我们的方法在轨迹去噪和预测任务上均达到最先进性能，显著优于现有基准。此外，我们还对比了卡尔曼滤波等传统去噪方法，并将近期轨迹预测模型适配到该任务中，构建了全面的基准体系。本研究首次提出将视觉-定位投影整合用于视线外智能体含噪声传感器轨迹的去噪，为该领域的未来发展奠定了基础。相关代码及预处理数据集可访问github.com/Hai-chao-Zhang/OST获取。

> Trajectory prediction is a critical task in computer vision and autonomous systems, playing a key role in autonomous driving, robotics, surveillance, and virtual reality. Existing methods often rely on complete and noise-free observational data, overlooking the challenges associated with out-of-sight objects and the inherent noise in sensor data caused by limited camera coverage, obstructions, and the absence of ground truth for denoised trajectories. These limitations pose safety risks and hinder reliable prediction in real-world scenarios. In this extended work, we present advancements in Out-of-Sight Trajectory (OST), a novel task that predicts the noise-free visual trajectories of out-of-sight objects using noisy sensor data. Building on our previous research, we broaden the scope of Out-of-Sight Trajectory Prediction (OOSTraj) to include pedestrians and vehicles, extending its applicability to autonomous driving, robotics, surveillance, and virtual reality. Our enhanced Vision-Positioning Denoising Module leverages camera calibration to establish a vision-positioning mapping, addressing the lack of visual references, while effectively denoising noisy sensor data in an unsupervised manner. Through extensive evaluations on the Vi-Fi and JRDB datasets, our approach achieves state-of-the-art performance in both trajectory denoising and prediction, significantly surpassing previous baselines. Additionally, we introduce comparisons with traditional denoising methods, such as Kalman filtering, and adapt recent trajectory prediction models to our task, providing a comprehensive benchmark. This work represents the first initiative to integrate vision-positioning projection for denoising noisy sensor trajectories of out-of-sight agents, paving the way for future advances. The code and preprocessed datasets are available at github.com/Hai-chao-Zhang/OST

[Arxiv](https://arxiv.org/abs/2509.15219)