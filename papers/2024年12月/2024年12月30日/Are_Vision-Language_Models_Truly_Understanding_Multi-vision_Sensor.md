# 视觉语言模型是否真正理解多视觉传感器？

发布时间：2024年12月30日

`LLM应用` `计算机视觉` `多视觉传感器`

> Are Vision-Language Models Truly Understanding Multi-vision Sensor?

# 摘要

> 大规模视觉语言模型（VLMs）通过将视觉输入与文本对齐实现了进步，大幅提升了计算机视觉任务的表现。而且，要让 VLMs 在现实应用中有效发挥作用，理解诸如热、深度和 X 射线等多样的多视觉传感器数据至关重要。但我们发现，当下的 VLMs 在处理多视觉传感器图像时，对传感器信息缺乏深度理解，忽略了每个传感器的独特物理属性。这一局限限制了它们解读和回应需要多视觉传感器推理的复杂问题的能力。为此，我们提出了新颖的多视觉传感器感知与推理（MS-PR）基准，用于评估 VLMs 在传感器特定推理方面的能力。另外，我们引入了多样负属性（DNA）优化，让 VLMs 能够针对多视觉传感器任务进行深度推理，助力填补图像与传感器数据之间的核心信息鸿沟。大量实验结果证实，所提出的 DNA 方法能显著增强 VLMs 的多视觉传感器推理能力。

> Large-scale Vision-Language Models (VLMs) have advanced by aligning vision inputs with text, significantly improving performance in computer vision tasks. Moreover, for VLMs to be effectively utilized in real-world applications, an understanding of diverse multi-vision sensor data, such as thermal, depth, and X-ray information, is essential. However, we find that current VLMs process multi-vision sensor images without deep understanding of sensor information, disregarding each sensor's unique physical properties. This limitation restricts their capacity to interpret and respond to complex questions requiring multi-vision sensor reasoning. To address this, we propose a novel Multi-vision Sensor Perception and Reasoning (MS-PR) benchmark, assessing VLMs on their capacity for sensor-specific reasoning. Moreover, we introduce Diverse Negative Attributes (DNA) optimization to enable VLMs to perform deep reasoning on multi-vision sensor tasks, helping to bridge the core information gap between images and sensor data. Extensive experimental results validate that the proposed DNA method can significantly improve the multi-vision sensor reasoning for VLMs.

[Arxiv](https://arxiv.org/abs/2412.20750)