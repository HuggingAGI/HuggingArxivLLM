# SAM2Auto：基于 FLASH 的高效自动标注工具

发布时间：2025年06月09日

`其他` `人工智能` `视频处理`

> SAM2Auto: Auto Annotation Using FLASH

# 摘要

> 视觉语言模型（VLMs）因标注数据集的稀缺性而落后于大型语言模型，创建配对的视觉-文本标注既费时又昂贵。为突破这一瓶颈，我们推出了SAM2Auto——首个完全自动化、无需人工干预的视频数据集标注管道。我们的方法由两大核心组件构成：SMART-OD，结合自动掩码生成与开放世界目标检测能力的鲁棒系统；以及FLASH，一种多目标实时视频实例分割方法，即使在检测间隙间歇出现时，也能保持目标识别的一致性。与现有开放世界检测方法不同，我们的系统无需特定帧的超参数调整，且误报率低，通过统计方法确保了检测的准确性与目标跟踪的一致性。实验结果表明，SAM2Auto的标注准确性可与人工标注相媲美，同时大幅缩短了标注时间并降低了人力成本。该系统无需重新训练或大量参数调整，即可处理多样化的数据集，为大规模数据集的创建提供了实用解决方案。我们的研究不仅为自动视频标注树立了新基准，更通过突破数据集瓶颈，为加速视觉语言模型的发展开辟了新路径。


> Vision-Language Models (VLMs) lag behind Large Language Models due to the scarcity of annotated datasets, as creating paired visual-textual annotations is labor-intensive and expensive. To address this bottleneck, we introduce SAM2Auto, the first fully automated annotation pipeline for video datasets requiring no human intervention or dataset-specific training. Our approach consists of two key components: SMART-OD, a robust object detection system that combines automatic mask generation with open-world object detection capabilities, and FLASH (Frame-Level Annotation and Segmentation Handler), a multi-object real-time video instance segmentation (VIS) that maintains consistent object identification across video frames even with intermittent detection gaps. Unlike existing open-world detection methods that require frame-specific hyperparameter tuning and suffer from numerous false positives, our system employs statistical approaches to minimize detection errors while ensuring consistent object tracking throughout entire video sequences. Extensive experimental validation demonstrates that SAM2Auto achieves comparable accuracy to manual annotation while dramatically reducing annotation time and eliminating labor costs. The system successfully handles diverse datasets without requiring retraining or extensive parameter adjustments, making it a practical solution for large-scale dataset creation. Our work establishes a new baseline for automated video annotation and provides a pathway for accelerating VLM development by addressing the fundamental dataset bottleneck that has constrained progress in vision-language understanding.

[Arxiv](https://arxiv.org/abs/2506.07850)