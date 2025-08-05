# 基于视频的车辆监控在真实场景中的车牌、品牌和型号识别：使用自反思视觉-语言模型

发布时间：2025年08月02日

`LLM应用` `智能交通系统`

> Video-based Vehicle Surveillance in the Wild: License Plate, Make, and Model Recognition with Self Reflective Vision-Language Models

# 摘要

> # 摘要  
自动车牌识别（ALPR）和车辆品牌型号识别是智能交通系统的关键技术，支持执法、收费和事故调查等场景。将这些技术应用于手持智能手机或非静态车载摄像头拍摄的视频相比固定设备更具挑战性，面临频繁的摄像头运动、多变的视角、遮挡以及未知的道路几何结构等问题。传统ALPR解决方案依赖专用硬件和手工设计的OCR流水线，在这些复杂条件下性能往往下降。大型视觉语言模型（VLMs）的最新进展为直接从任意图像中识别文本和语义属性提供了可能。本研究评估了VLMs在使用手持智能手机和非静态车载摄像头拍摄的单目视频中进行ALPR和品牌型号识别的潜力。所提出的车牌识别流水线通过筛选清晰帧，并使用多种提示策略向VLM发送多模态提示。品牌型号识别流水线则使用修改后的提示运行相同的VLM，并可选配自我反思模块。自我反思模块通过将查询图像与来自134类数据集的参考图像进行对比，纠正不匹配。在得克萨斯大学奥斯汀分校校园内收集的智能手机数据集上，ALPR的top-1准确率为91.67%，品牌型号识别为66.67%。在公开的UFPR-ALPR数据集上，分别达到了83.05%和61.07%的准确率。自我反思模块进一步将品牌型号识别的平均结果提高了5.72%。这些结果表明，VLMs为可扩展的动态交通视频分析提供了一种经济高效的解决方案。


> Automatic license plate recognition (ALPR) and vehicle make and model recognition underpin intelligent transportation systems, supporting law enforcement, toll collection, and post-incident investigation. Applying these methods to videos captured by handheld smartphones or non-static vehicle-mounted cameras presents unique challenges compared to fixed installations, including frequent camera motion, varying viewpoints, occlusions, and unknown road geometry. Traditional ALPR solutions, dependent on specialized hardware and handcrafted OCR pipelines, often degrade under these conditions. Recent advances in large vision-language models (VLMs) enable direct recognition of textual and semantic attributes from arbitrary imagery. This study evaluates the potential of VLMs for ALPR and makes and models recognition using monocular videos captured with handheld smartphones and non-static mounted cameras. The proposed license plate recognition pipeline filters to sharp frames, then sends a multimodal prompt to a VLM using several prompt strategies. Make and model recognition pipeline runs the same VLM with a revised prompt and an optional self-reflection module. In the self-reflection module, the model contrasts the query image with a reference from a 134-class dataset, correcting mismatches. Experiments on a smartphone dataset collected on the campus of the University of Texas at Austin, achieve top-1 accuracies of 91.67% for ALPR and 66.67% for make and model recognition. On the public UFPR-ALPR dataset, the approach attains 83.05% and 61.07%, respectively. The self-reflection module further improves results by 5.72% on average for make and model recognition. These findings demonstrate that VLMs provide a cost-effective solution for scalable, in-motion traffic video analysis.

[Arxiv](https://arxiv.org/abs/2508.01387)