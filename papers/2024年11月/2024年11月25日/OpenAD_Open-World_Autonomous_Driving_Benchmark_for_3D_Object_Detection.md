# OpenAD：面向 3D 物体检测的开放世界自动驾驶基准

发布时间：2024年11月25日

`LLM应用` `自动驾驶` `对象检测`

> OpenAD: Open-World Autonomous Driving Benchmark for 3D Object Detection

# 摘要

> 开放世界自动驾驶涵盖了领域泛化和开放词汇。领域泛化指的是自动驾驶系统在不同场景和传感器参数配置中的能力。开放词汇指的是能够识别训练时未碰到的各类语义类别。在本文中，我们推出了 OpenAD，这是首个针对 3D 对象检测的真实世界开放世界自动驾驶基准。OpenAD 构建于一个与多模态大型语言模型（MLLM）相结合的角落案例发现与标注流水线之上。所提出的流水线以统一格式为五个拥有 2000 个场景的自动驾驶感知数据集标注角落案例对象。另外，我们设计了评估方法，对各种 2D 和 3D 开放世界及专业模型进行了评估。而且，我们提出了一个以视觉为核心的 3D 开放世界对象检测基线，并进一步引入了一种通过融合通用和专业模型的集成方法，来解决 OpenAD 基准中现有开放世界方法精度较低的问题。注释、工具包代码以及所有评估代码都将予以发布。

> Open-world autonomous driving encompasses domain generalization and open-vocabulary. Domain generalization refers to the capabilities of autonomous driving systems across different scenarios and sensor parameter configurations. Open vocabulary pertains to the ability to recognize various semantic categories not encountered during training. In this paper, we introduce OpenAD, the first real-world open-world autonomous driving benchmark for 3D object detection. OpenAD is built on a corner case discovery and annotation pipeline integrating with a multimodal large language model (MLLM). The proposed pipeline annotates corner case objects in a unified format for five autonomous driving perception datasets with 2000 scenarios. In addition, we devise evaluation methodologies and evaluate various 2D and 3D open-world and specialized models. Moreover, we propose a vision-centric 3D open-world object detection baseline and further introduce an ensemble method by fusing general and specialized models to address the issue of lower precision in existing open-world methods for the OpenAD benchmark. Annotations, toolkit code, and all evaluation codes will be released.

[Arxiv](https://arxiv.org/abs/2411.17761)