# 基于视觉与文本特征的多维度实验研究视觉语言模型

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Examining Vision Language Models through Multi-dimensional Experiments with Vision and Text Features

# 摘要

> 近期对视觉语言模型（VLMs）的研究发现，这类模型在回答图像视觉属性相关问题时，往往依赖训练中习得的固有偏差。而当问题高度具体、需要聚焦图像特定区域时，这些偏差会进一步放大。比如，若让VLMs数一面修改过的美国国旗（比如星星数量超过50颗）上的星星，模型常会无视图像中的实际星星数量，给出错误答案。基于这一发现，我们构建了多维度分析框架，系统探究输入数据（包括图像及配套提示）的哪些特征会引发此类性能差异。借助开源VLMs，我们进一步分析了注意力值随输入参数（如图像尺寸、物体数量、背景颜色及提示特异性）变化的波动规律。本研究旨在揭示视觉语言模型的行为变化规律，并探索刻画这些变化的方法。研究结果显示，尤其值得注意的是，图像特征或提示特异性的微小调整，就可能大幅改变VLMs的回答逻辑，进而显著影响其整体性能。

> Recent research on Vision Language Models (VLMs) suggests that they rely on inherent biases learned during training to respond to questions about visual properties of an image. These biases are exacerbated when VLMs are asked highly specific questions that require focusing on specific areas of the image. For example, a VLM tasked with counting stars on a modified American flag (e.g., with more than 50 stars) will often disregard the visual evidence and fail to answer accurately. We build upon this research and develop a multi-dimensional examination framework to systematically determine which characteristics of the input data, including both the image and the accompanying prompt, lead to such differences in performance. Using open-source VLMs, we further examine how attention values fluctuate with varying input parameters (e.g., image size, number of objects in the image, background color, prompt specificity). This research aims to learn how the behavior of vision language models changes and to explore methods for characterizing such changes. Our results suggest, among other things, that even minor modifications in image characteristics and prompt specificity can lead to large changes in how a VLM formulates its answer and, subsequently, its overall performance.

[Arxiv](https://arxiv.org/abs/2509.08266)