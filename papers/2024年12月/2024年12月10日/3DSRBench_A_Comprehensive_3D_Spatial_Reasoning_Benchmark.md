# 3DSRBench：一个综合性的 3D 空间推理基准

发布时间：2024年12月10日

`其他` `机器人技术` `AR/VR`

> 3DSRBench: A Comprehensive 3D Spatial Reasoning Benchmark

# 摘要

> 3D 空间推理指的是分析和解读 3D 空间中物体的位置、朝向以及空间关系的能力。这让模型能够对 3D 场景有全面的理解，从而能在更广泛的领域得以应用，比如自主导航、机器人技术以及 AR/VR 等。尽管大型多模态模型（LMMs）在众多图像和视频理解任务中取得了显著成就，但其在不同自然图像上进行 3D 空间推理的能力却研究甚少。在本项工作中，我们推出了首个全面的 3D 空间推理基准——3DSRBench，其中涵盖了 12 种问题类型的 2772 个手动标注的视觉问答对。我们通过平衡数据分布并采用新颖的 FlipEval 策略，对 3D 空间推理能力展开了有力且深入的评估。为进一步探究 3D 空间推理对于相机 3D 视点的鲁棒性，我们的 3DSRBench 包含了两个子集，其中有在具有常见和不常见视点的成对图像上的 3D 空间推理问题。我们对各类开源和专有的 LMMs 进行了基准测试，揭示了它们在 3D 感知的诸如高度、朝向、位置和多对象推理等各个方面的局限性，以及在具有不常见相机视点的图像上性能的下滑。我们的 3DSRBench 为具备强大 3D 推理能力的 LMMs 的未来发展提供了宝贵的发现和见解。我们的项目页面和数据集可在 https://3dsrbench.github.io 获取。

> 3D spatial reasoning is the ability to analyze and interpret the positions, orientations, and spatial relationships of objects within the 3D space. This allows models to develop a comprehensive understanding of the 3D scene, enabling their applicability to a broader range of areas, such as autonomous navigation, robotics, and AR/VR. While large multi-modal models (LMMs) have achieved remarkable progress in a wide range of image and video understanding tasks, their capabilities to perform 3D spatial reasoning on diverse natural images are less studied. In this work we present the first comprehensive 3D spatial reasoning benchmark, 3DSRBench, with 2,772 manually annotated visual question-answer pairs across 12 question types. We conduct robust and thorough evaluation of 3D spatial reasoning capabilities by balancing the data distribution and adopting a novel FlipEval strategy. To further study the robustness of 3D spatial reasoning w.r.t. camera 3D viewpoints, our 3DSRBench includes two subsets with 3D spatial reasoning questions on paired images with common and uncommon viewpoints. We benchmark a wide range of open-sourced and proprietary LMMs, uncovering their limitations in various aspects of 3D awareness, such as height, orientation, location, and multi-object reasoning, as well as their degraded performance on images with uncommon camera viewpoints. Our 3DSRBench provide valuable findings and insights about the future development of LMMs with strong 3D reasoning capabilities. Our project page and dataset is available https://3dsrbench.github.io.

[Arxiv](https://arxiv.org/abs/2412.07825)