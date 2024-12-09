# HOT3D：基于以自我为中心的多视图视频实现 3D 中的手和物体跟踪

发布时间：2024年11月28日

`其他` `计算机视觉` `3D 追踪`

> HOT3D: Hand and Object Tracking in 3D from Egocentric Multi-View Videos

# 摘要

> 我们推出了 HOT3D，这是一个可公开获取的用于 3D 以自我为中心的手和物体追踪的数据集。此数据集提供了超过 833 分钟（逾 370 万张图像）的多视图 RGB/单色图像流，展现了 19 位受试者与 33 种不同的刚性物体的互动，还有诸如眼睛注视或场景点云之类的多模态信号，以及全面的真实标注，涵盖物体、手和相机的 3D 姿态，以及手和物体的 3D 模型。除了简单的拿起/观察/放下动作，HOT3D 还包含类似厨房、办公室和客厅环境中的典型动作场景。该数据集由 Meta 的两款头戴式设备记录：Project Aria，一款轻量级 AR/AI 眼镜的研究原型，以及 Quest 3，一款销量达数百万的生产型 VR 头显。真实姿态通过专业的运动捕捉系统获取，该系统使用附着在手上和物体上的小光学标记。手的标注以 UmeTrack 和 MANO 格式提供，物体由内部扫描仪获取的带有 PBR 材料的 3D 网格来表示。在我们的实验中，我们证明了多视图以自我为中心的数据对于三个热门任务的有效性：3D 手跟踪、6DoF 物体姿态估计和未知手持物体的 3D 提升。通过 HOT3D 得以独特实现基准测试的评估多视图方法，明显优于其单视图同类方法。

> We introduce HOT3D, a publicly available dataset for egocentric hand and object tracking in 3D. The dataset offers over 833 minutes (more than 3.7M images) of multi-view RGB/monochrome image streams showing 19 subjects interacting with 33 diverse rigid objects, multi-modal signals such as eye gaze or scene point clouds, as well as comprehensive ground-truth annotations including 3D poses of objects, hands, and cameras, and 3D models of hands and objects. In addition to simple pick-up/observe/put-down actions, HOT3D contains scenarios resembling typical actions in a kitchen, office, and living room environment. The dataset is recorded by two head-mounted devices from Meta: Project Aria, a research prototype of light-weight AR/AI glasses, and Quest 3, a production VR headset sold in millions of units. Ground-truth poses were obtained by a professional motion-capture system using small optical markers attached to hands and objects. Hand annotations are provided in the UmeTrack and MANO formats and objects are represented by 3D meshes with PBR materials obtained by an in-house scanner. In our experiments, we demonstrate the effectiveness of multi-view egocentric data for three popular tasks: 3D hand tracking, 6DoF object pose estimation, and 3D lifting of unknown in-hand objects. The evaluated multi-view methods, whose benchmarking is uniquely enabled by HOT3D, significantly outperform their single-view counterparts.

[Arxiv](https://arxiv.org/abs/2411.19167)